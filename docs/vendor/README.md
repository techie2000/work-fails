# Vendor Documentation

This folder contains source vendor artifacts used by the TF-1 project.

## Current Artifacts

| File | Version | Date | Description |
| --- | --- | --- | --- |
| [Functional Specification – TF-1. Intraday Trade Fails Workflow and Dashboard v1.0.docx](Functional%20Specification%20%E2%80%93%20TF-1.%20Intraday%20Trade%20Fails%20Workflow%20and%20Dashboard%20v1.0.docx) | 1.0 (Draft for Review) | 03/09/2026 | Functional baseline for TF-1 intraday fail monitoring workflow and dashboard behavior. |

## Functional Scope Summary (From Vendor Spec)

- Defines TF-1 as an advisory intraday monitoring and visibility solution.
- Covers workflow states, settlement condition logic, and dashboard view behavior.
- Documents data domains: settlement, RAD approvals, position (DTC box), and pricing.
- Defines user-editable fields (handling status and notes) and system-driven closure rules.
- Captures auditability, assumptions, dependencies, and out-of-scope boundaries.

## Usage Guidelines

- Keep vendor source files unmodified in this folder.
- Add team-authored interpretations and implementation notes under [docs/internal/](../internal/).
- Use versioned filenames for new vendor drops and update this index table.
