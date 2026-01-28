
# Repository Structure

This document describes the high-level layout of the repository and the purpose of each major directory.

## Top-Level Layout

```text
deterministic-data-reconciliation-system/
├── LICENSE
├── pyproject.toml
├── README.md
├── docs/
│   ├── 01_abstract.md
│   ├── 02_repository_structure.md
│   ├── images/
│   └── reports/
│       ├── 01_final-report.md
│       └── 02_viva-faqs.md
└── src/
  ├── backend/
  └── frontend/
```

## Directory Guide

- **docs/**
 	- Project documentation and reports.
 	- **images/**: Figures and diagrams referenced by documentation.
 	- **reports/**: Formal deliverables and review material.

- **src/**
 	- Application source code.
 	- **backend/**: Server-side services, APIs, data reconciliation logic.
 	- **frontend/**: Client-side UI and web assets.

## Key Files

- **README.md**: Project overview, setup, and usage instructions.
- **pyproject.toml**: Python project configuration, tooling, and dependencies.
- **LICENSE**: Repository license.

## Notes

- Keep documentation updates in **docs/** aligned with code changes in **src/**.
- Place new reports under **docs/reports/** and link them from **README.md** if needed.
