# 8051

KiCad design files for 8051.

## Project files

- [8051 Breakout Board/8051_breakout.kicad_pro](8051%20Breakout%20Board/8051_breakout.kicad_pro)
- [8051 Development Board v2/8051.kicad_pro](8051%20Development%20Board%20v2/8051.kicad_pro)
- [8051 Development Board/8051.kicad_pro](8051%20Development%20Board/8051.kicad_pro)
- [8051 ultra/Ultra_DB_X51_v1.kicad_pro](8051%20ultra/Ultra_DB_X51_v1.kicad_pro)
- [8051 ultra/Ultra_DB_X51_v1.pro](8051%20ultra/Ultra_DB_X51_v1.pro)
- [8051 ultra/file549BD866.kicad_pro](8051%20ultra/file549BD866.kicad_pro)
- [8051 ultra/file549BD866.pro](8051%20ultra/file549BD866.pro)
- [8051 ultra/file549BDEFB.pro](8051%20ultra/file549BDEFB.pro)
- [8051 ultra/file549BE66B.pro](8051%20ultra/file549BE66B.pro)

Open the appropriate `.kicad_pro` file in KiCad; `.pro` entries are legacy projects. Keep schematics, boards, local libraries, library tables, and supporting files together. Hierarchical schematic sheets are part of their parent design.

## Git workflow

Automatic backups, recovery files, editor state, and filesystem metadata are ignored. Existing fabrication outputs and local component libraries are retained. For existing repositories, ignore rules do not automatically untrack previously committed files.

Review and save a meaningful design revision with:

```sh
git status --short
git diff
git add -- <changed-files>
git commit -m "Describe the design change"
```

## Documentation images

Add a clear 3D board view at `docs/images/board-3d.png` and, optionally, a PCB layout view at `docs/images/pcb-layout.png`. A schematic PDF is useful for reading circuit details. Once present, embed an image in this README with `![Board 3D view](docs/images/board-3d.png)`. For folders with several designs, use a separate named image for each.

## Design notes to complete

Describe purpose, power and connectors, revision status, assembly requirements, and what has been physically tested. The repository setup does not establish electrical correctness or manufacturing readiness.

## Repository portability notes

- Computer-specific library path: `8051 ultra/fp-lib-table` → `H:\\PCB_Designes\\LPC1768 Stick1\\lib_new\\logo.pretty`.
- Computer-specific library path: `8051 ultra/fp-lib-table` → `H:\\PCB_Designes\\LPC1768 Stick1\\lib_new\\New_Logo.pretty`.
