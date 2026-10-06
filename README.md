# 3D_Modeling

A collection of general-purpose 3D models I design to solve problems for myself; replacement parts, mounts, holders, adapters, and the occasional one-off fix.

Everything is modeled in [FreeCAD](https://www.freecad.org/) and printed on an FDM printer (bambulab a1, for now).

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

## Notes

- `.FCBak` files are FreeCAD's automatic backups and are not tracked.
- Models are designed to fit my own hardware, so dimensions are specific to the
  part they were made for. Check measurements before printing.
