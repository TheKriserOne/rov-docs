# Mechanical (ME) Documentation

This folder is for the **mechanical / ME** team. Anything related to the ROV's
physical structure, drivetrain, buoyancy, or assembly goes here.

> Only ME contributors should commit to this folder. See the
> [root README](../README.md) for the full contribution rules.

## What Belongs Here

- Frame and chassis design notes
- Thruster selection, mounting, and orientation
- Buoyancy, ballast, and trim calculations
- CAD references (file lists, export notes, links to source files in CAD repos
  or shared drives)
- Assembly and disassembly instructions
- Materials specifications and sourcing notes
- Tolerance, fastener, and waterproofing decisions
- Maintenance and inspection procedures

## Suggested Subfolders

Use these as the project grows. Create them only when you have something to
put in them.

- `cad/` — CAD file references, export notes, drawings (PDF/PNG)
- `assembly/` — build guides, exploded views, step-by-step instructions
- `materials/` — material choices, sourcing, vendor links
- `calculations/` — buoyancy, stress, tolerance, and trim notes

## Conventions

- File names: lowercase with hyphens, for example `frame-buoyancy-calc.md`.
- For large binary files (CAD exports, high-res photos), prefer linking to
  external storage over committing huge files. If a binary must live in the
  repo, keep it small and document why it is needed.
- Include units on every measurement and a date on every calculation so
  future readers know what version of the design it reflects.

## Cross-Team Coordination

When mechanical changes affect electrical (for example, mounting points for a
PCB) or software (for example, thruster layout that affects the control
mixer), update this folder and notify the affected teams so they can update
their own documentation. Do not edit their folders directly.
