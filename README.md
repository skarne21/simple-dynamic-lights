# Simple Dynamic Lights

A lightweight Minecraft datapack that adds dynamic lighting when holding light-emitting items. No mods required — pure vanilla datapack.

## Features

- **Mainhand & Offhand lighting** — Hold any supported item and light follows you
- **Head slot lighting** — Wear a Jack o' Lantern as a helmet for hands-free lighting
- **Multiple light levels** — Items emit light at their realistic vanilla levels
- **Lightweight** — Only 14 files, no overlays, no bloat
- **No setup required** — Just install and it works

## Supported Items

| Light Level | Items |
|---|---|
| **15** | Glowstone, Lantern, Sea Lantern, Jack o' Lantern, Beacon, Conduit, Shroomlight, Campfire, Lava Bucket, Redstone Lamp, all Froglights |
| **14** | Torch, End Rod, Fire Charge |
| **10** | Soul Torch, Soul Lantern, Soul Campfire, Crying Obsidian, Enchanted Golden Apple |
| **7** | Redstone Torch, Glow Berries, Glow Ink Sac, Glow Item Frame |

## Installation

1. Download the `.zip` from [Modrinth](https://modrinth.com/datapack/simple-dynamic-lights) or from the [Releases](../../releases) page
2. Place it in your world's `datapacks` folder (`saves/<world name>/datapacks/`)
3. Run `/reload` in-game or rejoin the world
4. Hold a torch and walk into the dark!

## Compatibility

Built and tested for **Minecraft 26.2 Snapshot 7** (pack format 105).

## Uninstalling

1. Remove the zip from your `datapacks` folder
2. If any lights got stuck, run:
   - `/kill @e[type=minecraft:marker,tag=dynlight]`
   - `/fill ~-50 ~-50 ~-50 ~50 ~50 ~50 air replace minecraft:light`

## License

[MIT](LICENSE)
