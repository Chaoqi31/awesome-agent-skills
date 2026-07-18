# Awesome Agent Skills

> Curated skills for AI coding agents: Hermes, Codex, Claude Code, OpenCode, and beyond.

A hand-picked collection of the best community skills for AI coding agents. Each repository listed here has been tested and selected for its practical value in real-world development workflows.

Looking for more? Browse the full ecosystem at [skills.sh](https://www.skills.sh/) - the open agent skills directory with 400K+ skills across 20+ platforms.

[中文版本](README.zh.md)

---

### [superpowers](https://github.com/obra/superpowers) · 205k ⭐

An agentic skills framework and software development methodology that works across 8 platforms (Claude Code, Codex, Cursor, OpenCode, Gemini, GitHub Copilot, and more). Features a 7-step workflow from brainstorming to finishing a development branch, with subagent-driven development and true red/green TDD.

| Skill | Description |
|-------|-------------|
| [`brainstorming`](https://github.com/obra/superpowers/tree/main/skills/brainstorming) | Socratic design refinement before writing any code |
| [`writing-plans`](https://github.com/obra/superpowers/tree/main/skills/writing-plans) | Turn a one-line objective into a step-by-step construction plan |
| [`subagent-driven-development`](https://github.com/obra/superpowers/tree/main/skills/subagent-driven-development) | Agents work autonomously with inspection/review for hours |
| [`test-driven-development`](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) | True red/green TDD targeting "enthusiastic junior engineer" quality |
| [`requesting-code-review`](https://github.com/obra/superpowers/tree/main/skills/requesting-code-review) | Tiered code review with behavioral tests (plants real bugs, asserts flags) |
| [`finishing-a-development-branch`](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) | Clean merge, verify, remove worktree, delete branch |
| [`using-git-worktrees`](https://github.com/obra/superpowers/tree/main/skills/using-git-worktrees) | Detect-and-defer architecture for native harness worktree systems |

### [OpenSpec](https://github.com/Fission-AI/OpenSpec) · 50.9k ⭐

The most loved spec framework. Spec-driven development (SDD) for AI coding assistants. Lightweight, iterative, and fluid - agree on what to build before any code is written. Works with 20+ AI assistants via slash commands and native skill integrations.

| Command | Description |
|---------|-------------|
| [`/opsx:propose`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxpropose) | Create a change and generate planning artifacts in one step |
| [`/opsx:explore`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxexplore) | Think through ideas before committing to a change |
| [`/opsx:apply`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxapply) | Implement tasks from the change |
| [`/opsx:sync`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxsync) | Merge delta specs into main specs |
| [`/opsx:archive`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxarchive) | Archive a completed change |
| [`/opsx:verify`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxverify) | Validate implementation matches artifacts |
| [`/opsx:onboard`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxonboard) | Guided tutorial through the complete workflow |

**Schema:** [`spec-driven`](https://github.com/Fission-AI/OpenSpec/tree/main/schemas/spec-driven)

### [Skills For Real Engineers](https://github.com/mattpocock/skills) · 104k ⭐

Matt Pocock's daily-use agent skills for "real engineering - not vibe coding." Small, composable, and model-agnostic. Built around four failure modes: misalignment, verbosity, broken code, and architectural decay.

| Skill | Description |
|-------|-------------|
| [`diagnosing-bugs`](https://github.com/mattpocock/skills/tree/main/skills/engineering/diagnosing-bugs) | Disciplined diagnosis loop for hard bugs and performance regressions |
| [`grill-with-docs`](https://github.com/mattpocock/skills/tree/main/skills/engineering/grill-with-docs) | Pre-build grilling sessions plus domain model alignment via `CONTEXT.md` |
| [`grill-me`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me) | Get relentlessly interviewed about a plan or design until every branch is resolved |
| [`tdd`](https://github.com/mattpocock/skills/tree/main/skills/engineering/tdd) | Red-green-refactor TDD, one vertical slice at a time |
| [`improve-codebase-architecture`](https://github.com/mattpocock/skills/tree/main/skills/engineering/improve-codebase-architecture) | Find "deepening opportunities" to rescue muddy codebases |
| [`setup-matt-pocock-skills`](https://github.com/mattpocock/skills/tree/main/skills/engineering/setup-matt-pocock-skills) | One-time repo scaffold - configures issue tracker, triage labels, and docs directory |
| [`to-spec`](https://github.com/mattpocock/skills/tree/main/skills/engineering/to-spec) | Synthesize conversation context into a specification and publish it to the issue tracker |
| [`to-tickets`](https://github.com/mattpocock/skills/tree/main/skills/engineering/to-tickets) | Break plans and specifications into dependency-aware vertical tickets |
| [`triage`](https://github.com/mattpocock/skills/tree/main/skills/engineering/triage) | State-machine-driven issue triage |
| [`wayfinder`](https://github.com/mattpocock/skills/tree/main/skills/engineering/wayfinder) | Map large efforts into decision tickets before implementation |

### [ecc](https://github.com/affaan-m/ecc) · 191k ⭐

The agent harness performance optimization system. Not just skills - a complete operator system covering skills, instincts, memory optimization, continuous learning, security scanning, hooks, agents, rules, MCP configurations, and research-first development. Supports 12+ harnesses including Claude Code, Codex, Cursor, OpenCode, Gemini, Zed, GitHub Copilot, and more.

| Component | Count | Description |
|-----------|-------|-------------|
| [Agents](https://github.com/affaan-m/ecc/tree/main/agents) | 60 | Specialized subagents for various workflows |
| [Skills](https://github.com/affaan-m/ecc/tree/main/skills) | 232 | Workflow definitions covering engineering, media, operations |
| [Rules](https://github.com/affaan-m/ecc/tree/main/rules) | 34 | Always-follow guidelines (common + language-specific: TypeScript, Python, Go, Swift, etc.) |
| [Hook Events](https://github.com/affaan-m/ecc/tree/main/hooks) | 8-15 | Trigger-based automations per harness |
| MCP Servers | 14 | Pre-configured MCP server configurations |
| [Commands](https://github.com/affaan-m/ecc/tree/main/commands) | 75 | Legacy slash-entry shims for backward compatibility |

**Notable Skills:**

| Skill | Description |
|-------|-------------|
| [`ai-first-engineering`](https://github.com/affaan-m/ecc/tree/main/skills/ai-first-engineering) | Operating model for teams shipping with AI-assisted code generation |
| [`agentic-engineering`](https://github.com/affaan-m/ecc/tree/main/skills/agentic-engineering) | Patterns for building autonomous agent workflows |
| [`tdd-workflow`](https://github.com/affaan-m/ecc/tree/main/skills/tdd-workflow) | Test-driven development adapted for agent-generated code |
| [`coding-standards`](https://github.com/affaan-m/ecc/tree/main/skills/coding-standards) | Cross-project conventions for naming, readability, and structure |
| [`architecture-decision-records`](https://github.com/affaan-m/ecc/tree/main/skills/architecture-decision-records) | Structured ADR format for agent-assisted architecture decisions |
| [`codebase-onboarding`](https://github.com/affaan-m/ecc/tree/main/skills/codebase-onboarding) | Analyze unfamiliar codebases and generate structured onboarding guides |
| [`brand-voice`](https://github.com/affaan-m/ecc/tree/main/skills/brand-voice) | Consistent brand voice across agent-generated content |
| [`manim-video`](https://github.com/affaan-m/ecc/tree/main/skills/manim-video) | Mathematical animation generation |
| [`remotion-video-creation`](https://github.com/affaan-m/ecc/tree/main/skills/remotion-video-creation) | Programmatic video creation |

**Tools:** Includes a Tkinter desktop GUI (`ecc_dashboard.py`), Rust control plane prototype (`ecc2/`), and CLI installer with consult mode.

### [impeccable](https://github.com/pbakaus/impeccable) · 34.6k ⭐

The design language that makes your AI harness better at frontend design. Built on Anthropic's original `frontend-design` skill with 7 domain references (typography, color, spatial, motion, interaction, responsive, UX writing), 23 commands (`audit`, `polish`, `critique`, `distill`, `animate`, etc.), and 27 deterministic anti-pattern rules.

| Command | Description |
|---------|-------------|
| [`/impeccable craft`](https://impeccable.cn/docs/) | Full shape-then-build flow with visual iteration |
| [`/impeccable audit`](https://impeccable.cn/docs/) | Technical quality checks (a11y, performance, responsive) |
| [`/impeccable polish`](https://impeccable.cn/docs/) | Final pass, design system alignment, shipping readiness |
| [`/impeccable critique`](https://impeccable.cn/docs/) | UX design review: hierarchy, clarity, emotional resonance |
| [`/impeccable distill`](https://impeccable.cn/docs/) | Strip to essence |
| [`/impeccable animate`](https://impeccable.cn/docs/) | Add purposeful motion |

**Supported platforms:** Claude Code, Codex CLI, Cursor, OpenCode, Gemini CLI, GitHub Copilot, Trae, Rovo Dev, Qoder, and 11+ harnesses.

### [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) · 82.4k ⭐

An AI skill that provides design intelligence for building professional UI/UX across multiple platforms and frameworks. Generates complete, tailored design systems automatically through an AI-powered reasoning engine with 161 rules, 67 visual styles, and 161 color palettes.

| Skill | Description |
|-------|-------------|
| [`ui-ux-pro-max`](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/tree/main/src/ui-ux-pro-max) | Multi-domain design system generator - analyzes requirements and outputs complete pattern + style + colors + typography + anti-patterns in seconds |

### [academic-research-skills](https://github.com/imbad0202/academic-research-skills) · 20.7k ⭐

The most comprehensive academic research skill set for Claude Code. A complete research-to-publication pipeline with anti-hallucination safeguards, citation verification, and style calibration.

| Skill Module | Description |
|-------------|-------------|
| [`deep-research`](https://github.com/imbad0202/academic-research-skills/tree/main/deep-research) | 13-agent research with 7 modes: full, quick, systematic-review, socratic, fact-check, lit-review, review |
| [`academic-paper`](https://github.com/imbad0202/academic-research-skills/tree/main/academic-paper) | 12-agent paper writing with 10 modes including style calibration and citation management |
| [`academic-reviewer`](https://github.com/imbad0202/academic-research-skills/tree/main/academic-paper-reviewer) | 7-agent peer review simulation with calibration mode |
| [`academic-pipeline`](https://github.com/imbad0202/academic-research-skills/tree/main/academic-pipeline) | 10-stage orchestrator from research to final publication with integrity gates at stage 2.5 and 4.5 |

**Key Innovation:** L3 Claim-Faithfulness Audit - fetches cited sources and verifies every claim against its anchor, with 5 HIGH-WARN classes that gate-refuse unverified output.

### [nature-skills](https://github.com/Yuan1z0825/nature-skills) · 11.5k ⭐

Nature-standard academic writing and figure generation skills. Each skill is grounded in actual *Nature* publications and official journal guidelines, covering the full research workflow from literature search to publication.

| Skill | Description |
|-------|-------------|
| [`nature-figure`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-figure) | Publication-ready Python/R figure workflow with 10 chart-type families and bundled demos |
| [`nature-polishing`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-polishing) | *Nature* style academic prose polishing with 12-step workflow including hedging calibration and overclaim detection |
| [`nature-writing`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-writing) | Manuscript section drafting and argument restructuring |
| [`nature-citation`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-citation) | Strict *Nature*/CNS citation retrieval with ENW/RIS/Zotero RDF export |
| [`nature-data`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-data) | Data Availability statements, repository plans, and FAIR checks |
| [`nature-reader`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-reader) | Full-paper bilingual Markdown reader with source anchors |
| [`nature-response`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-response) | Point-by-point reviewer response letters with action mapping |
| [`nature-paper2ppt`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-paper2ppt) | Chinese PPTX decks generated from scientific papers |
| [`nature-academic-search`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-academic-search) | Multi-source literature search, citation verification, and reference management |

### [x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) · 155 ⭐

Installable X/Twitter data skill for agents. It covers public X data lookup, extraction jobs, monitors, MCP, REST API access, and approval-gated write workflows through Xquik.

Xquik is an independent third-party service. Not affiliated with X Corp. "Twitter" and "X" are trademarks of X Corp.

| Skill | Description |
|-------|-------------|
| [`x-twitter-scraper`](https://github.com/Xquik-dev/x-twitter-scraper/tree/master/skills/x-twitter-scraper) | Search tweets, inspect profiles, export followers, download media, monitor accounts or keywords, and use Xquik through MCP or REST API access |

---

## Contributing

Found a great skill? Open an issue or PR to add it!

1. The skill must be publicly available on GitHub
2. Include a brief description of what it does
3. Note which agents it works with (Hermes, Codex, Claude Code, etc.)

---

## License

This curation is released under [CC0 1.0 Universal](LICENSE) - feel free to copy, modify, and share.

Individual skills retain their original licenses (see respective repositories).
