# Oumar Ibrahim (`IamOumarIbrahim`)

<p align="left">
  <strong>Electrical & Computer Engineering Senior</strong> @ University of Sharjah<br />
  Building zero-trust AI developer tooling (Model Context Protocol), an open-source AI video platform, & researching 6G DSP architectures.
</p>

<p align="left">
  <a href="https://linkedin.com/in/oumarmamounibrahim"><img src="https://img.shields.io/badge/LinkedIn-Oumar%20Ibrahim-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://orcid.org/0009-0008-0312-1605"><img src="https://img.shields.io/badge/ORCID-0009--0008--0312--1605-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID" /></a>
  <img src="https://img.shields.io/badge/Location-Sharjah%2C%20UAE-0F766E?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Focus-AI%20Tooling%20%7C%206G%20DSP%20%7C%20AI%20Video-10B981?style=flat-square" alt="Focus" />
</p>

---

> **Currently building:** an Open-Source AI Video Platform ([Pumblo](https://github.com/IamOumarIbrahim/pumblo)), 6G Radar & RF Signal Processing Research ([radar-rf-research-stack](https://github.com/IamOumarIbrahim/radar-rf-research-stack)), Governed Agent MCP Infrastructure ([governed-agent-mcp-stack](https://github.com/IamOumarIbrahim/governed-agent-mcp-stack)), Developer Capability Tooling ([SkillDeck](https://github.com/IamOumarIbrahim/SkillDeck)), & Rooftop Solar Feasibility Automation ([SolarScan](https://github.com/IamOumarIbrahim/SolarScan)).

---

## Consumer Platforms

### [Pumblo](https://github.com/IamOumarIbrahim/pumblo)
> **The YouTube of AI Video — Provenance-Verified, Human-Accountable, Open-Source**

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg?style=flat-square)](https://github.com/IamOumarIbrahim/pumblo/blob/main/LICENSE)
[![Status: Live](https://img.shields.io/badge/status-live-brightgreen?style=flat-square)](https://www.pumblo.ai)
[![Built with Next.js](https://img.shields.io/badge/built%20with-Next.js-000000?style=flat-square&logo=next.js)](https://nextjs.org)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange?style=flat-square)](#)

Live at **[pumblo.ai](https://www.pumblo.ai)** — every video is AI-generated, every account is a real verified human, and every ranking is earned, never bought.

* **Provenance-first**: C2PA Content Credentials are validated at upload and preserved through re-encoding, instead of being reduced to a generic "may be AI" label.
* **One human, one account**: email/password sign-up gated by a Proof-of-Humanity challenge (Cloudflare Turnstile) before any write access — no anonymous or bot accounts.
* **Synthesis Quality Score (SQS)**: a transparent, weighted Discovery ranking formula (Technical Fidelity, Provenance Completeness, Human Engagement, Creator Trust, Freshness) that deliberately excludes raw watch-time and click-through.
* **Upload anywhere**: browser Studio, REST API, or a one-line CLI (`pumblo upload`), all on the same metadata schema — built for individual creators and pipeline/batch uploaders alike.

<details>
<summary><strong>Quickstart (Self-Hosting)</strong></summary>

```bash
git clone https://github.com/IamOumarIbrahim/pumblo.git
cd pumblo
cp .env.example .env.local
npm install
npm run db:migrate
npm run dev
```
</details>

---

## Flagship Research & Open-Source Stacks

### [radar-rf-research-stack](https://github.com/IamOumarIbrahim/radar-rf-research-stack)
> **Unified Monorepo for FMCW Radar DSP Simulation, Selective State-Space (Mamba) ISAC Estimation, and Sequence-Model Benchmarking**

[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/radar-rf-research-stack?style=flat-square&color=10B981&logo=github)](https://github.com/IamOumarIbrahim/radar-rf-research-stack)
[![Python](https://img.shields.io/badge/Python-3.13%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.10%2B-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![Architectures](https://img.shields.io/badge/Architectures-Mamba%20%7C%20Transformer%20%7C%20LSTM-7C3AED?style=flat-square)](#)

* **Pillar I — FMCW Radar DSP & Counter-UAS**: End-to-end signal generation pipeline featuring 2D CA-CFAR target detection, MVDR jammer nulling, and micro-Doppler classification.
* **Pillar II — Mamba ISAC Research**: Linear-time selective state-space model for joint sensing-communication estimation in 6G systems.
* **Pillar III — Standardized RF Benchmarking (`rf-bench`)**: Compute-normalized benchmark harness evaluating sequence models under matched parameter constraints on complex-baseband IQ data.

<details>
<summary><strong>Quickstart</strong></summary>

```bash
git clone https://github.com/IamOumarIbrahim/radar-rf-research-stack.git
cd radar-rf-research-stack
```
</details>

---

### [governed-agent-mcp-stack](https://github.com/IamOumarIbrahim/governed-agent-mcp-stack)
> **Zero-Trust Model Context Protocol (MCP) Server Suite for SDR/Radar DSP & CAD/SPICE Tool Governance**

[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/governed-agent-mcp-stack?style=flat-square&color=10B981&logo=github)](https://github.com/IamOumarIbrahim/governed-agent-mcp-stack)
[![MCP Standard](https://img.shields.io/badge/MCP-1.0.0-7C3AED?style=flat-square)](https://modelcontextprotocol.io/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)

* **`SpectraMCP`**: Specialized MCP server equipping LLM agents with native tools for RF signal processing, SDR data handling, and radar DSP analysis.
* **`interlock-mcp`**: Governance & policy enforcement server providing zero-trust access control, permission sandboxing, and execution logging for CAD, EDA, and SPICE tools.
* **Fleet Observability**: Unified audit telemetry tracking agent tool usage, argument payloads, and policy evaluations across sessions.

<details>
<summary><strong>Claude Desktop Configuration</strong></summary>

```json
{
  "mcpServers": {
    "spectramcp": {
      "command": "uvx",
      "args": ["spectramcp"]
    },
    "interlock": {
      "command": "uvx",
      "args": ["interlock-mcp"]
    }
  }
}
```
</details>

---

## Developer Tooling & Engineering Systems

### [SkillDeck](https://github.com/IamOumarIbrahim/SkillDeck)
> **Modular AI Agent & Developer Capability Suite for Automated Engineering Workflows**

[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/SkillDeck?style=flat-square&color=10B981&logo=github)](https://github.com/IamOumarIbrahim/SkillDeck)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)

* **`readme-forge`**: AST-driven automated documentation generator mapping function signatures and project architectures.
* **`reviewerzero`**: Automated academic paper auditing pipeline inspecting empirical claims, data leaks, and baseline fairness.
* **Prompt Engineering & Code Unrolling**: Production-grade agent skill routines for deterministic code transformation and reasoning.

---

### [SolarScan](https://github.com/IamOumarIbrahim/SolarScan)
> **End-to-End Rooftop Solar Feasibility Automation & Engineering PV System Sizing Platform**

[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/SolarScan?style=flat-square&color=10B981&logo=github)](https://github.com/IamOumarIbrahim/SolarScan)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)

* **Geospatial Extraction**: Building footprint analysis and solar irradiance estimation from geospatial locations.
* **NREL SAM Integration**: Automated configuration and export to NREL System Advisor Model for technical and economic simulation.

<details>
<summary><strong>Quickstart & Usage</strong></summary>

```bash
git clone https://github.com/IamOumarIbrahim/SolarScan.git && cd SolarScan
pip install -r requirements.txt && python -m solarscan "Computer Science Department W5 Sharjah"
```
</details>

---

## Tech & Tooling Suite

| Category | Tools & Technologies |
| :--- | :--- |
| **AI / ML & Agent Infrastructure** | `PyTorch` `Model Context Protocol (MCP)` `State-Space Models (Mamba)` `FastMCP` `OpenCV` |
| **DSP & Communications** | `Python` `MATLAB` `6G ISAC` `FMCW Radar` `2D CA-CFAR` `MVDR` `Adaptive Filtering` `PySDR` |
| **Web & Platform Infrastructure** | `Next.js` `TypeScript` `PostgreSQL` `Redis` `Cloudflare R2` `C2PA Content Credentials` |
| **Hardware & EDA** | `KiCad` `LTspice` `FreeCAD` `Discrete TTL Logic (50+ ICs)` |
| **Languages & Systems** | `Python` `C/C++` `MATLAB` `TypeScript` `Bash` `Windows API` |

---

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-10B981?style=flat-square" alt="MIT License" />
</p>
