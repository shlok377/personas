# 🤖 Antigravity Agent Router

> **Precision AI Orchestration for Modern Software Engineering**

Antigravity Agent Router is a specialized framework designed to streamline the software development lifecycle by leveraging distinct, high-fidelity AI **Personas** implemented as native **Antigravity CLI Customizations**. Each **Persona** is structured as an individual **Skill** with specific objectives, workflows, and constraints to ensure surgical implementation and architectural integrity.

---

## 🌟 Core Personas (Discovered as Skills)

| Persona / Skill | Command ID | Primary Objective |
| :--- | :--- | :--- |
| **📋 Planner** | `planner` | Requirements gathering and detailed roadmap planning. |
| **🎨 UI Designer** | `ui-designer` | Visual architecture, layouts, design tokens, and specs. |
| **🏗️ Project Architect** | `project-architect` | System architecture, contracts, and data modeling. |
| **🚀 Setup** | `initial-setup` | Physical scaffolding and workspace configuration. |
| **💻 Coder** | `coder` | Logic implementation, type-safety, and module builds. |
| **✨ Feature Coder** | `feature-coder` | Safe feature integration with zero regressions. |
| **🔧 Fixer** | `fixer` | Forensic bug isolation, reproductions, and permanent repairs. |
| **🛡️ Security Auditor** | `security-auditor` | Security scanning, secret auditing, and licensing. |
| **🧹 Maintainer** | `maintainer` | Refactoring, code health, and tech debt reduction. |

---

## 🚦 Core Routing & Customization Model

This framework leverages the native customization capabilities of the **Antigravity CLI (`agy`)**. Rather than relying on rigid manual routing steps, the system is fully integrated:

1. **Auto-Discovery**: Place the `.agents/` folder in your workspace root. The `agy` CLI automatically discovers the custom skills and rules.
2. **Flexible Loading**: The active agent analyzes your request, reviews the rules in [.agents/AGENTS.md](file:///.agents/AGENTS.md), and reads the specific [SKILL.md](file:///.agents/skills/) instructions for the persona that fits your current task.
3. **Optimized Context**: By loading only the relevant skill instructions when needed, the agent maintains maximum context space for your codebase and implementation.

---

## 📂 Project Structure

```text
/
├── .agents/                # Workspace Customizations Root
│   ├── AGENTS.md           # Workspace Rules (Core Directives & Handoffs)
│   └── skills/             # Custom Persona Skills (discovered by agy CLI)
│       ├── planner/
│       │   └── SKILL.md
│       ├── ui_designer/
│       │   └── SKILL.md
│       ├── ...
└── README.md               # Framework entry point documentation
```

---

## 🛠 Usage & Execution

When starting a project or feature:
- Activate the `planner` skill to define your roadmap in `docs/roadmap.md`.
- Move through the chain (Architect $\rightarrow$ Setup $\rightarrow$ Coder/Fixer $\rightarrow$ Auditor $\rightarrow$ Maintainer) as the task demands.
- Run `/skills` in your `agy` CLI terminal session to verify that the custom skills are loaded correctly.

---

## ⚖️ Standards & Philosophy

- **Persona Centricity**: Every step is driven by a specialized operational mindset.
- **Surgical Edits**: Targeted updates to minimize file bloat and context noise.
- **Modular Design**: Adherence to the Single Responsibility Principle.
- **Empirical Validation**: Verification and regression testing are mandatory.
