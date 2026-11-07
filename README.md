# ITB STIKOM Bali Campus Building Plugin for TheoTown

A custom 2.5D isometric pixel art simulation building plugin for the city-building simulation game TheoTown. This modification introduces an authentic digital replica of the ITB STIKOM Bali Renon campus into the game engine, complete with functional educational simulation attributes, wide urban influence radii, and multiplatform compatibility.

## Overview

In the TheoTown city simulation ecosystem, higher education institutions are predominantly modeled after generic Western institutional architecture. This plugin introduces an authentic Indonesian academic landmark into the game. Designed with Balinese architectural elements (multi-tiered roof profiles, entrance gateways, and regional building accents), the asset acts as a functional higher education facility that elevates residential literacy metrics and surrounding land value.

## Simulation Parameters and Engine Specifications

The building is configured via `code.json` adhering strictly to TheoTown Plugin API specifications:

| Parameter | Value | Description |
|:---|:---|:---|
| Plugin Identifier | `$gekaaaaa.education.2026-01-19-08:59:25.562` | Unique system registry ID |
| Manifest Identifier | `$manifest-d6826706-1141-40a5-b360-d5ca5708da9b` | Manifest registry entry |
| Footprint Dimension | 5 x 5 Tiles | Land area footprint |
| Building Type | `education` | Categorized under the Education service tree |
| Student Capacity | 2,500 Students | Low and high education capacity threshold |
| Influence Radius | 700 Tiles | Spherical urban coverage radius |
| Education Provision | 1,000 - 2,500 Points | Educational aspect points provided |
| Ground Rendering | `draw ground: true` | Seamless terrain blending with native game ground |
| Build Time | Instant (0s) | Configured for sandbox and standard city builders |

## Visual Design & Projection

- 2.5D Isometric Dimetric Projection: Pixel artwork rendered according to TheoTown standard projection angles (true 2:1 isometric ratio).
- Cultural Architectural Detailing: Captures the architectural identity of the ITB STIKOM Bali Renon campus, including tiered roof forms and cultural entrance aesthetics.
- Texture Optimization: Clean 32-bit PNG sprite texture (`StikomBali.png`) optimized for rendering performance across mobile and desktop GPUs.

## Project Structure

```
PLUGIN-STIKOM-BALI-THEOTOWN/
├── code.json        # Engine parameter definitions and educational simulation attributes
├── plugin.manifest  # TheoTown Plugin Manager metadata manifest
├── StikomBali.png   # 2.5D isometric pixel art sprite atlas
├── preview.png      # In-game daytime gameplay showcase screenshot
└── README.md        # Technical documentation
```

## Installation Guide

### Android Installation

1. Download or clone this repository folder.
2. Using a mobile file manager (e.g., ZArchiver or default Files app), copy the plugin folder into:
   ```text
   Android/data/info.flowersoft.theotown.theotown/files/plugins/
   ```
3. Restart TheoTown.
4. Open the **Services > Education** building catalog to place the campus in your city.

### PC (Windows / Steam) Installation

1. Download or clone this repository folder.
2. Copy the entire folder into your local TheoTown plugins directory:
   ```text
   C:\Users\<YourUsername>\TheoTown\plugins\
   ```
   *(Or inside your Steam library: `steamapps\common\TheoTown\plugins\`)*
3. Launch TheoTown via Steam or the desktop client.
4. Access the **Education** menu and place the building.

## Compatibility

- TheoTown Version: Compatible with all modern mobile (Android, iOS) and desktop (Steam PC) releases.
- Plugin Manager: Compatible with in-game TheoTown Plugin Store guidelines.

## Author

Anak Agung Ngurah Krisna Artha Wibawa ([ANTARTICA1](https://github.com/ANTARTICA1))  
Creator Alias: Gekaaaaa

## Disclaimer

This is a community-created modification for the game TheoTown (developed by Blueflower / Flower Software). All rights to TheoTown belong to their respective owners.