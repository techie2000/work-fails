# Internal Documentation

This folder is reserved for team-authored TF-1 implementation and delivery documentation.

## Current Contents

| File | Description |
| --- | --- |
| [.gitkeep](.gitkeep) | Placeholder file so the folder remains tracked while no internal docs are present. |

## Suggested Content

- Meeting notes and action logs.
- Environment-specific runbooks and troubleshooting notes.
- Internal decisions that should not be mixed with vendor documents.

## Implementation Workflow

Use this sequence to keep implementation aligned with the vendor functional specification.

1. Review the current baseline in [docs/vendor/README.md](../vendor/README.md) and the linked TF-1 functional specification.
2. Capture implementation interpretation notes by functional area (for example,
   View 1 logic, View 2 logic, data freshness, handling status behavior).
3. Record open questions and assumptions as explicit dated entries.
4. Add testing notes that map expected behavior to specification sections.
5. Track change impact when vendor versions are updated, including what changed and what action is needed.

## Naming and Structure Guidance

- Prefer dated filenames for working notes, for example: `2026-06-01-view1-behavior-notes.md`.
- Keep one topic per document where possible.
- Include references to source spec sections so decisions are traceable.
