# 🔥 Campfire Tales

A Minecraft plugin that brings players together around campfires to share mysterious tales and receive group buffs.

## Features

- 🔥 When 2 or more players sit near an active campfire, they enter "Story Mode"
- 📖 Players receive random tales about the world's lore, secrets, and mysteries
- 🌟 Groups receive beneficial effects that last 30 minutes:
  - Regeneration
  - Luck
  - Night Vision
  - Conduit Power
- ⭐ More players = stronger buffs and rarer stories
- 🔄 Stories rotate weekly, encouraging regular gatherings

## Requirements

- Paper 1.21.4
- Java 17 or higher

## Installation

1. Download the latest release from the releases page
2. Place the jar file in your server's `plugins` folder
3. Restart your server
4. The plugin will generate default configuration files

## Usage

### For Players

Simply gather around a campfire with at least one other player. Stories will automatically begin after a few seconds, and you'll receive group buffs!

The more players gather around, the better the buffs and the rarer the stories you might hear.

### Permissions

- `campfiretales.admin` - Access to administrative commands

## Configuration

Stories are configured in `plugins/CampfireTales/stories.yml`. They are categorized into three tiers:
- `default` - Common stories
- `uncommon` - Requires at least 2 players
- `rare` - Requires at least 4 players

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
