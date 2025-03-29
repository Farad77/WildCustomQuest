# WildCustomQuest - Monster Hunter Wild Custom Quest Generator

A tool for creating custom quests for Monster Hunter Wild with a user-friendly interface.

**Try it online: [https://farad77.github.io/WildCustomQuest/quest_generator.html](https://farad77.github.io/WildCustomQuest/quest_generator.html)**

## Overview

WildCustomQuest allows you to create custom hunts by selecting monsters, defining rewards, and setting quest parameters through a simple web interface. Generate quest files that can be imported directly into the game for a personalized hunting experience.

## Requirements

This tool requires [Custom Quest Loader](https://www.nexusmods.com/monsterhunterwilds/mods/1096) by kassent to work. Please install the mod before attempting to use custom quests.

Special thanks to kassent for creating the Custom Quest Loader mod that makes this possible!

## Features

- Create quests with custom titles, descriptions, and parameters
- Select from the full monster roster in Monster Hunter Wild
- Add custom rewards with item quantities and drop probabilities
- Multi-language support (English, Japanese, Chinese)
- Export quest files ready for in-game use

## How to Use

1. **Setup**:
   - Install [Custom Quest Loader](https://www.nexusmods.com/monsterhunterwilds/mods/1096) by kassent
   - Follow the mod installation instructions

2. **Creating Quests**:
   - Open `quest_generator.html` in a web browser
   - Fill in quest details (title, description, difficulty, etc.)
   - Select monsters for your quest
   - Configure reward items with quantities and probabilities
   - Generate and download quest files

3. **Installing Quests**:
   - Extract the ZIP file created by the generator
   - Place the `.raw.json` and `.ext.json` files in the appropriate folder as specified by Custom Quest Loader
   - Start the game and enjoy your custom quest!

## File Structure

- `quest_generator.html`: Main application file
- `enemies.json`: Database of all monsters
- `items.json`: Database of all items
- `reward_list_*.json`: Reward templates by language
- `quest_examples/`: Example quest files for reference

## Credits

- This tool was created as a companion to kassent's [Custom Quest Loader](https://www.nexusmods.com/monsterhunterwilds/mods/1096)
- Special thanks to kassent for making custom quests possible in Monster Hunter Wild

## Legal Notice

This is an unofficial fan-made tool and is not affiliated with CAPCOM or Monster Hunter Wild. All game assets and data referenced belong to their respective owners.