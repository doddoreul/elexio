# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack
Electron + plain browser site; Node.js syntax/test tooling; no cloud backend, no telemetry.

## Users
Inferred: electricians and technical users working on small domestic installations in Belgium; situational, intermittent use to document or verify local installations.

## Product Purpose
Elexio is a local editor of single-line electrical diagrams and installation plans for domestic use (RGIE/AREI). Its goal is to prepare and control schematics, cables, protections and placement plans with Belgian-specific conventions.

## Positioning
100 % local electrical schema editor with Belgian conventions and audit rules, usable in desktop and browser modes.

## Operating Context
Project files are local `.elx`; workflows are offline editing, audit, plan printing, and configuration changes. The application uses a supply-first rooted schema model.

## Capabilities and Constraints
- Single-line domestic electrical diagrams
- Circuit, cable, protection and tableau layout
- RGIE/AREI and NF C 15-100 validation rules
- Installation plan editor and PDF export
- Multilingual interface (FR/NL/EN)
- No cloud, no licence, no telemetry

## Brand Commitments
- Product name: Elexio (ex-ElecSchema)
- Local-first operation is a user-confirmed durable fact.

## Evidence on Hand
- AGENT.md, README.md, README_FR.md, README_NL.md
- Source code in src/
- Tests under test/

## Product Principles
1. Keep all project data local.
2. Preserve Belgian norm-oriented validation as optional guidance, not legal certification.
3. Keep low-friction editing from a root supply.
4. Avoid hidden network calls and telemetry.

## Accessibility & Inclusion
Omit product-specific accessibility requirements beyond general readable labels and keyboard actions.
