# Software (CS) Documentation

This folder is for the **software / CS** team. Anything related to the ROV's
code, control systems, communications, or deployment workflow goes here.

> Only CS contributors should commit to this folder. See the
> [root README](../README.md) for the full contribution rules.

## What Belongs Here

- Control software architecture and design notes
- Firmware documentation (build instructions, flashing, configuration)
- Communication protocol specs (serial, CAN, Ethernet, etc.)
- API and interface documentation between subsystems
- Deployment, build, and release procedures
- Debugging guides and known issues
- Tooling notes (IDE setup, toolchains, dependencies)

## Suggested Subfolders

Use these as the project grows. Create them only when you have something to put
in them — empty folders add noise.

- `architecture/` — system design, block diagrams, decision records
- `firmware/` — embedded code documentation
- `protocols/` — wire formats and message definitions
- `deployment/` — build and flash instructions, release checklists

## Conventions

- File names: lowercase with hyphens, for example `pid-tuning-notes.md`.
- One topic per file. Split large documents instead of letting them sprawl.
- Link to other documents (in this folder or other team folders) instead of
  duplicating content.
- If you reference code that lives in another repository, include the repo
  name and a permalink to a specific commit when accuracy matters.

## Cross-Team Coordination

When software changes depend on mechanical or electrical decisions (for
example, motor specs or sensor pinouts), reference the relevant document in
the other team's folder rather than copying it here. If the other team's docs
are missing or out of date, ask them to update — do not edit their folder
directly.
