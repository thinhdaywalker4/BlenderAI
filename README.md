# BlenderAI — Trial Version

**Control Blender with Claude Desktop through MCP (Model Context Protocol).**

BlenderAI lets Claude Desktop work directly inside Blender: run code, read scene and object info, capture viewport screenshots, and import models/materials from your local asset library.

> ## 🚀 Want the Full Version?
> ### 👉 **[Get BlenderAI Full Version on Gumroad](https://aiblender.gumroad.com/l/khaap)**
> https://aiblender.gumroad.com/l/khaap

---

## What's in this repo

| Folder | Description |
| --- | --- |
| `BlenderAI_Sever/` | MCP server, Blender add-on packages (`cp310`–`cp314`), installer scripts, and the installation guide (PDF) |
| `Trial Package/` | Sample asset library for the trial: 11 OBJ models with materials/textures |

### Trial asset list

Bush with radiating leaves · Coconut tree · Coffee cup · Floor lamp with patterned shade · Fork · German Shepherd dog · Patterned saucer plate · Spoon · Women's bicycle with rear rack · Wooden cafe chair · Wooden table (street-style)

## Requirements

- Windows PC, 64-bit (AMD64)
- Python **3.10 – 3.14** (AMD64 build, with *"Add python.exe to PATH"* checked)
- Blender **3.x – 5.x**
- [Claude Desktop](https://claude.ai/download), signed in with your Claude account

## 🎬 Video tutorial

Watch the step-by-step setup and demo on YouTube (click the image to play):

[![BlenderAI video tutorial](https://img.youtube.com/vi/nRSr5EOqbkM/maxresdefault.jpg)](https://youtu.be/nRSr5EOqbkM)

👉 https://youtu.be/nRSr5EOqbkM

## Quick install

1. Download this repo (**Code → Download ZIP**) or grab the ready-made ZIP from the [Releases](../../releases) page, then extract it to a fixed folder (e.g. your Desktop).
2. Open the `BlenderAI_Sever` folder and double-click **`INSTALL.bat`**.
3. If the `.bat` fails, follow **`INSTALL IF BAT FAIL.txt`** to install manually.
4. Restart Claude Desktop and Blender, then enable the BlenderAI add-on in Blender.

For screenshots and full details, see **`BlenderAI_Sever/BlenderAI_Installation_Guide.pdf`**.

To uninstall, run `remove_blenderai_en.bat`.

## Trial vs Full

This repository contains the **Trial** version with a small sample asset package. To unlock the **Full Version**, get it here:

👉 **https://aiblender.gumroad.com/l/khaap**

## License

BlenderAI is released under a **personal-use license** — see [`BlenderAI_Sever/LICENSE.md`](BlenderAI_Sever/LICENSE.md). You may not redistribute, resell, or reverse engineer the Software. It includes code derived from [blender-mcp](https://github.com/ahujasid/blender-mcp) (MIT License).

## Acknowledgments

❤️ Huge thanks to **[ahujasid](https://github.com/ahujasid)**, the author of the original **[blender-mcp](https://github.com/ahujasid/blender-mcp)** project (MIT License). BlenderAI builds on that foundation, and this project would not exist without their work. If you like this idea, please go give the original repo a ⭐ too!

## Contact

**Thinh Nguyen** — thinhdaywalker4@gmail.com
