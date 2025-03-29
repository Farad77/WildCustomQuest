# WildCustomQuest - Claude Guidelines

## Project Overview
WildCustomQuest is a JSON-based tool for customizing game data, including enemies, items, missions, and reward lists across multiple languages (EN, JP, CN).

## File Structure
- `enemies.json` - Enemy definitions with multilingual names
- `items.json` - Item definitions with multilingual names
- `missions.json` - Mission definitions with multilingual names
- `reward_list_*.json` - Reward lists by language (en, jp, cn)

## Editing Guidelines
- Maintain JSON structure integrity
- Follow existing format patterns
- Preserve ID references between files
- Keep unique identifiers (`id`, `fixedId`, `label`) unchanged
- Validate JSON after editing

## Naming Conventions
- Use CamelCase for object properties
- Use descriptive keys that match existing patterns
- Maintain consistent spacing and indentation

## Multilingual Support
- All name elements should have translations for all supported languages:
  - `en`: English
  - `jp`: Japanese
  - `cn`: Chinese

## Testing Changes
- Validate JSON syntax: `jsonlint [filename].json`
- Cross-reference IDs between related files
- Ensure all required fields are present

## Import/Export
- JSON files use UTF-8 encoding with CRLF line terminators
- Maintain original file encoding when modifying files