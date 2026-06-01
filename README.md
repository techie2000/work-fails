# TF-1 Intraday Trade Fails Workflow and Dashboard

This repository contains documentation artifacts for the TF-1 initiative at
Cantor Fitzgerald, focused on intraday monitoring and operational visibility
of settlement obligation fails.

## Purpose

TF-1 provides advisory visibility and prioritization support for operations users during the settlement day.

TF-1 does not:

- Initiate settlement transactions
- Execute stock borrowing
- Send automated external communications
- Override upstream systems of record

## Primary Source Document

The baseline functional behavior is defined in:

- [docs/vendor/Functional Specification – TF-1. Intraday Trade Fails Workflow and Dashboard v1.0.docx](docs/vendor/Functional%20Specification%20%E2%80%93%20TF-1.%20Intraday%20Trade%20Fails%20Workflow%20and%20Dashboard%20v1.0.docx)

Use this document as the authoritative reference for scope, behavior, and testing expectations.

## Documentation Layout

| Path | Purpose |
| --- | --- |
| [docs/](docs/) | Documentation index and high-level structure |
| [docs/vendor/](docs/vendor/) | Vendor-provided source artifacts and functional specifications |
| [docs/internal/](docs/internal/) | Team-authored notes, implementation interpretations, and working documents |
| [images/](images/) | Supporting screenshots and diagrams |

## Functional Areas Covered

- Intraday monitoring population and fail identification
- Active or Closed fail record lifecycle behavior
- Derived settlement condition and carry-fail handling
- Data availability rules for settlement, RAD, position, and pricing
- Exposure calculation and ordering logic for dashboard views
- User handling status and notes behavior at obligation level
- Dashboard view behavior for Box Exposure and RAD Exceptions
- Auditability, traceability, assumptions, and dependencies

## Working Model

- Keep vendor documents as source artifacts in [docs/vendor/](docs/vendor/)
- Capture internal interpretation and delivery notes in [docs/internal/](docs/internal/)
- Keep this repository documentation-first and aligned to the latest approved spec version

## Local Documentation Checks

Use the repository tooling to keep markdown and settings aligned:

1. make install-hooks
2. make settings-sort
3. make lint-docs
