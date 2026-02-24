# AMRIT Newcomer Guide

This repository is the **coordination hub** for the AMRIT ecosystem, not the place where core product code lives.

## What this repo contains

- `README.md`: project mission, links to all UI/API/service repositories, and community entry points.
- `CONTRIBUTOR_GUIDELINES.md`: contribution process and issue/PR expectations.
- `CODE_OF_CONDUCT.md`: behavior and enforcement standards.
- `LICENSE`: legal terms.

## How AMRIT is structured

AMRIT is a **multi-repository platform**:

- UI modules are separate Angular repositories (for example, `TM-UI`, `HWC-UI`, `Inventory-UI`).
- API modules are separate Spring Boot repositories (for example, `TM-API`, `HWC-API`, `Inventory-API`).
- Supporting repositories exist for data migration, core common services, and DevOps.

In practice, this means you start from this repository to understand the landscape, then jump into a specific UI/API repo depending on your task.

## First things to do as a new contributor

1. Read the README end-to-end and pick one service line (for example, TM, HWC, or Inventory).
2. Follow the linked developer setup docs to run the chosen UI/API locally.
3. Check open issues in this main repository and align on assignment before coding.
4. Join the Discord community if you need clarification quickly.

## Suggested learning path

1. Learn one end-to-end flow (one UI repo + one API repo).
2. Understand shared libraries/components (for example, Common-UI and Common-API).
3. Review AMRIT-DevOps repo basics to understand deployment/runtime assumptions.
4. Explore product-level docs (JIRA + Confluence) to map business workflow to technical modules.
