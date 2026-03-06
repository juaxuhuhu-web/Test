# Wolf Client Mod MCPE 1.21 - Mod Menu Only

## 📦 What's Included

**ULTRA-MINIMAL version** - Contains **ONLY essential mod menu settings**. All cosmetics, textures, and visual effects removed.

### ✅ Kept (Mod Menu System):
- `manifest.json` - Required pack metadata
- **Mod menu configs** - Settings and UI
  - Crosshair customization
  - Mods configuration
  - Music/audio settings
  - Interface settings
  - Info settings

### ❌ Removed (ALL Non-Essential):
- ❌ Cosmetics (344KB - models, attachables, capes)
- ❌ Particles (700KB+ - all effects)
- ❌ Animations (28KB all removed)
- ❌ Textures (4.7MB+ ALL REMOVED)
- ❌ Sounds/Audio (1.5MB+ ALL REMOVED)
- ❌ Font customization (180KB)
- ❌ Materials & Renders
- ❌ Entity configurations
- ❌ All visual UI elements

## 📊 Size Comparison

| Version | Size | Reduction |
|---------|------|-----------|
| Original Pack | 8.5 MB | - |
| Cleaned Pack | 3.2 MB | -62% |
| **Mod Menu Only** | **164 KB** | **-98%** ✨ |

## 📁 Directory Structure

```
Wolf-Client-Mod-1.21-CLEANED/
├── manifest.json              # ⚙️ REQUIRED - Pack metadata
└── ui/
    └── .uidx/
        ├── mod_menu/          # 🎮 Mod menu configurations
        │   ├── crosshair_section.json
        │   ├── drawable.json
        │   ├── mods_section.json
        │   └── music_section.json
        ├── settings/          # ⚙️ Mod settings
        │   ├── Info.json
        │   ├── Interface.json
        │   └── Mods.json
        └── other/             # 📊 UI assets
            ├── assets.json
            ├── wolfclientmod_hud.json
            ├── images.json
            └── pause_button.json
```

## 🎮 Installation

1. Navigate to `/workspaces/Test/Asteroid-Client-MCPE-1.21-CLEANED/`
2. Create ZIP archive of all contents
3. Rename `.zip` → `.mcpack`
4. Open with Minecraft Pocket Edition to install

Or use command:
```bash
cd /workspaces/Test/Asteroid-Client-MCPE-1.21-CLEANED && zip -r ../Asteroid-Client-MCPE-1.21-Pure.mcpack .
```

## 🔧 Mod Menu System

This pack includes functional mod menu system:
- **Crosshair Settings** - Customize crosshair appearance
- **Mods Section** - Enable/disable mods
- **Music Settings** - Audio customization
- **Interface** - UI customization options
- **Information** - Pack info

## ⚙️ Modifying Configs

Edit JSON files with any text editor:
```bash
# Edit mod menu settings
nano ui/.uidx/mod_menu/mods_section.json

# Edit mod settings
nano ui/.uidx/settings/Mods.json
```

## ⚠️ Important

## ⚠️ Important Notes

- **manifest.json** is REQUIRED - do not delete
- All files use UTF-8 encoding
- Pack is MCPE 1.21+ compatible
- Only contains mod menu - no visual customization
- Minimal footprint (164 KB) for fast loading

---

**Pack Type:** Mod Menu Configuration Only  
**Version:** 1.21  
**Optimized:** March 2026  
**Size:** 164 KB (Ultra-minimal!)  
**Type:** Global Resource Pack

