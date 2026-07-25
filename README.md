# EAW_Changes_Mod

A custom mod for Star Wars: Empire at War (compatible with Forces of Corruption) that adds new units, balance tweaks, and gameplay enhancements to refresh the vanilla experience while preserving core balance.

## Overview

This mod introduces new capital ships, ground and space units, hero units, and campaign/skirmish balance adjustments. Changes focus on adding strategic variety without breaking multiplayer compatibility.

### New Heroes
- **Colonel Wulff Yularen** - A veteran commander from the Clone Wars, and head of the ISB. Colonel Yularen brings decades of strategic command to the Imperial fleet, commanding The Resolute, an enhanced Venator-class Star Destroyer.

### New Units
- **Venator-class Star Destroyer** - Heavy attack cruiser from The Clone Wars, formerly commanded by Jedi Generals featuring massive hangars, which provide significant starfighter support, making it perfect for escorting larger capital ships. Garrison includes:
    - **Empire Y-Wings** - New Empire fighter variant with specialized bombing capabilities
    - **Empire V-Wings** - New Empire fighter variant

### Changes to Existing Units
- **Home One and Mon Calamari Cruisers** - Now equipped with a hangar to deploy star fighters

## Notable Additions
- Mon Calamari cruisers updated to include hangar functionality.

## Modified Files

Common XML and asset files modified by the mod:
- Data/XML/Factions.xml — faction composition & unit availability
- Data/XML/GameObjectFiles.xml — game object registration
- Data/XML/Hardpoints.xml and MOD_Hardpoints_*.xml — weapon & hardpoint configs
- Data/XML/MOD_Containers.xml — unit containers and garrisons
- Data/XML/CAMPAIGNS_*_GC.xml — campaign adjustments
- Data/Audio, Models, Textures — added or overridden assets

## File Structure

```
EAW_Changes_Mod/
├── Data/
│   ├── XML/            # XML configs
│   ├── Models/         # 3D models (overrides/additions)
│   ├── Textures/       # Textures and UI sprites
│   ├── Audio/          # SFX and voice overrides
│   └── SFX/            # Visual effects
└── README.md
```

## Installation

1. Locate the game's Data directory (e.g., your Steam install path).
2. Create a Mods folder inside the game's Data directory if needed.
3. Copy the `EAW_Changes_Mod` folder into the `Mods` folder.
4. Launch the game. From the main menu choose Options → Mods and enable `EAW_Changes_Mod`.
5. Start a new campaign or skirmish to ensure changes load properly.

## Compatibility

- Game: Star Wars: Empire at War (Forces of Corruption compatible)
- Single-player and skirmish supported. For multiplayer, ensure all players use identical mod files to avoid desyncs.

## Notes & Known Issues

- Experimental/test files may remain in `Test` or `OLD` folders — safe to remove for a cleaner install.
- Generated files should be edited via their generation workflow where applicable.
- If crashes occur, remove the mod folder to test vanilla game stability.

## Credits

Created by the modding community to expand unit variety and balance. Thanks to contributors for models, textures, and testing.

## Disclaimer

This community-created mod is not affiliated with Petroglyph Games, LucasArts, or Steam. Use at your own risk.
