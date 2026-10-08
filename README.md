# Claude Code Web Beginner Testing 🚀

A structured, battle-tested multi-agent development environment designed for **Claude Code**, **Gemini**, and modern agentic coding harnesses.

This repository serves as a clean testing ground for agent-driven web development, test-driven development (TDD), and multi-specialist coordination.

---

## 👥 Multi-Agent Persona Roster

Every interaction within this workspace coordinates specialized sub-agents:

| Agent | Role | Focus & Specialty |
| :--- | :--- | :--- |
| **Jane** | Lead Architect & Security | Executive technical coordination, zero-mistake architecture, security audits, and risk management. |
| **Aisha** | UI/UX & Frontend Lead | Aesthetic web interfaces, dark modes, fluid motion design, CSS systems, and glassmorphism. |
| **Aura** | Documentation Specialist | Structured documentation for Microsoft Word, Excel, Google Docs, and Sheets. |
| **Nasuha (Suha)** | Deep Web Investigator | Live web search, GitHub repo exploration, evidence synthesis, and citation verification. |
| **Syuhada (Syu)** | Ruthless Quality Engineer | Strict QA verification, empirical test validation, browser testing, and regression gating. |
| **Anis** | Token CFO & Efficiency | Prompt cost optimization, context budget audit, and anti-bloat enforcement. |
| **Aina** | Database Architect | Schema design, migrations, indexing, and high-performance queries. |

---

## 🧠 Karpathy Core Operating Principles

All agents adhere strictly to Andrej Karpathy's engineering guidelines:

1. **Think Before Coding:** Never make silent assumptions. Surface tradeoffs, ask clarifying questions, and design before modifying code.
2. **Simplicity First:** Write the minimum code required to solve the task cleanly. Avoid bloated abstractions and overengineering.
3. **Surgical Changes:** Modify only what is strictly necessary. Never perform drive-by formatting or touch orthogonal files.
4. **Goal-Driven Execution:** Define measurable verification criteria and verify with empirical commands before declaring completion.

---

## 🛠️ Submodules & Skill Libraries Included

This environment integrates four foundational agentic libraries:

- **[ECC (Enterprise Claude Code)](https://github.com/affaan-m/ECC):** Comprehensive skills library covering backend patterns, frontend accessibility, security, and cloud ops.
- **[Andrej Karpathy Skills](https://github.com/multica-ai/andrej-karpathy-skills):** Practical mental models for modern AI engineering.
- **[Open Design](https://github.com/nexu-io/open-design):** UI/UX standards and design tokens.
- **[Ruflo](https://github.com/ruvnet/ruflo):** Multi-agent swarm orchestration and agent tools.

---

## 🚀 Getting Started

### 1. Cloning the Repository with Submodules
```bash
git clone --recurse-submodules https://github.com/ArRawi/Claude-Code-Web-Beginner-Testing.git
cd Claude-Code-Web-Beginner-Testing
```

If you cloned without `--recurse-submodules`:
```bash
git submodule update --init --recursive
```

### 2. Running Claude Code
Launch Claude Code in the workspace root:
```bash
claude
```

The system automatically loads the agent rules from `AGENTS.md`, `CLAUDE.md`, and the `skills/` directory.

### 3. Testing Web Workflows
Try issuing prompts such as:
- *"Jane, let's design a simple habit tracker web app using TDD."*
- *"Aisha, design a modern dark-mode landing page with glassmorphism."*
- *"Nasuha, research the latest Vite plugins for fast web builds."*
