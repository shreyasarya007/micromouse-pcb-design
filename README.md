# Micromouse PCB Designs

Two user-supplied KiCad design versions, prepared as a minimal public source copy.

## Open a version

| Version | Project | Schematic | Board |
| --- | --- | --- | --- |
| Version 1 | [Project](Version1/micromouse.kicad_pro) | [Schematic](Version1/micromouse.kicad_sch) | [PCB](Version1/micromouse.kicad_pcb) |
| Version 2 | [Project](Version2/micromouse.kicad_pro) | [Schematic](Version2/micromouse.kicad_sch) | [PCB](Version2/micromouse.kicad_pcb) |

Both board files identify KiCad 9.0 as their generator. Install a compatible KiCad version and the appropriate standard libraries. The six native files are byte-identical to the supplied design files: no connectivity, geometry, symbol, footprint, or source-attribution field was edited for publication.

## Deliberately omitted

- Downloaded 3D models and separate symbol/footprint library collections whose individual provenance was not fully documented.
- Historical ZIPs, manufacturing outputs, backups, editor history, local editor state, caches, lock files, screenshots, and the component workbook.
- Original upload archives and private preservation copies.

The board and schematic files already contain embedded symbol/footprint data. Updating those items from external libraries may require local library configuration; no `sym-lib-table` or `fp-lib-table` was supplied. Version 1 references `KICAD8_3DMODEL_DIR`; version 2 references `KICAD9_3DMODEL_DIR` and project-relative 3D files. Missing model files are intentional in this public copy. No placeholders or substitute electrical parts have been added.

## Attribution and limits

See [THIRD_PARTY.md](THIRD_PARTY.md) for the known SnapMagic/SnapEDA and KiCad sources and their design exceptions. Source links embedded in the native files remain intact. Some custom blocks do not carry an independent author/source record; this preparation is not a comprehensive ownership or legal-clearance determination. No blanket license has been assigned to all project content.

No KiCad application validation, ERC, DRC, fabrication, assembly, or hardware test was run during this preparation. The files are design sources, not a certified manufacturing release.
