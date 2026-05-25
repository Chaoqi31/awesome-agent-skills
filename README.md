# Awesome Agent Skills

> Curated skills for AI coding agents: Hermes, Codex, Claude Code, OpenCode, and beyond.

A hand-picked collection of the best community skills for AI coding agents. Each repository listed here has been tested and selected for its practical value in real-world development workflows.

[中文版本](README.zh.md)

---

## Table of Contents

- [General-Purpose](#general-purpose)
- [Frontend & UI/UX](#frontend--uiux)
- [Academic & Research](#academic--research)
- [Engineering Methodology](#engineering-methodology)

---

## General-Purpose

### [superpowers](https://github.com/obra/superpowers) · 2.1k ⭐

General-purpose superpowers for daily development workflows. Covers planning, experimentation, and architecture scaffolding.

| Skill | Description |
|-------|-------------|
| `writing-plans` | Turn a one-line objective into a step-by-step construction plan |
| `spike` | Throwaway experiments to validate an idea before building |
| `blueprint` | Architecture decision records and system design scaffolding |

### [nature-skills](https://github.com/Yuan1z0825/nature-skills) · 11.5k ⭐

Nature-standard academic writing and figure generation skills. Each skill is grounded in actual *Nature* publications and official journal guidelines, covering the full research workflow from literature search to publication.

| Skill | Description |
|-------|-------------|
| `nature-figure` | Publication-ready Python/R figure workflow with 10 chart-type families and bundled demos |
| `nature-polishing` | Academic prose polishing to *Nature* style with 12-step workflow including hedging calibration and overclaim detection |
| `nature-writing` | Manuscript section drafting and argument restructuring |
| `nature-citation` | Strict *Nature*/CNS citation retrieval with ENW/RIS/Zotero RDF export |
| `nature-data` | Data Availability statements, repository plans, and FAIR checks |
| `nature-reader` | Full-paper bilingual Markdown reader with source anchors |
| `nature-response` | Point-by-point reviewer response letters with action mapping |
| `nature-paper2ppt` | Chinese PPTX decks generated from scientific papers |
| `nature-academic-search` | Multi-source literature search, citation verification, and reference management |

### [skills](https://github.com/mattpocock/skills) · 104k ⭐

Matt Pocock's daily-use agent skills for "real engineering — not vibe coding." Small, composable, and model-agnostic. Built around four failure modes: misalignment, verbosity, broken code, and architectural decay.

| Skill | Description |
|-------|-------------|
| `diagnose` | Disciplined diagnosis loop for hard bugs and performance regressions |
| `grill-with-docs` | Pre-build grilling sessions plus domain model alignment via `CONTEXT.md` |
| `tdd` | Red-green-refactor TDD, one vertical slice at a time |
| `improve-codebase-architecture` | Find "deepening opportunities" to rescue muddy codebases |
| `setup-matt-pocock-skills` | One-time repo scaffold — configures issue tracker, triage labels, and docs directory |
| `to-prd` | Synthesize conversation context into PRD, submit as GitHub issue |
| `to-issues` | Break plans/specs/PRDs into independently-grabbable GitHub issues |
| `triage` | State-machine-driven issue triage |
| `zoom-out` | System-level context for unfamiliar code |

---

## Frontend & UI/UX

### [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) · 1.8k ⭐

Professional UI/UX design skills for agent-assisted interface development. Comprehensive design system and component generation workflow.

| Skill | Description |
|-------|-------------|
| `ui-ux-pro-max` | End-to-end UI/UX design system with component generation and design token management |

---

## Academic & Research

### [academic-research-skills](https://github.com/imbad0202/academic-research-skills) · 20.7k ⭐

The most comprehensive academic research skill set for Claude Code. A complete research-to-publication pipeline with anti-hallucination safeguards, citation verification, and style calibration.

| Skill Module | Description |
|-------------|-------------|
| `deep-research` | 13-agent research with 7 modes: full, quick, systematic-review, socratic, fact-check, lit-review, review |
| `academic-paper` | 12-agent paper writing with 10 modes including style calibration and citation management |
| `academic-reviewer` | 7-agent peer review simulation with calibration mode |
| `academic-pipeline` | 10-stage orchestrator from research to final publication |

**Key Innovation:** L3 Claim-Faithfulness Audit — fetches cited sources and verifies every claim against its anchor, with 5 HIGH-WARN classes that gate-refuse unverified output.

---

## Engineering Methodology

### [ecc](https://github.com/affaan-m/ecc) · 3.4k ⭐

Engineering Competence Center — methodology and process skills for AI-assisted engineering teams. Covers operating models, autonomous loops, and quality assurance.

| Skill | Description |
|-------|-------------|
| `ai-first-engineering` | Operating model for teams shipping with AI-assisted code generation |
| `agentic-engineering` | Patterns for building autonomous agent workflows |
| `tdd-workflow` | Test-driven development adapted for agent-generated code |
| `coding-standards` | Cross-project conventions for naming, readability, and structure |
| `architecture-decision-records` | Structured ADR format for agent-assisted architecture decisions |
| `codebase-onboarding` | Analyze unfamiliar codebases and generate structured onboarding guides |

---

## Contributing

Found a great skill? Open an issue or PR to add it!

1. The skill must be publicly available on GitHub
2. Include a brief description of what it does
3. Note which agents it works with (Hermes, Codex, Claude Code, etc.)

---

## License

This curation is released under [CC0 1.0 Universal](LICENSE) — feel free to copy, modify, and share.

Individual skills retain their original licenses (see respective repositories).
