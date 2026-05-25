# Awesome Agent Skills

> Curated skills for AI coding agents: Hermes, Codex, Claude Code, OpenCode, and beyond.

A hand-picked collection of the best community skills for AI coding agents. Each repository listed here has been tested and selected for its practical value in real-world development workflows.

[中文版本](README.zh.md)

---

### [superpowers](https://github.com/obra/superpowers) · 205k ⭐

An agentic skills framework and software development methodology that works across 8 platforms (Claude Code, Codex, Cursor, OpenCode, Gemini, GitHub Copilot, and more). Features a 7-step workflow from brainstorming to finishing a development branch, with subagent-driven development and true red/green TDD.

| Skill | Description |
|-------|-------------|
| `brainstorming` | Socratic design refinement before writing any code |
| `writing-plans` | Turn a one-line objective into a step-by-step construction plan |
| `subagent-driven-development` | Agents work autonomously with inspection/review for hours |
| `test-driven-development` | True red/green TDD targeting "enthusiastic junior engineer" quality |
| `requesting-code-review` | Tiered code review with behavioral tests (plants real bugs, asserts flags) |
| `finishing-a-development-branch` | Clean merge, verify, remove worktree, delete branch |
| `using-git-worktrees` | Detect-and-defer architecture for native harness worktree systems |

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

### [ecc](https://github.com/affaan-m/ecc) · 191k ⭐

The agent harness performance optimization system. Not just skills — a complete operator system covering skills, instincts, memory optimization, continuous learning, security scanning, hooks, agents, rules, MCP configurations, and research-first development. Supports 12+ harnesses including Claude Code, Codex, Cursor, OpenCode, Gemini, Zed, GitHub Copilot, and more.

| Component | Count | Description |
|-----------|-------|-------------|
| Agents | 60 | Specialized subagents for various workflows |
| Skills | 232 | Workflow definitions covering engineering, media, operations |
| Rules | 34 | Always-follow guidelines (common + language-specific: TypeScript, Python, Go, Swift, etc.) |
| Hook Events | 8-15 | Trigger-based automations per harness |
| MCP Servers | 14 | Pre-configured MCP server configurations |
| Commands | 75 | Legacy slash-entry shims for backward compatibility |

**Notable Skills:**

| Skill | Description |
|-------|-------------|
| `ai-first-engineering` | Operating model for teams shipping with AI-assisted code generation |
| `agentic-engineering` | Patterns for building autonomous agent workflows |
| `tdd-workflow` | Test-driven development adapted for agent-generated code |
| `coding-standards` | Cross-project conventions for naming, readability, and structure |
| `architecture-decision-records` | Structured ADR format for agent-assisted architecture decisions |
| `codebase-onboarding` | Analyze unfamiliar codebases and generate structured onboarding guides |
| `brand-voice` | Consistent brand voice across agent-generated content |
| `manim-video` | Mathematical animation generation |
| `remotion-video-creation` | Programmatic video creation |

**Tools:** Includes a Tkinter desktop GUI (`ecc_dashboard.py`), Rust control plane prototype (`ecc2/`), and CLI installer with consult mode.

### [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) · 82.4k ⭐

An AI skill that provides design intelligence for building professional UI/UX across multiple platforms and frameworks. Generates complete, tailored design systems automatically through an AI-powered reasoning engine with 161 rules, 67 visual styles, and 161 color palettes.

| Skill | Description |
|-------|-------------|
| `ui-ux-pro-max` | Multi-domain design system generator — analyzes requirements and outputs complete pattern + style + colors + typography + anti-patterns in seconds |

### [academic-research-skills](https://github.com/imbad0202/academic-research-skills) · 20.7k ⭐

The most comprehensive academic research skill set for Claude Code. A complete research-to-publication pipeline with anti-hallucination safeguards, citation verification, and style calibration.

| Skill Module | Description |
|-------------|-------------|
| `deep-research` | 13-agent research with 7 modes: full, quick, systematic-review, socratic, fact-check, lit-review, review |
| `academic-paper` | 12-agent paper writing with 10 modes including style calibration and citation management |
| `academic-reviewer` | 7-agent peer review simulation with calibration mode |
| `academic-pipeline` | 10-stage orchestrator from research to final publication with integrity gates at stage 2.5 and 4.5 |

**Key Innovation:** L3 Claim-Faithfulness Audit — fetches cited sources and verifies every claim against its anchor, with 5 HIGH-WARN classes that gate-refuse unverified output.

### [nature-skills](https://github.com/Yuan1z0825/nature-skills) · 11.5k ⭐

Nature-standard academic writing and figure generation skills. Each skill is grounded in actual *Nature* publications and official journal guidelines, covering the full research workflow from literature search to publication.

| Skill | Description |
|-------|-------------|
| `nature-figure` | Publication-ready Python/R figure workflow with 10 chart-type families and bundled demos |
| `nature-polishing` | *Nature* style academic prose polishing with 12-step workflow including hedging calibration and overclaim detection |
| `nature-writing` | Manuscript section drafting and argument restructuring |
| `nature-citation` | Strict *Nature*/CNS citation retrieval with ENW/RIS/Zotero RDF export |
| `nature-data` | Data Availability statements, repository plans, and FAIR checks |
| `nature-reader` | Full-paper bilingual Markdown reader with source anchors |
| `nature-response` | Point-by-point reviewer response letters with action mapping |
| `nature-paper2ppt` | Chinese PPTX decks generated from scientific papers |
| `nature-academic-search` | Multi-source literature search, citation verification, and reference management |

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
