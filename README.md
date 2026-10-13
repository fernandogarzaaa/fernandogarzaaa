# Hi, I'm Fernando 👋

**AI / ML engineer building the trust, eval, and runtime layers around LLM agents.**
I ship small, tested tools that make AI systems measurable and safe to run: mutation-tested evals, guardrails, MCP servers, and local-first agent runtimes.

📍 Philippines (UTC+8) · 🟢 Open to AI/ML engineering roles, remote or on-site

---

## ⚡ Highlights

| Project | What it does | Proof |
|---|---|---|
| [**testteeth**](https://github.com/fernandogarzaaa/testteeth) | Mutation-test grader for AI-written tests: CLI, pytest plugin, MCP server. Wraps StrykerJS and cargo-mutants for TS/JS and Rust. | On [PyPI](https://pypi.org/project/testteeth/). Weak AI tests score 20.7% vs 96.6% for strong ones. |
| [**sealbox**](https://github.com/fernandogarzaaa/sealbox) | Compute-to-data MCP server: agents query sensitive data inside an encrypted vault, and an egress gate (k-anonymity, DP noise, PII, code fingerprints, leakage budget) checks every output. | 56 red-team attacks, 0 leaks. 344 tests, 95% coverage. |
| [**semcache**](https://github.com/fernandogarzaaa/semcache) | Semantic cache proxy for OpenAI-compatible APIs. | 65.1% hit rate, 0.51% false hits on a paraphrase workload. |
| [**regresscheck**](https://github.com/fernandogarzaaa/regresscheck) | Prompt/model regression gate for CI: a bad prompt change fails the PR. | Mutation score 95.6%. |
| [**evalforge**](https://github.com/fernandogarzaaa/evalforge) | Turns production LLM logs into eval datasets. | Mutation score 81.2% → 98.4%. |
| [**peertrace**](https://github.com/fernandogarzaaa/peertrace) | P2P sharing of agent run logs on Hypercore/Hyperswarm: signed append-only logs with live tail. | On [npm](https://www.npmjs.com/package/peertrace). |
| [**project-away**](https://github.com/fernandogarzaaa/project-away) | Hands-free PC control: webcam hand gestures drive the cursor, local Whisper handles voice typing. | Windows installer on [Releases](https://github.com/fernandogarzaaa/project-away/releases). |

## 🧪 Agent infrastructure & research

- [**AXIOM-AETHER**](https://github.com/fernandogarzaaa/AXIOM-AETHER) (Rust): test-time-training runtime for fast-weight context adaptation, compression proxying, and MCP access.
- [**genesis**](https://github.com/fernandogarzaaa/genesis): assurance for machine-authored work. Audit the verifier, not the artifact.
- [**ghost-chimera-rs**](https://github.com/fernandogarzaaa/ghost-chimera-rs) (Rust): local agent control plane with provider routing, cost ledger, and an Electron console.
- [**OpenChimera_v1**](https://github.com/fernandogarzaaa/OpenChimera_v1): local-first multi-LLM orchestration runtime.
- [**ape-mcp**](https://github.com/fernandogarzaaa/ape-mcp): MCP server with an embedded agent, task graphs, and cost-aware model routing.
- [**sigil**](https://github.com/fernandogarzaaa/sigil) + [**sigil-index**](https://github.com/fernandogarzaaa/sigil-index): trust scanning and signed trust badges for MCP servers.
- [**ChimeraLang**](https://github.com/fernandogarzaaa/ChimeraLang) + [**chimeralang-mcp**](https://github.com/fernandogarzaaa/chimeralang-mcp): uncertainty-aware reasoning DSL with probabilistic types, on [PyPI](https://pypi.org/project/chimeralang/).

## 🏢 Applied AI apps (v1.0.0, FastAPI + Postgres + Docker)

[callinsights](https://github.com/fernandogarzaaa/callinsights) (sales call scoring) · [tenderbuddy](https://github.com/fernandogarzaaa/tenderbuddy) (tender discovery and bid prep) · [enterprise-brain](https://github.com/fernandogarzaaa/enterprise-brain) (Q&A over company docs) · [vitality-bss](https://github.com/fernandogarzaaa/vitality-bss) (healthcare document processing) · [clusterx-os](https://github.com/fernandogarzaaa/clusterx-os) (lead qualification agent)

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat)

**Focus:** LLM evals & mutation testing · guardrails & data privacy · MCP servers · model routing & caching · local inference (llama.cpp, Whisper)

## 🧭 How I work

- **Measure it.** Every project ships with numbers you can reproduce, and says plainly what is untested.
- **Test the tests.** I mutation-test my own suites with testteeth, usually to 90%+.
- **Local-first.** Runs on your machine or your infra, with clear tool surfaces and no hidden calls.
