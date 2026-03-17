# Warmage 2024 Foundry Starter

This bundle is a **clean source starter** for a 2024 Warmage implementation for Foundry VTT.

What is included:
- one cleaned class source file for Warmage 2024
- Arcane Initiations as separate source items
- core class features as separate source items
- all subclass source items with level-by-level summaries
- major subclass feature source items
- a starter tricks reference pack
- a starter spell list reference file

What is **not** fully automated yet:
- live compendium UUID relinking
- auto-granted subclass features during level-up
- fully imported dnd5e pack databases
- complete itemized spell and trick automation

Why this shape:
Foundry class advancement automation depends on stable compendium UUIDs. Those UUIDs do not exist until the final packs are imported and built inside a real Foundry world/module workflow. So this starter keeps everything **namespaced and clean** without broken Valda links.

## Suggested use
1. Create a new module folder in your Foundry `Data/modules/` directory.
2. Copy the contents of this `module/` folder into it.
3. Import the JSON source items into your preferred compendiums or world folders.
4. After import, relink the class advancement entries to your own created compendium UUIDs.

## Namespacing
All identifiers use the `warmage2024.*` namespace to avoid conflict with older Valda / 2014 content.

## Important note
This bundle is meant to be a **solid build base**. It removes the broken legacy UUID references from the uploaded class export and gives you a clean place to finish pack linking.
