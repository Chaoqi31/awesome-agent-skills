# Awesome Agent Skills

> 为 AI 编程助手精选的 Skills 集合：Hermes、Codex、Claude Code、OpenCode 等。

一份精心筛选的 AI 编程助手 Skills 合集。这里列出的每个仓库都经过实际测试，在真实开发工作流中具有实用价值。

想要更多？浏览完整的 Skills 生态系统：[skills.sh](https://www.skills.sh/) —— 覆盖 20+ 平台的开放 Agent Skills 目录，收录 40 万+ Skills。

[English Version](README.md)

---

### [superpowers](https://github.com/obra/superpowers) · 205k ⭐

跨 8 个平台的 Agentic Skills 框架和软件开发方法论（Claude Code、Codex、Cursor、OpenCode、Gemini、GitHub Copilot 等）。包含从头脑风暴到完成开发分支的 7 步工作流，支持子代理驱动开发和真正的红绿 TDD。

| Skill | 描述 |
|-------|------|
| [`brainstorming`](https://github.com/obra/superpowers/tree/main/skills/brainstorming) | 写代码前进行苏格拉底式设计提炼 |
| [`writing-plans`](https://github.com/obra/superpowers/tree/main/skills/writing-plans) | 将一句话目标拆解为逐步执行计划 |
| [`subagent-driven-development`](https://github.com/obra/superpowers/tree/main/skills/subagent-driven-development) | 代理自主工作数小时，带检查/评审 |
| [`test-driven-development`](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) | 真正的红绿 TDD，目标质量为"热情但品味欠佳的初级工程师" |
| [`requesting-code-review`](https://github.com/obra/superpowers/tree/main/skills/requesting-code-review) | 分层代码评审，含行为测试（植入真实 Bug，断言标记） |
| [`finishing-a-development-branch`](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) | 干净合并、验证、移除 worktree、删除分支 |
| [`using-git-worktrees`](https://github.com/obra/superpowers/tree/main/skills/using-git-worktrees) | 检测-委托架构，优先使用原生 harness worktree 系统 |

### [Suede Creator Skills](https://github.com/JasonColapietro/suede-creator-skills)

面向 Claude Code 与 Codex 的 MIT 授权 Skills 合集。以可复用的 `SKILL.md` 目录封装多 Agent 编排、Codex 工作节点集群、代码审查与发布门槛、AI 评测、产品、设计和增长工作流。

| Skill | 描述 |
|-------|------|
| [`suede-agent-teams`](https://github.com/JasonColapietro/suede-creator-skills/tree/main/skills/suede-agent-teams) | 通过明确的职责划分和审查门槛协调多 Agent 工作 |
| [`suede-codex-fleet`](https://github.com/JasonColapietro/suede-creator-skills/tree/main/skills/suede-codex-fleet) | 编写任务简报、启动并审查并行 Codex CLI 工作节点 |
| [`suede-code-review`](https://github.com/JasonColapietro/suede-creator-skills/tree/main/skills/suede-code-review) | 按严重级别输出结构化代码审查结果 |
| [`suede-ai-eval`](https://github.com/JasonColapietro/suede-creator-skills/tree/main/skills/suede-ai-eval) | 为 AI 功能设计和审计评测策略 |

### [OpenSpec](https://github.com/Fission-AI/OpenSpec) · 50.9k ⭐

最受欢迎的 Spec 框架。面向 AI 编程助手的 Spec-Driven Development（SDD）。轻量、迭代、流畅 —— 在写任何代码前先对齐需求。通过斜杠命令和原生 Skill 集成支持 20+ 种 AI 助手。

| 命令 | 描述 |
|---------|------|
| [`/opsx:propose`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxpropose) | 一步创建变更并生成规划产物 |
| [`/opsx:explore`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxexplore) | 在提交变更前探索思路、调研问题 |
| [`/opsx:apply`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxapply) | 执行变更中的任务清单 |
| [`/opsx:sync`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxsync) | 将增量 Spec 合并到主 Spec |
| [`/opsx:archive`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxarchive) | 归档已完成的变更 |
| [`/opsx:verify`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxverify) | 验证实现与产物的一致性 |
| [`/opsx:onboard`](https://github.com/Fission-AI/OpenSpec/blob/main/docs/commands.md#opsxonboard) | 完整工作流的交互式引导教程 |

**Schemas：** [`spec-driven`](https://github.com/Fission-AI/OpenSpec/tree/main/schemas/spec-driven) · [`workspace-planning`](https://github.com/Fission-AI/OpenSpec/tree/main/schemas/workspace-planning)

### [Skills For Real Engineers](https://github.com/mattpocock/skills) · 104k ⭐

Matt Pocock 的日常工程 Skills，用于"真正的工程 —— 不是氛围编程"。小巧、可组合、模型无关。围绕四个失败模式构建：需求错位、输出冗长、代码出错、架构腐化。

| Skill | 描述 |
|-------|------|
| [`diagnose`](https://github.com/mattpocock/skills/tree/main/skills/engineering/diagnose) | 针对疑难 Bug 和性能回归的纪律性诊断循环 |
| [`grill-with-docs`](https://github.com/mattpocock/skills/tree/main/skills/engineering/grill-with-docs) | 开发前深度问答 + 通过 `CONTEXT.md` 对齐领域模型 |
| [`grill-me`](https://github.com/mattpocock/skills/tree/main/skills/productivity/grill-me) | 针对计划或设计进行无情追问，直到每个决策分支都被解决 |
| [`tdd`](https://github.com/mattpocock/skills/tree/main/skills/engineering/tdd) | 红绿重构 TDD，每次一个垂直切片 |
| [`improve-codebase-architecture`](https://github.com/mattpocock/skills/tree/main/skills/engineering/improve-codebase-architecture) | 发现"深化机会"，拯救泥球代码库 |
| [`setup-matt-pocock-skills`](https://github.com/mattpocock/skills/tree/main/skills/engineering/setup-matt-pocock-skills) | 一次性仓库脚手架 —— 配置问题追踪器、分类标签和文档目录 |
| [`to-prd`](https://github.com/mattpocock/skills/tree/main/skills/engineering/to-prd) | 将对话上下文合成为 PRD，作为 GitHub Issue 提交 |
| [`to-issues`](https://github.com/mattpocock/skills/tree/main/skills/engineering/to-issues) | 将计划/规格/PRD 拆分为可独立领取的 GitHub Issues |
| [`triage`](https://github.com/mattpocock/skills/tree/main/skills/engineering/triage) | 状态机驱动的问题分类 |
| [`zoom-out`](https://github.com/mattpocock/skills/tree/main/skills/engineering/zoom-out) | 为陌生代码提供系统级上下文 |

### [ecc](https://github.com/affaan-m/ecc) · 191k ⭐

Agent Harness 性能优化系统。不只是 Skills —— 是一个完整的操作系统，涵盖 Skills、Instincts、内存优化、持续学习、安全扫描、Hooks、Agents、Rules、MCP 配置和研究优先开发。支持 12+ 个 Harness，包括 Claude Code、Codex、Cursor、OpenCode、Gemini、Zed、GitHub Copilot 等。

| 组件 | 数量 | 描述 |
|-----------|-------|-------------|
| [Agents](https://github.com/affaan-m/ecc/tree/main/agents) | 60 | 各类工作流的专用子代理 |
| [Skills](https://github.com/affaan-m/ecc/tree/main/skills) | 232 | 覆盖工程、媒体、运营的流程定义 |
| [Rules](https://github.com/affaan-m/ecc/tree/main/rules) | 34 | 始终遵循的指南（通用 + 语言特定：TypeScript、Python、Go、Swift 等） |
| [Hook Events](https://github.com/affaan-m/ecc/tree/main/hooks) | 8-15 | 每个 Harness 的触发式自动化 |
| MCP Servers | 14 | 预配置的 MCP 服务器配置 |
| [Commands](https://github.com/affaan-m/ecc/tree/main/commands) | 75 | 向后兼容的旧版斜杠命令 |

**代表性 Skills：**

| Skill | 描述 |
|-------|-------------|
| [`ai-first-engineering`](https://github.com/affaan-m/ecc/tree/main/skills/ai-first-engineering) | AI 辅助代码生成团队的运营模式 |
| [`agentic-engineering`](https://github.com/affaan-m/ecc/tree/main/skills/agentic-engineering) | 构建自主 Agent 工作流的模式 |
| [`tdd-workflow`](https://github.com/affaan-m/ecc/tree/main/skills/tdd-workflow) | 适配 Agent 生成代码的测试驱动开发 |
| [`coding-standards`](https://github.com/affaan-m/ecc/tree/main/skills/coding-standards) | 跨项目命名、可读性和结构规范 |
| [`architecture-decision-records`](https://github.com/affaan-m/ecc/tree/main/skills/architecture-decision-records) | 面向 Agent 辅助架构决策的结构化 ADR 格式 |
| [`codebase-onboarding`](https://github.com/affaan-m/ecc/tree/main/skills/codebase-onboarding) | 分析陌生代码库并生成结构化入门指南 |
| [`brand-voice`](https://github.com/affaan-m/ecc/tree/main/skills/brand-voice) | 代理生成内容中的一致品牌声音 |
| [`manim-video`](https://github.com/affaan-m/ecc/tree/main/skills/manim-video) | 数学动画生成 |
| [`remotion-video-creation`](https://github.com/affaan-m/ecc/tree/main/skills/remotion-video-creation) | 程序化视频创建 |

**工具：** 包含 Tkinter 桌面 GUI（`ecc_dashboard.py`）、Rust 控制平面原型（`ecc2/`）和带咨询模式的 CLI 安装器。

### [impeccable](https://github.com/pbakaus/impeccable) · 34.6k ⭐

让你的 AI 编程助手更擅长前端设计的 Skill。基于 Anthropic 原版 frontend-design 打造，包含 7 个设计领域参考文件（排版、色彩、空间、动效、交互、响应式、UX 文案）和 23 个设计命令（`audit`、`polish`、`critique`、`distill`、`animate` 等），以及 27 条确定性反模式规则。

| 命令 | 描述 |
|------|------|
| [`/impeccable craft`](https://impeccable.cn/docs/) | 完整的形状→构建流程，带视觉迭代 |
| [`/impeccable audit`](https://impeccable.cn/docs/) | 技术质量检查（无障碍、性能、响应式） |
| [`/impeccable polish`](https://impeccable.cn/docs/) | 最终清理，设计系统对齐与上线准备 |
| [`/impeccable critique`](https://impeccable.cn/docs/) | UX 设计评审：层级、清晰度、情感共鸣 |
| [`/impeccable distill`](https://impeccable.cn/docs/) | 剥离冗余，回归本质 |
| [`/impeccable animate`](https://impeccable.cn/docs/) | 添加有目的的动效 |

**支持平台：** Claude Code、Codex CLI、Cursor、OpenCode、Gemini CLI、GitHub Copilot、Trae、Rovo Dev、Qoder 等 11+ 个 Harness。

### [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) · 82.4k ⭐

为多个平台和框架构建专业 UI/UX 的 AI 设计智能 Skill。通过 AI 推理引擎自动生成完整的定制设计系统，包含 161 条规则、67 种视觉风格和 161 种配色方案。

| Skill | 描述 |
|-------|------|
| [`ui-ux-pro-max`](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/tree/main/src/ui-ux-pro-max) | 多领域设计系统生成器 —— 分析需求并在数秒内输出完整的模式 + 风格 + 配色 + 字体 + 反模式 |

### [academic-research-skills](https://github.com/imbad0202/academic-research-skills) · 20.7k ⭐

最全面的 Claude Code 学术研究 Skill 集。从研究到发表的完整流水线，带反幻觉保护、引文验证和风格校准。

| Skill 模块 | 描述 |
|-----------|------|
| [`deep-research`](https://github.com/imbad0202/academic-research-skills/tree/main/deep-research) | 13 个 Agent 的研究系统，7 种模式：完整、快速、系统综述、苏格拉底式、事实核查、文献综述、评审 |
| [`academic-paper`](https://github.com/imbad0202/academic-research-skills/tree/main/academic-paper) | 12 个 Agent 的论文写作，10 种模式含风格校准和引文管理 |
| [`academic-reviewer`](https://github.com/imbad0202/academic-research-skills/tree/main/academic-paper-reviewer) | 7 个 Agent 的同行评审模拟，含校准模式 |
| [`academic-pipeline`](https://github.com/imbad0202/academic-research-skills/tree/main/academic-pipeline) | 从研究到最终发表的 10 阶段编排器，在阶段 2.5 和 4.5 设完整性检查点 |

**核心创新：** L3 声明忠实度审计 —— 获取被引来源并验证每条声明与其锚点的一致性，5 类 HIGH-WARN 会阻止未经验证的输出。

### [nature-skills](https://github.com/Yuan1z0825/nature-skills) · 11.5k ⭐

符合 *Nature* 期刊标准的学术写作与科研绘图 Skills。每个 Skill 都基于真实的 *Nature* 出版物和官方期刊指南，覆盖从文献检索到发表的完整研究工作流。

| Skill | 描述 |
|-------|------|
| [`nature-figure`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-figure) | 出版级 Python/R 绘图工作流，支持 10 种图表类型家族，附带示例 |
| [`nature-polishing`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-polishing) | *Nature* 风格学术润色，12 步工作流包含对冲校准和过度声明检测 |
| [`nature-writing`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-writing) | 手稿分段起草和论证重构 |
| [`nature-citation`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-citation) | 严格的 *Nature*/CNS 引文检索，支持 ENW/RIS/Zotero RDF 导出 |
| [`nature-data`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-data) | 数据可用性声明、仓库计划和 FAIR 检查 |
| [`nature-reader`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-reader) | 全文双语 Markdown 阅读器，带源锚点 |
| [`nature-response`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-response) | 逐条审稿意见回复信，带行动映射 |
| [`nature-paper2ppt`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-paper2ppt) | 从科研论文生成中文 PPTX 演示文稿 |
| [`nature-academic-search`](https://github.com/Yuan1z0825/nature-skills/tree/main/skills/nature-academic-search) | 多源文献检索、引文验证和参考文献管理 |

---

## 贡献

发现了好用的 Skill？开 Issue 或 PR 来添加！

1. Skill 必须在 GitHub 上公开可用
2. 包含简要描述说明其功能
3. 注明适用的 Agent（Hermes、Codex、Claude Code 等）

---

## 许可

本合集采用 [CC0 1.0 Universal](LICENSE) 发布 —— 可自由复制、修改和分享。

各 Skill 保留其原始许可（见各自仓库）。
