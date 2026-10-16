# Guild v1.1

Local-only Fabric client mod for **ally** and **enemy** tags with **gradient colours**.
Shows in your tab list and above-head nametags. Fully offline.

## Features

- Allies + enemies (separate tags & gradients)
- Multi-stop gradient tags (1–6 hex colours)
- Liquid Glass GUI (**G** or `/guild`)
- Tab list + nametag rendering (client-side only)

## Commands

| Command | Effect |
|--------|--------|
| `/guild` / `/g` | Open menu |
| `/guild add <ign>` | Add ally |
| `/guild enemy <ign>` | Add enemy |
| `/guild remove <ign>` | Remove either |
| `/guild list` | List both |
| `/guild tag <tag>` | Ally tag |
| `/guild etag <tag>` | Enemy tag |
| `/guild colors #A #B …` | Ally gradient (1–6) |
| `/guild ecolors #A #B …` | Enemy gradient |
| `/guild style BRACKETS\|PIPE\|PLAIN` | Bracket style |
| `/guild gradient` | Toggle gradient / solid |
| `/guild toggle` | Show/hide all tags |

## Build

```bash
cd GuildLocal
gradle build
# JAR → build/libs/guild-1.1.0.jar
```

MC **1.21.11** + Fabric API.

## Data

```
.minecraft/config/guild-data.json
.minecraft/config/guild.json
```

Tags are only visible to **you**.
