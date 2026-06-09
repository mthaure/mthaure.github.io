# My Room — Interactive Portfolio

## Setup (3 steps)

### 1. Export your Blender model
- File → Export → **glTF 2.0 (.glb/.gltf)**
- Choose **GLB** format
- Save as `room.glb` **in this same folder**

### 2. Name your objects in Blender
Select each clickable object and press **F2** to rename it:

| Blender object name | Opens page     |
|---------------------|---------------|
| `monitors`          | Projects       |
| `bike`              | Hobbies        |
| `certificates`      | Career         |
| `cat`               | About Me       |

You can add more in `index.html` under the `CONFIG.objectMap` section.

### 3. Run a local server
Open this folder in VS Code, then open the **terminal** and run:

```
npx serve .
```

Then open http://localhost:3000 in your browser.

> ⚠️ You MUST use a local server — opening index.html directly won't load the .glb file.

---

## Customising content
Open `index.html` and edit the **CONFIG** and **PAGES** sections at the top. That's all you need to touch.

## Controls
- **Click** a highlighted object → opens its page
- **Drag** to orbit the camera
- **Scroll** to zoom
