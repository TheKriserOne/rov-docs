# ROV Project Documentation

Central documentation hub for the ROV team. This repository holds all written
documentation for the project, organized by discipline. Code, CAD source files,
and other team artifacts can live in their own repositories — this one is for
documentation, references, and shared knowledge.

## Repository Structure

| Folder | Owning Team | Abbreviation | Contents |
|--------|-------------|--------------|----------|
| [`software/`](./software) | Software | CS | Control software, firmware, protocols, deployment notes |
| [`mechanical/`](./mechanical) | Mechanical | ME | Frame design, CAD references, assembly, materials |
| [`electrical/`](./electrical) | Electrical | EE | Schematics, wiring, power budget, sensor integration |

Each folder has its own `README.md` with team-specific guidance — read it before
adding documentation to that folder.

## Contribution Rules

This repository is shared across three disciplines. To keep things organized
and prevent stepping on each other's work, the following rules apply:

1. **Stay in your folder.** Only commit changes within your team's folder:
   - **CS** contributors commit only to `software/`
   - **ME** contributors commit only to `mechanical/`
   - **EE** contributors commit only to `electrical/`
2. **Do not edit another team's folder** without explicit coordination and
   approval from someone on that team.
3. **Cross-team changes** (for example, updating a shared interface or
   reference) should be discussed in team channels first, then made by — or
   reviewed by — a member of each affected team.
4. **Commit messages** should mention the discipline so history is easy to
   scan, for example:
   - `software: add control loop notes`
   - `mechanical: update thruster mount drawings`
   - `electrical: revise power budget for v2 board`
5. **Use Markdown** (`.md`) for documentation unless another format is required
   (CAD exports, schematics, datasheets, images, etc.).
6. **Keep it readable.** Prefer short, focused documents over one giant file.
   Link between documents instead of duplicating content.

These rules are an honor-system policy. There is no automated enforcement —
please respect your teammates' work.

## Getting Started

1. Clone the repository.
2. Open the folder for your team.
3. Read that folder's `README.md` for team-specific conventions and suggested
   structure.
4. Add or edit documentation, commit with a clear message, and push.

## Questions

If you are unsure where something belongs or whether a change crosses team
boundaries, ask in the team chat before committing.
