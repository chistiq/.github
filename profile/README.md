<div align="center">

# Chistiq

## Intelligence infrastructure company behind RapidKit and Workspai

Home of **Workspai**, **RapidKit Core**, and open-source tools that help
developers, IDEs, CI, and AI agents understand and work with the same software
system.

[Chistiq](https://chistiq.com) · [RapidKit](https://www.getrapidkit.com) · [Workspai](https://www.workspai.com) · [Learn Workspace Intelligence](https://www.workspai.dev)

[![Workspai npm](https://img.shields.io/npm/v/workspai?style=flat-square&label=workspai&color=cb3837)](https://www.npmjs.com/package/workspai)
[![Workspai VS Code](https://img.shields.io/visual-studio-marketplace/v/rapidkit.rapidkit-vscode?style=flat-square&label=VS%20Code&color=007acc)](https://marketplace.visualstudio.com/items?itemName=rapidkit.rapidkit-vscode)
[![RapidKit Core](https://img.shields.io/pypi/v/rapidkit-core?style=flat-square&label=rapidkit-core&color=3776ab)](https://pypi.org/project/rapidkit-core/)

</div>

---

# What is Chistiq?

Chistiq is the intelligence infrastructure company behind RapidKit and
Workspai. We build open-source tools for creating software, understanding how
its parts fit together, and keeping it healthy as it changes.

**Workspai** gives people and tools a shared view of a software system.
**RapidKit Core** helps teams create and maintain production-ready
applications.

---

# Workspace Intelligence

Software is more than source code.

Modern software is more than code. It includes projects, dependencies, APIs,
deployment files, documentation, rules, tests, owners, and release checks.

Workspace Intelligence connects that information and keeps a saved,
checkable view that humans and AI can use together.

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
| **[Workspai CLI](https://github.com/chistiq/workspai)** | Connect projects, map a software system, check changes, and prepare context for people and tools. |
| **[Workspai for VS Code](https://github.com/chistiq/rapidkit-vscode)** | View workspace status, reports, repair actions, and AI workflows inside VS Code. |
| **[RapidKit Core](https://github.com/chistiq/rapidkit-core)** | Create Python applications and add reusable modules, setup, and health checks. |
| **Reference Workspaces** | Learn from example projects and common adoption patterns. |

---

# See Workspace Intelligence on Existing Software

Workspai does not require a rewrite or repository move. Connect an existing
project, then run one command to build a shared and checkable view for people
and tools.

```bash
cd /absolute/path/to/project
npx workspai adopt .
```

`adopt` creates or reuses a minimal workspace in the default Workspai location
and leaves the project where it is. Without the VS Code extension, copy the
exact `Next shell step` printed by the CLI and continue in that workspace
terminal:

```bash
cd ~/.workspai/workspaces/workspai
npx workspai workspace intelligence run --for-agent generic --strict --json
```

Use `generic` for vendor-neutral context, or choose `codex`, `claude`,
`cursor`, or `orca`. The same chain also syncs shared grounding for GitHub
Copilot, VS Code, and `AGENTS.md` consumers.

The run maps the system, records how its parts connect, checks what changes may
affect, runs health and release checks, and prepares focused AI context under
`.workspai/`. Developers, CI, VS Code, MCP clients, and AI agents can use the
same result. If something is not ready, Workspai shows the reason and where the
answer came from.

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
