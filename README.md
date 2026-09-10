# Six-channel relay module

SPHA six-channel relay/light-output module.

## Design files

- `relay-module-light.kicad_pro` — KiCad project
- `relay-module-light.kicad_sch` — top-level schematic
- `relay-module-light.kicad_pcb` — PCB layout
- Additional `.kicad_sch` files — hierarchical schematic sheets
- `models/` — project-specific 3D and mechanical models

## Working with the project

Open the `.kicad_pro` file in KiCad. The design includes files originating from an older KiCad workflow; review schematic links, footprints, design rules, zones, and manufacturing outputs after any conversion or upgrade.

KiCad source files and project-specific libraries are the source of truth. Generated BOM, Gerber, assembly, and fabrication-house outputs are excluded from the repository; regenerate and verify them before manufacturing.

## Repository notes

Temporary KiCad state, locks, autosaves, and backup directories are excluded by `.gitignore`. Board revision, tested KiCad version, manufacturing revision, and hardware/firmware compatibility still need to be recorded when provenance is confirmed.
