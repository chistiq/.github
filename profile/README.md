<div align="center">

# Chistiq

## Intelligence infrastructure company behind RapidKit and Workspai

Home of **Workspai**, **RapidKit Core**, and the technologies that enable developers, IDEs, CI, and AI agents to operate from a shared understanding of software.

[Chistiq](https://chistiq.com) · [RapidKit](https://www.getrapidkit.com) · [Workspai](https://www.workspai.com) · [Learn Workspace Intelligence](https://www.workspai.dev)

[![Workspai npm](https://img.shields.io/npm/v/workspai?style=flat-square&label=workspai&color=cb3837)](https://www.npmjs.com/package/workspai)
[![Workspai VS Code](https://img.shields.io/visual-studio-marketplace/v/rapidkit.rapidkit-vscode?style=flat-square&label=VS%20Code&color=007acc)](https://marketplace.visualstudio.com/items?itemName=rapidkit.rapidkit-vscode)
[![RapidKit Core](https://img.shields.io/pypi/v/rapidkit-core?style=flat-square&label=rapidkit-core&color=3776ab)](https://pypi.org/project/rapidkit-core/)

</div>

---

# What is Chistiq?

Chistiq is the intelligence infrastructure company behind RapidKit and
Workspai. We build open-source foundations for creating, understanding, and
operating software systems.

Instead of treating software as disconnected repositories, files, and prompts, Chistiq enables developers, AI agents, IDEs, and engineering systems to collaborate through a shared workspace model built on architecture, context, knowledge, governance, and execution.

The ecosystem combines **Workspai** for workspace intelligence with **RapidKit Core** for production-ready application development, enabling teams to build, understand, and evolve modern software systems.

---

# Workspace Intelligence

Software is more than source code.

Modern software systems include architecture, dependencies, operational knowledge, ownership, runtime behavior, governance, documentation, and the decisions that shape how systems evolve.

Workspace Intelligence transforms those signals into a shared, evidence-backed model that humans and AI can understand together.

```mermaid
flowchart TB
    INPUTS["Software Systems<br/>Code · Architecture · Knowledge · Runtime · Policies"]
    INTELLIGENCE["Workspace Intelligence<br/>Model · Graph · Context · Evidence · Governance"]
    OUTPUTS["Shared Intelligence<br/>Reports · Skills · AGENTS.md · Impact · Automation"]
    CONSUMERS["Developers · IDEs · CI · AI Agents"]

    INPUTS --> INTELLIGENCE --> OUTPUTS --> CONSUMERS
    CONSUMERS -. Continuous feedback .-> INPUTS

    classDef core fill:#0f172a,color:#f8fafc,stroke:#38bdf8,stroke-width:2px;
    class INTELLIGENCE core;
```

Existing software can be adopted without changing repositories, frameworks, or programming languages. Native project kits are available for teams starting new applications.

---

# Products

| Product | Role |
| --- | --- |
| **[Workspai CLI](https://github.com/chistiq/workspai)** | Workspace Intelligence platform for creating, adopting, modeling, governing, and operating software workspaces across projects, languages, and frameworks. |
| **[Workspai for VS Code](https://github.com/chistiq/rapidkit-vscode)** | Native developer experience for Workspace Intelligence, context, evidence, AI workflows, and workspace operations. |
| **[RapidKit Core](https://github.com/chistiq/rapidkit-core)** | Production-ready Python framework featuring modular architecture, reusable modules, project scaffolding, and powerful developer tooling. |
| **Reference Workspaces** | Example projects, reusable workspace kits, adoption patterns, and reference implementations across modern software stacks. |

---

# Start With Existing Software

```bash
npx workspai adopt ../existing-project --json

cd ~/.workspai/workspaces/workspai

npx workspai workspace model --json --write
npx workspai workspace context --for-agent --json --write
npx workspai workspace agent-sync --write --refresh-context
npx workspai workspace verify --strict --json
```

The resulting workspace intelligence powers documentation, AI grounding, IDE integrations, governance, impact analysis, release workflows, and engineering automation from the same shared source of truth.

---

# Ecosystem

| Project | Description |
| --- | --- |
| **[RapidKit](https://www.getrapidkit.com)** | Open-source Python framework and development platform for production-ready applications. |
| **[Workspai](https://www.workspai.com)** | Workspace Intelligence platform for developers, AI agents, and engineering systems. |
| **[workspai.dev](https://www.workspai.dev)** | Documentation, guides, tutorials, and Workspace Intelligence learning resources. |

---

# Open Source

We build in the open and believe software should remain understandable, governable, and evidence-driven.

Our principles are simple:

- Shared understanding over isolated context.
- Explicit contracts over hidden assumptions.
- Evidence before confidence.
- Open standards over vendor lock-in.
- Software that humans and AI can understand together.

---

<div align="center">

## One workspace. One truth.

### Shared by humans and AI.

</div>
