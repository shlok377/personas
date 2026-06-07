# 🤖 Gemini Agent Router

> **Precision AI Orchestration for Modern Software Engineering**

Gemini Agent Router is a specialized framework designed to streamline the software development lifecycle by leveraging distinct, high-fidelity AI **Personas**. Each **Persona** is meticulously crafted with specific objectives, workflows, and constraints to ensure surgical implementation and architectural integrity.

---

## 🌟 Core Personas

| Persona | Role | Primary Objective |
| :--- | :--- | :--- |
| **🏗️ Project Architect** | Design Lead | Establishes the high-level system architecture and standards. |
| **📋 Planner** | Strategist | Requirements gathering and detailed blueprint creation. |
| **✨ Feature Coder** | Integration | Implements new features into existing code with zero regressions. |
| **💻 Coder** | Implementation | Translates blueprints into production-grade, modular code. |
| **🔧 Fixer** | Troubleshooting | Rapidly diagnoses and repairs bugs with surgical precision. |
| **🎨 UI Designer** | Visual Lead | Crafts interactive, aesthetic, and functional user interfaces. |
| **🛡️ Security Auditor** | Guardian | Ensures codebase integrity and identifies potential vulnerabilities. |
| **🧹 Maintainer** | Optimization | Focuses on refactoring, scalability, and code health. |
| **🚀 Setup** | Foundation | Handles project initialization and scaffolding. |

---

## 🚦 Core Routing Directive

The framework operates on a strict "Classify then Load" principle. Upon any user request, the system follows this **Persona** selection process:

1.  **Analyze Intent**: Determine which single **Persona** best fits the immediate requirement.
2.  **Targeted Load**: Access *only* the specific `.md` file in `.gemini-agents/` to keep context lean.
3.  **Adopt Persona**: Strictly follow the constraints and workflows of the chosen **Persona**.

---

## 🤝 Handoff Protocol

To maintain consistency during complex projects, every **Persona** follows a standardized handoff protocol:

- **Finalize State**: All current-phase deliverables are saved and verified.
- **Explicit Handoff**: The current **Persona** signals the transition (e.g., *"Transitioning to Feature Coder Persona"*).
- **User Confirmation**: The system waits for user approval before activating the next **Persona** in the chain.

---

## 📂 Project Structure

```text
/
├── .gemini-agents/       # Core Persona definitions (Markdown)
│   ├── feature_coder.md
│   ├── coder.md
│   ├── fixer.md
│   ├── planner.md
│   └── ...
└── GEMINI.md             # The central router and entry point
```

---

## 🛠 Usage

To activate a specific **Persona**, the system refers to the definitions in `.gemini-agents/`. This ensures the AI assistant adopts the correct strategy, constraints, and implementation standards for the task at hand.

---

## ⚖️ Standards & Philosophy

- **Persona Centricity**: Every interaction is driven by a specialized **Persona** mindset.
- **Surgical Precision**: Targeted changes that minimize context noise.
- **Modularity First**: Adherence to the Single Responsibility Principle.
- **Empirical Validation**: Rigorous testing is mandatory for every **Persona** phase.

---

<p align="center">
  <i>Built for the next generation of AI-native developers.</i>
</p>
