# Minecraft Litematic import checklist (Java)

A short, tested checklist for getting a `.litematic` into Litematica on Minecraft Java Edition. Built for builders using [Minecraft Schematic Generator](https://minecraftschematicgenerator.com/help) (fixed build types → `.litematic` / `.schem`).

Not affiliated with Mojang or Microsoft.

## 1. Get a file

- Compile a build on the [generator help workbench](https://minecraftschematicgenerator.com/help) (13 shapes, palette, size), **or**
- Convert an existing file with the free [schematic converter](https://minecraftschematicgenerator.com/schematic-converter) (browser-only, no upload).

Prefer `.litematic` for holograms + material lists. Prefer `.schem` for WorldEdit / FAWE paste. Format notes: [litematic vs schem](https://minecraftschematicgenerator.com/litematic-vs-schem).

## 2. Put it in the right folder

Use the **launching instance** `schematics` folder (MultiMC / Prism / official launcher each have their own). Full paths: [how to load a litematic](https://minecraftschematicgenerator.com/how-to-load-litematic-in-litematica).

Common failure: the browser saved `name.litematic.txt`. Remove the extra `.txt`.

## 3. Load in-world

1. Install Fabric + matching MaLiLib + Litematica for your game version.
2. Open a world → press **M** → **Load Schematics** → create a placement.
3. If the list is empty, fix the folder / double extension first — [schematic not showing](https://minecraftschematicgenerator.com/litematica-schematic-not-showing).

## 4. Farmhouse example

On the workbench: Build → Farm, Blocks → Oak, size 15×7×13. Dedicated notes: [minecraft farm schematic](https://minecraftschematicgenerator.com/minecraft-farm-schematic).

## Limits (site, as of 2026-10)

- Free: 1 build / UTC day, ≤20 on a side
- Extra builds: $2.99 each, one-time (no subscription)
- Java only — no Bedrock `.mcstructure`

## License

CC0-1.0 — checklist text is public domain. Product names belong to their owners.
