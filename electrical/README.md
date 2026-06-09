# Electrical (EE) Documentation

This folder is for the **electrical / EE** team. Anything related to the ROV's
circuits, wiring, power, or sensor integration goes here.

> Only EE contributors should commit to this folder. See the
> [root README](../README.md) for the full contribution rules.

## What Belongs Here

- Schematics and circuit design notes
- Wiring diagrams and harness documentation
- Connector and pinout references
- Power budget and power distribution design
- PCB layout notes and design decisions
- Sensor datasheets and integration notes
- Battery, fusing, and protection design
- Test procedures and bring-up checklists

## Suggested Subfolders

Use these as the project grows. Create them only when you have something to
put in them.

- `schematics/` — circuit design documents and exports (PDF/PNG)
- `wiring/` — harness drawings, connector tables, pinouts
- `power/` — power budget, distribution, battery and fusing notes
- `sensors/` — datasheets, integration notes, calibration procedures

## Conventions

- File names: lowercase with hyphens, for example `power-budget-v2.md`.
- Always include voltage, current, and tolerance information on diagrams.
- For schematic and PCB source files, link to the source repo or shared
  drive. Commit exported PDFs/PNGs here for easy reading.
- Include revision numbers and dates on schematics and power budgets so
  readers can match the documentation to the hardware version.

## Cross-Team Coordination

Electrical decisions often constrain mechanical (component sizes, mounting,
heat) and software (protocols, pinouts, sensor behavior). When something
changes here that affects another team, update this folder and notify them so
they can update their own documentation. Do not edit their folders directly.
