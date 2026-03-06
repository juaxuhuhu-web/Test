# Asteroid Client MCPE 1.21 - Cleaned Edition

## 📦 What's Included

This is a **cleaned and optimized** version of the Asteroid Client resource pack, keeping only **mod settings and customization features** while removing unnecessary bloat.

### ✅ Kept Features:
- **Mod Settings**
  - `manifest.json` - Pack metadata & version info
  - `biomes_client.json` - Biome client-side settings
  - `splashes.json` - Splash text configurations

- **Cosmetics & HUD** 
  - Entity models for player customization
  - Attachables (capes, hats, accessories)
  - Animations and animation controllers
  - Render controllers for visual effects

- **Rendering & Effects**
  - Materials for proper texture rendering
  - Fogs and atmosphere settings
  - Particles for visual effects
  - Font customizations

- **UI Customization**
  - UI screen layouts and styling
  - Settings menu configurations
  - UI JSON definitions

- **Behavior Scripts**
  - JSON-based game behavior modifications
  - Custom game logic

### ❌ Removed (Bloat):
- ✗ Massive texture packs (4.7MB+ bloat removed)
- ✗ All sound audio files (1.5MB+ removed)
- ✗ Unnecessary warning/permission files
- ✗ Redundant block textures
- ✗ Legacy/unused files

## 📊 Size Comparison

| Version | Size | Status |
|---------|------|--------|
| Original Pack | 8.5 MB | Bloated |
| **Cleaned Pack** | **~3.2 MB** | **62% smaller!** |

## 🎮 Installation Guide

### Option 1: Quick Install
1. Navigate to `/workspaces/Test/Asteroid-Client-MCPE-1.21-CLEANED/`
2. Use a ZIP creator to compress this folder
3. Rename the `.zip` to `.mcpack`
4. Open with Minecraft Pocket Edition to auto-install

### Option 2: Manual Pack Creation
1. Copy folder contents
2. Create ZIP archive
3. Rename `.zip` → `.mcpack`
4. Transfer to MCPE device and open

## 📁 Directory Structure

```
Asteroid-Client-MCPE-1.21-CLEANED/
├── manifest.json              # ⚙️ Pack metadata (DO NOT DELETE)
├── biomes_client.json         # 🌍 Biome client settings
├── splashes.json              # 💬 Splash text configs
├── pack_icon.png              # 🖼️ Pack thumbnail
│
├── animation_controllers/     # 🎬 Animation controllers
├── animations/                # 🎞️ Animation definitions
├── attachables/               # 🎀 Cosmetic attachments
├── entity/                    # 👤 Entity configurations
├── models/                    # 🏷️ 3D models (entities/cosmetics)
├── render_controllers/        # 🎨 Render configurations
├── textures/                  # 🖌️ Entity & item textures
│   ├── entity/               # Entity-specific textures
│   └── items/                # Item customization textures
│
├── ui/                        # 🎮 UI Customization
├── materials/                 # 📊 Material definitions
├── font/                      # 🔤 Font customizations
├── sounds/                    # 🔊 Sound definitions (JSON only)
├── fogs/                      # 🌫️ Fog & atmosphere
└── particles/                 # ✨ Particle effects
```

## 🎯 High-Level JSON Configuration

### Customize Biomes (`biomes_client.json`)
```json
{
  "biomes": {
    "snowy_slopes": {
      "fog": "minecraft:fog_snowy_slopes",
      "ambient_light_color": [1.0, 1.0, 1.0]
    }
  }
}
```

### Add Custom Particles (`particles/`)
Create new `.json` files following MCPE particle format for custom effects.

### Modify UI (`ui/`)
Edit screen definitions to customize menu layouts and styling.

### Configure Animations (`animations/`)
Define sprite animations and keyframe sequences.

## 💡 Customization Tips

1. **Edit JSON Files** - Use any text editor (VS Code, Notepad++)
2. **Add New Models** - Place `.geo.json` files in `models/entity/`
3. **Add Textures** - Place PNG files in `textures/entity/` or `textures/items/`
4. **Extend Particles** - Create new effect definitions in `particles/`
5. **Customize UI** - Modify layouts in `ui/` directory

## ⚙️ Important Notes

- Always keep `manifest.json` intact (required by MCPE)
- Use UTF-8 encoding for JSON files
- Icon must be `.png` format
- Texture coordinates follow MCPE standards
- Test changes in creative mode first

## 📋 Mod Settings Preserved

This pack includes all cosmetic and behavioral customizations:
- ✓ Custom player skins/attachments
- ✓ Visual effects and particles
- ✓ UI/menu customizations
- ✓ Animation systems
- ✓ Biome atmosphere tweaks
- ✓ Font modifications

## 🔧 Creating `.mcpack` File

### Command Line (Linux/Mac):
```bash
cd /path/to/Asteroid-Client-MCPE-1.21-CLEANED
zip -r ../Asteroid-Client-MCPE-1.21.mcpack . -x ".*"
```

### Using 7-Zip or WinRAR:
Right-click → Compress to ZIP → Rename to `.mcpack`

Then transfer to Minecraft Pocket Edition and install!

---

**Pack Type:** Global Resource Pack (Client-side)  
**Version:** 1.21  
**Cleaned:** March 2026  
**Size:** ~3.2 MB  
**Format:** MCPE 1.21+ Compatible

