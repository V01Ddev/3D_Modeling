# 3D_Modeling

A collection of general-purpose 3D models I design to solve problems for myself —
replacement parts, mounts, holders, adapters, and the occasional one-off fix.

Everything is modeled in [FreeCAD](https://www.freecad.org/) and printed on an FDM printer.

## Layout

Each project gets its own folder containing the FreeCAD source and its exports:

```
<Project Name>/
├── <Project Name>.FCStd    # FreeCAD source (the editable original)
├── <Project Name>.stl      # Mesh export, ready to slice
└── <Project Name>.3mf      # Print-ready export, where present
```

`.FCStd` is the source of truth. The `.stl` / `.3mf` files are exports for printing —
they're committed so a model can be printed without opening FreeCAD.

## Projects

- Antenna Holder
- Antenna Rig
- Bag Hook
- Bathroom Organizer
- Bit Holder
- Book Protector
- CigV10
- Cutting Chuck
- Diamond Sharpener Holder
- Drill Table Saw
- FETCH 2 Battery Mod
- Fishing Rod Clip
- FlySky i6x USB Mod
- FPV Drone Backpack Strap
- IAU
- Kallax Wall Extension
- Keycap
- LAGKAPTEN Bag Hook
- Mic Spacer
- Milat Fridge Fix
- Onvo MX03 Hook
- Perfume Testers Stand
- Phone Stand
- PS Holder
- RM Pocket Stick Ends
- Roll Down Curtain Fix
- Shataf Holder
- Side Bag Hook
- Simple Plane
- Snake Medal
- Tertial Microscope Adapter
- Toner Transfer Tool
- Traffic Light Mount
- Traffic Light Stand
- UK Plug Case
- Vape Holder

## Notes

- `.FCBak` files are FreeCAD's automatic backups and are not tracked.
- Models are designed to fit my own hardware, so dimensions are specific to the
  part they were made for. Check measurements before printing.
