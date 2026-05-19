# TibiaHunt — Monster Spawn Finder

A fan-made interactive map for finding monster spawn locations in Tibia.

## Features
- Search for monsters by name
- Click a spawn entry to jump to the exact location on the map
- Coordinate data sourced from TibiaWiki

## How to add a monster
Open `monsters.json` and follow this pattern:

```json
{
  "name": "Rotworm",
  "image": "https://tibia.fandom.com/wiki/Special:Redirect/file/Rotworm.gif",
  "spawns": [
    { "x": 32369, "y": 32450, "floor": 7, "label": "Rookgaard Caves" }
  ]
}
```

## Credits
- Map tiles: TibiaMaps.io
- Spawn data: TibiaWiki
- Not affiliated with CipSoft