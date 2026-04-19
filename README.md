# ComponentLib+

KiCad component library containing custom symbols, footprints, 3D models, and related library assets.

## Repository layout

- `symbols/` - schematic symbols and library backups
- `footprints/` - footprint libraries in `.pretty` folders
- `3dmodels/` - associated 3D model files
- `simulation/` - simulation assets, if used

## Using the library in KiCad

1. Clone or download this repository.
2. Add the symbol libraries from `symbols/` in KiCad's Symbol Library Manager.
3. Add the footprint libraries from `footprints/` in KiCad's Footprint Library Manager.
4. Point any footprint 3D model references to `3dmodels/` if needed.

## Notes

- The repository is organized so it can be published directly to GitHub.
- Generated caches and editor-specific files are ignored by default.