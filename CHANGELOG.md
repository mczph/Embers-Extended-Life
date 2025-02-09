# Embers Unofficial Extended Life

A dwarven magic mod

## v1.23.0 - Finished Compatibility
### Changes
- merged various test branches into the main branch
- tweaked build scripts
- updated README.md to explain all compatibility options

### Bugfixes
- added compatibility with Embers' Construct
- added missing Dawnstone Anvil recipes
- added missing localization for Caminite Large Bricks
- added missing recipe for Caminite Large Bricks

## v1.22.5 - Soot
### Changes
- removed the integrated version of Soot
  - it is now a separate mod again
  - I now maintain a fork of Soot, which is compatible with Embers Unofficial Extended Life
- the original Soot mod is now incompatible

## v1.22.4 - Compatibility
### Bugfixes
- fixed broken mixins for mystical gears
- fixed incompatibility with Thaumic Periphery
- fixed incompatibility between Mystical Mechanics and Thaumic Periphery
- fixed incompatibility with Polymancy
- fixed incompatibility with Embersified

## v1.22.3 - Compatibility
### Bugfixes
- fixed incompatibility with Ore Stone Variants
  - instead of crashing it now just disables ores that are not registered
- small tweak to the recipe registry to avoid registering recipes for disabled metals

## v1.22.2 - Compatibility
### Bugfixes
- fixed incompatibility with Aetherworks
- fixed incompatibility with Aetherium Ashen Armor
- fixed recipe registration of tools if the metal is disabled
- fixed crash when placing blocks, while aetherworks is installed

## v1.22.1 - Compatibility
### Bugfixes
- fixed incompatibility with JAOPCA
- fixed incompatibility with Mystical Gears
- fixed possible IndexOutOfBoundsException in Stamping compatibility

## v1.22.0 - Soot
### Changes
- integrated Soot into Embers
  - this makes Embers Unofficial Extended Life incompatible with the Soot mod on CurseForge
  - consider this as a beta release for now, as there might be some issues with the integration
- refactored the Soot config system
  - this allows editing the Soot config in-game
  - moved the config to the Embers config folder
- added a new config option to disable the Soot integration

### Bugfixes
- fixed a CraftTweaker issues that prevented the brewing recipes in Soot from working

## v1.21.1 - Bugfixes
### Changes
- added a new material registration mode, to only register the metal seed
- refactored the recipe registration to use the new material registration mode

### Bugfixes
- fixed missing registration of the clockwork attenuator
- fixed crash with UniDict, when some metals are disabled
- fixed registration of broken recipes, when some metals are disabled
- fixed registration of OreDict entries for disabled metals

## v1.21.0 - Config Rework
### Changes
- reworked the whole config system
  - switched from a single file to a folder
  - added a bunch more config options for tools, world gen, ...
  - added a config to enable most of the WIP stuff that never made it into the mod
- fixed a bunch of missing model issues with the WIP items and added the missing localization
- updated dependencies
- added 2 new stamps (thanks to @InvaderMonky for the textures)
- added stamping recipes for EnderIO & Endergy Grinding Balls
- added stamping recipes for metal rods if they are registered by another mod
- changed the Melter to ignore items in the OFFHAND slot

### Bugfixes
- fixed dupe bug with melter and acceleration mods

## v1.20.1
### Bugfixes
- fixed crash when using the Dawnstone Anvil (KorewaLidesu)

## v1.20.0 - UEL
### Changes
- added CHANGELOG.md
- added Heat Coil as smelting catalyst in HEI
- added a project logo
- added compatibility with Inspiration Cauldrons
- added config option to show exact Ash amount in Alchemy recipes
- switched to RetroFuturaGradle
- updated README.md
- updated repository dependencies
- updated various lang files

### Bugfixes
- fixed Alchemy Table breaking after 240 hours
- fixed missing localizations
- tweaked Metallurgic Dust recipe, so it won't hash to 0
