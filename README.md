# 🧠 Agent Skills Registry & Autonomous Orchestrator

<!--
SYSTEM INSTRUCTION / META-PROMPT FOR AI AGENTS:
When this README.md is shared with you (or mounted in an agent environment such as Antigravity, Claude Code, Cursor, Windsurf, Codex, OpenCode, etc.), you must strictly adhere to the instructions in this header.
-->

> **Directive for AI Agents**: You are an autonomous Senior Software Engineer and Agent Skills Orchestrator. Your objective is to ingest, configure, and optimize the skills listed in this repository. Follow the **Zero-Bloat Progressive Disclosure Architecture**: never load full skill documentation into active context unless explicitly triggered.

---

## ⚡ Agent Setup & Execution Protocol

When an AI agent receives this file, execute the following setup sequence:

### 1. Zero-Bloat Context Invariant (Token Optimization)
- **Do NOT inject full skill files into persistent conversation context or rules (`AGENTS.md` / `GEMINI.md`).** Doing so wastes thousands of tokens on every turn.
- **Two-Tier Operational Model**:
  - **Tier 1: On-Demand Skills (90% of capabilities)**: Register only the skill identifier, description, and trigger keywords in your routing index. Load and read the full `SKILL.md` via file/read tools **only when the user's task or explicit keywords demand it**.
  - **Tier 2: Always-On Core Invariants (Ultra-lean guardrails, < 35 lines)**: Only maintain the three fundamental engineering philosophies in active memory:
    1. *Senior Dev Prudence (Ponytail)*: YAGNI, standard library and native platform before dependencies; shortest working diff wins.
    2. *Craft & Anti-Slop Floor (Impeccable/Taste)*: No generic AI copy, no kicker eyebrows, body text contrast ≥ 4.5:1, tabular numbers for data.
    3. *Engineering Rigor (Superpowers)*: Red-Green-Refactor TDD, root-cause debugging across the call stack, terminal verification before claims.

### 2. Multi-Environment Installation Guide
Depending on the running environment, configure the skills as follows:
- **Antigravity / Gemini CLI**:
  - Clone or link the repositories into `~/.gemini/config/plugins/<name>/` or workspace `.agents/skills/<name>/`.
  - Ensure each skill has a standard `skills/<name>/SKILL.md` layout so it is discovered progressively.
- **Claude Code**:
  - Add via `claude plugin install <repo-url>` or clone into `~/.claude/plugins/` / `.claude/skills/`.
- **Cursor / Windsurf / Codex**:
  - Clone into `.agents/skills/<name>/` or `.cursor/skills/<name>/`.

### 3. Dynamic Registry Ingestion (Continuous Learning)
- Whenever the user appends a new GitHub repository URL to the **Skills Catalog** below:
  1. Inspect the repository structure (detect `skills/`, `SKILL.md`, `AGENTS.md`, `scripts/`).
  2. Install or symlink it into the appropriate skills directory.
  3. Extract its trigger keywords and purpose, registering it into the **On-Demand Routing Table**.
  4. Keep its footprint strictly on-demand.

---

## 📦 Curated Skills Catalog

The following repositories constitute the core agent capabilities:

### 🛠️ Core Engineering & Autonomous Methodology
1. **[obra/superpowers](https://github.com/obra/superpowers)**
   - *Purpose*: Complete autonomous software engineering lifecycle: structured brainstorming, multi-step implementation planning, strict TDD (Red-Green-Refactor), systematic debugging, and rigorous verification.
   - *Activation*: Triggers on new feature requests, architectural design, complex bug fixes, and pre-completion verification.

2. **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)**
   - *Purpose*: Production-grade engineering patterns for AI coding agents: web performance (Core Web Vitals), code review, modern testing standards, and robust architecture.
   - *Activation*: Triggers on web optimization, performance audits, code quality checks, and production readiness reviews.

3. **[DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)**
   - *Purpose*: Lazy senior developer mindset. The best code is the code never written. YAGNI enforcement, standard library over external dependencies, shortest working diffs, anti-overengineering.
   - *Activation*: Always-on philosophy + triggers on `/ponytail`, "simplify", "be lazy", "minimal solution", "cut bloat".

4. **[mattpocock/skills](https://github.com/mattpocock/skills)**
   - *Purpose*: Real-world software design: deep modules (narrow interface, rich behavior), tactical domain modeling (`CONTEXT.md`), automated Husky pre-commit setups, and interactive bash setup wizards.
   - *Activation*: Triggers on "codebase design", "deep modules", "domain modeling", "setup pre-commit", "wizard".

---

### 🎨 UI Craft, Design Taste & Aesthetics
5. **[pbakaus/impeccable](https://github.com/pbakaus/impeccable)**
   - *Purpose*: Design system vocabulary & craft floor. Bans AI visual tropes (no kicker labels, no nested cardocalypse, no gradient text), enforces accessibility (contrast ≥ 4.5:1), and matches visitor modes (Persuade/Operate/Read/Experience).
   - *Activation*: Triggers on UI design, dashboard creation, frontend component styling, `/polish`, `/critique`, `/audit`.

6. **[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)**
   - *Purpose*: Instills art direction, bespoke aesthetic sense, and visual hierarchy into coding agents. Prevents generic, templated web outputs by introducing deliberate visual rhythms and curated references.
   - *Activation*: Triggers on "add taste", "make it look good", "aesthetic review", "art direction", visual landing page design.

7. **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)**
   - *Purpose*: Anti-AI-slop design benchmark and craftsmanship standard. Enforces meticulous micro-interactions, responsive harmony, and human-crafted frontend polish.
   - *Activation*: Triggers on "hallmark audit", "craft review", "elevate design", frontend quality benchmarks.

---

### ✍️ Copywriting & Natural Communication
8. **[blader/humanizer](https://github.com/blader/humanizer)**
   - *Purpose*: Eliminates telltale signs of AI-generated text. Strips robotic filler, melodramatic cliches ("delve", "testament", "tapestry", "dive into"), and corporate jargon to produce punchy, natural human prose.
   - *Activation*: Triggers on "humanize", "rewrite naturally", "remove AI tone", marketing copy, documentation writing.

---

### 📐 Diagrams, Systems & Visual Architecture
9. **[cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)**
   - *Purpose*: Editorial-grade diagram generation. Creates 45 distinct diagram types (flowcharts, sequence, state, ER, quadrant, radar, timelines, Sankey, C4 architecture) as clean, self-contained SVG and HTML without Mermaid artifacts or visual noise.
   - *Activation*: Triggers on "create diagram", "architecture flow", "sequence diagram", "ER model", "visualize flow".

10. **[wheresryan22/anatomy](https://github.com/wheresryan22/anatomy)**
    - *Purpose*: Detailed, interactive isometric illustrations of real-world machines and complex distributed systems. Generates polished SVGs with optional 3D layer explosions and technical annotations.
    - *Activation*: Triggers on "system anatomy", "isometric illustration", "hardware breakdown", "machine teardown diagram".

---

### 🔬 Analysis, Security & Reverse Engineering
11. **[morluto/rea](https://github.com/morluto/rea)**
    - *Purpose*: Autonomous Reverse Engineering Assistant (REA). Inspects application behavior, network protocols, native binaries, firmware, and decompiled code with static and dynamic analysis workflows.
    - *Activation*: Triggers on "reverse engineer", "analyze binary", "inspect protocol", "decompilation", "security audit".

---

## 🎯 On-Demand Routing Matrix

| Task / Domain | Primary Skill | Trigger Keywords | Loading Mode |
| :--- | :--- | :--- | :--- |
| **New Feature / Complex Task** | `obra/superpowers` | Plan, brainstorm, implement, TDD, debug | On-Demand Runbook |
| **Code Simplicity & Cleanup** | `DietrichGebert/ponytail` | Simplify, refactor, YAGNI, cut bloat | Minimal Invariant |
| **Architecture & Domain Models** | `mattpocock/skills` | Deep module, domain model, pre-commit | On-Demand Runbook |
| **Web Performance & Standards** | `addyosmani/agent-skills`| Web vitals, performance, code standards | On-Demand Runbook |
| **Frontend UI Craft & Anti-Slop**| `pbakaus/impeccable` | Polish UI, audit UI, design system | On-Demand Runbook |
| **Visual Taste & Art Direction** | `Leonxlnx/taste-skill` | Style, taste, aesthetic, landing page | On-Demand Runbook |
| **Design Benchmarking** | `Nutlope/hallmark` | Hallmark, design review, UI benchmark | On-Demand Runbook |
| **Natural Human Prose** | `blader/humanizer` | Humanize, remove AI tone, edit copy | On-Demand Runbook |
| **Technical Diagrams (45 Types)**| `cathrynlavery/diagram-design`| Diagram, sequence, ER, flow, C4 | On-Demand Runbook |
| **Isometric System Drawings** | `wheresryan22/anatomy` | Anatomy, isometric, system teardown | On-Demand Runbook |
| **Reverse Engineering & Binaries**| `morluto/rea` | Reverse engineer, binary, decompile | On-Demand Runbook |

---

## ➕ How to Add New Skills

To add a new skill to this repository:
1. Append the repository URL under the appropriate section in **Curated Skills Catalog**:
   ```markdown
   - [username/repo-name](https://github.com/username/repo-name): Brief description and primary capabilities.
   ```
2. Add a corresponding entry in the **On-Demand Routing Matrix** with its trigger keywords.
3. Commit and push:
   ```bash
   git add README.md
   git commit -m "feat: add new agent skill <name>"
   git push
   ```
4. Any AI agent reading this updated `README.md` will automatically discover, link, and route the newly added skill.
