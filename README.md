<p align="center">
  <picture>
    <img
      alt="José Daniel Martínez Moná in a fern garden at night"
      src="./assets/profile-banner.jpg"
      width="1200"
    >
  </picture>
</p>

# Hi, I'm José Daniel Martínez Moná

The ground is shifting. AI is changing not only what we build, but how we build
it, and developers have to change with it.

This portfolio is a record of my own evolution: seven years of frontend and
full-stack development and, more recently, a transition into AI-assisted and
agentic software engineering. I have worked with coding assistants for more than
a year and have spent the past few months studying agentic programming more
deliberately.

For me, working with coding agents is less about generating code and more about
managing risk and maintaining software quality. That means providing the right
context, setting clear boundaries, reviewing decisions and changes, testing real
behavior, and remaining accountable for the result. The projects below are where
I am putting that approach into practice.

[LinkedIn](https://www.linkedin.com/in/mmjosedaniel) · Based in Armenia, Colombia

## Portfolio projects

### VoxLeaf

**Local/portfolio MVP (v0.1.0) · 2026**

VoxLeaf is an AI-powered, privacy-first Windows book reader that opens EPUB
files and reads them aloud in Spanish or English. Its multi-model TTS
implementation includes bundled Piper CPU voices, the optional Chatterbox GPU
model on compatible hardware, and development-only Qwen3-TTS profiles. Books,
inference, and generated speech stay on the user's computer, with audio retained
only in bounded memory.

Developed end to end through a Codex-centered agentic workflow, VoxLeaf combines
Tauri, React, TypeScript, Rust, and Python with secure EPUB ingestion, a
reflowable reader, synchronized narration, cancellable generation, typed
cross-process contracts, automated testing, and Windows packaging.

[View the source](https://github.com/mmjosedaniel/voxleaf) ·
[Watch the demo](https://www.youtube.com/watch?v=2CU36tmh7Fc)

<a href="https://www.youtube.com/watch?v=2CU36tmh7Fc">
  <img
    alt="Watch the VoxLeaf 0.1.0 demo on YouTube"
    src="https://img.youtube.com/vi/2CU36tmh7Fc/maxresdefault.jpg"
    width="720"
  >
</a>

### Rick and Morty Explorer

**Completed 0-to-1 full-stack portfolio project · 2026**

Rick and Morty Explorer was built to demonstrate how agentic programming can
take a full-stack application from requirements and architecture to a verified
release candidate. The product includes character search and detail views,
favorites, comments, deterministic data import, PostgreSQL persistence, bounded
Redis caching, typed GraphQL operations, responsive states, and CI-backed
verification.

The repository also serves as an agentic software engineering harness. It turns
requirements into traceable work through documentation maps, ADRs, task graphs
and ExecPlans, project-scoped agent roles and skills, write leases,
milestone-slice TDD with separate test and implementation ownership, and
evidence-backed acceptance. The application stack includes React, TypeScript,
TanStack Query, Tailwind CSS, Vite, Node.js, Express, GraphQL Yoga, PostgreSQL,
Redis, Docker Compose, Vitest, Playwright, and GitHub Actions.

[View the source](https://github.com/mmjosedaniel/rick-and-morty-explorer)

### A11y Evidence Lab

**Concept and feasibility research · 2026**

A11y Evidence Lab is a planned accessibility analysis application for turning
deterministic browser findings into traceable, guidance-backed remediation
decisions. It is designed around cited explanations, explicit confidence and
manual checks, human review, and before-and-after evidence—supporting
accessibility investigation without claiming certification or legal compliance.

The engineering concept explores an evidence-centered RAG workflow with
LangChain for retrieval and model integration, LangGraph for stateful review and
recovery paths, and LangSmith for tracing, evaluation datasets, and regression
analysis. The repository currently contains product planning and local-MVP
feasibility research; implementation has not started.

[View the source](https://github.com/mmjosedaniel/a11y-evidence-lab)

## Core technologies

React · TypeScript · JavaScript · Node.js · NestJS · GraphQL · PostgreSQL ·
Redis · TanStack Query · Tauri · Rust · Docker · Vitest · Playwright · AWS · GCP ·
Python
