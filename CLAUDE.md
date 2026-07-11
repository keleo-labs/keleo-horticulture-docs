# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Horticulture Foundations is a knowledge framework for professional horticulture, published as a static documentation site using MkDocs Material. All content is Markdown under `docs/`. There is no application code, tests, or build pipeline beyond MkDocs.

## Commands

```bash
mkdocs serve          # Local dev server with live reload (http://127.0.0.1:8000)
mkdocs build          # Build static site to site/
```

## Content Architecture

The framework uses six interconnected content types. Understanding their relationships is essential — most edits require updating cross-references across multiple files.

### Content Types and Their Relationships

- **Concerns** (`docs/concerns/`) — Aspects of horticultural practice that must be managed (e.g. IPM, Biosecurity). Each concern defines a progression of **states** (numbered headings like `### 1. Monitored`). States have checklists, "Progressed by" links to activities, and "Evidenced by" links to work products.
- **Activities** (`docs/activities/`) — Things practitioners do (e.g. Perform Pest and Disease Scouting). Each activity links back to the concern states it progresses ("Contributes To"), the work products it creates/updates ("Works On"), the personas involved ("Involves"), and the competencies required.
- **Work Products** (`docs/work-products/`) — Documents/records produced by activities (e.g. IPM Plan). Each has **levels of detail** (numbered headings like `### 1. Pest and Disease Register`) with checklists. Levels link back to the concern states they evidence ("Contributes to") and the activities that develop them ("Developed by").
- **Patterns** (`docs/patterns/`) — Multi-concern lifecycle progressions shown as matrices. Each pattern maps named phases (rows) against multiple concerns (columns), with cells linking to specific concern states.
- **Personas** (`docs/personas/`) — Teams and individual roles grouped by functional area (Plant Production, Technical Operations, Sustainability & Compliance, Business Management).
- **Competencies** (`docs/competencies/`) — Skills with 5-level proficiency scales (Basic, Applies, Masters, Adapts, Innovating).

### Cross-Reference Web

The content types form a densely linked web. When modifying any content:

1. Activities link to concerns (states), work products (levels of detail), personas, and competencies
2. Concern states link back to activities ("Progressed by") and work products ("Evidenced by")
3. Work product levels link back to concern states ("Contributes to") and activities ("Developed by")
4. Patterns reference concern states across multiple concerns in a matrix table

Adding, renaming, or removing a concern state, activity, or work product level requires tracing all inbound and outbound links. These are relative Markdown links with anchor fragments (e.g. `../concerns/biological-systems/plant-protection.md#1-monitored`).

### Three Practice Domains

Content is organised into three parallel domains at the second directory level:

- `biological-systems/` — Plant health, growing environments, pest management, biosecurity, sustainability
- `production-operations/` — Production system design, technical infrastructure, resource management, digital integration
- `professional-practice/` — Business operations, regulatory compliance, workforce development, health & safety

### Document Conventions

- All content files begin with `hide: - toc` frontmatter and include `[TOC]` for in-page navigation
- Narrative sections use a STAR (Situation, Task, Action, Result) format as a numbered list (1-4)
- References use anchor-linked citations pointing to `docs/references.md` (e.g. `[Author (Year)](../../../references.md#anchor-id)`)
- Concern titles may use Font Awesome icons in the `# heading` (e.g. `# <i class="fa-solid fa-shield-halved"></i> IPM`)
- Overview pages (`overview.md`, `index.md`) contain inline SVG diagrams — these are hand-authored, not generated

## Navigation

All site navigation is defined in `mkdocs.yml` under the `nav:` key. Adding a new page requires an entry there.
