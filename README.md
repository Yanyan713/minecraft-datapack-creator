# Minecraft Datapack Creator

A simple, all-in-one batch script to create a **fully structured, empty Minecraft datapack** for any version from 1.16.5 to 1.21.11.

---

## Features
- ✅ **All Minecraft versions** supported (1.16.5 → 1.21.11)
- ✅ **Auto-generates valid `pack.mcmeta`** with the correct `pack_format`
- ✅ Creates a **complete, standard datapack structure**:
  - `functions/`
  - `tags/blocks/items/entities`
  - `recipes/`
  - `advancements/`
  - `loot_tables/`
  - `predicates/`
- ✅ Includes empty `load.json` and `tick.json` tags for easy `/reload`
- ✅ **No scattered files** — everything is created inside a single folder
- ✅ Works for both **Vanilla worlds** and **Fabric/Forge modded environments**

---

## How to Use
1.  **Run the script**: Double-click `datapack_creator.bat`
2.  **Select your Minecraft version** from the menu
3.  **Name your datapack**
4.  The script will create a new folder with your datapack

---

## Installation
  1. Place the generated folder into:
     `.minecraft/saves/[YOUR_WORLD]/datapacks/`
  2. In-game, run `/reload` to activate it.



---

## Notes
- The generated datapack is **empty by default** — you can add your own functions, recipes, and tags.
- Always test your datapack with `/reload` after making changes.
- The `pack_format` is automatically set based on your chosen version.

---
```
MIT License

Copyright (c) 2026 yanyan713

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE CREATOR OF THIS PROJECT CAN TO CHANGE THE LISCENCE.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



