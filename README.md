# Oumar Ibrahim (`IamOumarIbrahim`)

<p align="left">
  <strong>Electrical & Computer Engineering Senior</strong> @ University of Sharjah<br />
  Building open-source AI developer tooling (Model Context Protocol) & researching 6G DSP architecture.
</p>

<p align="left">
  <a href="https://linkedin.com/in/oumarmamounibrahim"><img src="https://img.shields.io/badge/LinkedIn-Oumar%20Ibrahim-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://orcid.org/0009-0008-0312-1605"><img src="https://img.shields.io/badge/ORCID-0009--0008--0312--1605-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID" /></a>
  <img src="https://img.shields.io/badge/Location-Sharjah%2C%20UAE-0F766E?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Focus-AI%20Tooling%20%7C%206G%20DSP-10B981?style=flat-square" alt="Focus" />
</p>

---

> ⚡ **Currently building:** Scaling [MCPntt](https://github.com/IamOumarIbrahim/MCPntt) for hardware EDA/SPICE workflows & benchmarking SSMs for ISAC.

---

## 🛠️ Flagship Open-Source Projects

### 🔌 [MCPntt](https://github.com/IamOumarIbrahim/MCPntt)
> **Unified Model Context Protocol (MCP) Server for Desktop CAD, EDA & SPICE**

Connects Claude Desktop, Antigravity, and autonomous AI agents directly to **KiCad**, **FreeCAD**, **LTspice**, and local workspace telemetry.

[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/MCPntt?style=flat-square&color=10B981&logo=github)](https://github.com/IamOumarIbrahim/MCPntt)
[![MCP Standard](https://img.shields.io/badge/MCP-1.0.0-7C3AED?style=flat-square)](https://modelcontextprotocol.io/)
[![KiCad](https://img.shields.io/badge/KiCad-10.0-3146B5?style=flat-square&logo=kicad&logoColor=white)](https://kicad.org)

<details>
<summary>📋 <strong>Claude Desktop Setup Snippet</strong></summary>

```json
{
  "mcpServers": {
    "mcpntt": {
      "command": "uvx",
      "args": ["mcpntt"]
    }
  }
}
```
</details>

---

### 🖊️ [handrolled](https://github.com/IamOumarIbrahim/handrolled)
> **Claude Skill transforming verbose LLM output into clean, procedural, unrolled code**

Strips away robotic comments, unnecessary functional abstractions, and boilerplate, forcing Claude models to write explicit, readable code.

[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/handrolled?style=flat-square&color=10B981&logo=github)](https://github.com/IamOumarIbrahim/handrolled)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-D97706?style=flat-square&logo=anthropic&logoColor=white)](https://github.com/IamOumarIbrahim/handrolled)

<details>
<summary>🚀 <strong>One-Command Installation</strong></summary>

```bash
mkdir -p ~/.claude/skills && curl -o ~/.claude/skills/handrolled.md https://raw.githubusercontent.com/IamOumarIbrahim/handrolled/main/SKILL.md
```
</details>

---

### 🐍 [mamba-isac](https://github.com/IamOumarIbrahim/mamba-isac)
> **Selective State-Space Architecture for 6G OFDM ISAC Channel Estimation**

PyTorch benchmarking framework evaluating Mamba (SSMs) against Transformers for joint channel and target parameter estimation in wireless communications.

[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/mamba-isac?style=flat-square&color=10B981&logo=github)](https://github.com/IamOumarIbrahim/mamba-isac)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)

<details>
<summary>⚡ <strong>Quickstart & Evaluation</strong></summary>

```bash
git clone https://github.com/IamOumarIbrahim/mamba-isac.git && cd mamba-isac
pip install -r requirements.txt && python eval/evaluate_all.py
```
</details>

---

## 📡 Signal Processing & Hardware Systems

* **[WokStation](https://github.com/IamOumarIbrahim/WokStation)** — Windows TUI orchestrating local offline AI coding models (Qwen, Kimi, DeepSeek) via Ollama with prompt broadcasting and crash recovery.
* **[counter-uas-fmcw-radar](https://github.com/IamOumarIbrahim/counter-uas-fmcw-radar)** — X-band FMCW radar pipeline simulation featuring 2D CA-CFAR detection, MVDR jammer nulling, and micro-Doppler STFT classification.

---

## 🧰 Tech & Tooling Suite

| Category | Tools & Technologies |
| :--- | :--- |
| **AI / ML & Infrastructure** | `PyTorch` `Model Context Protocol (MCP)` `Ollama` `State-Space Models (Mamba)` |
| **DSP & Communications** | `MATLAB` `6G ISAC` `FMCW Radar` `CA-CFAR` `Adaptive Filtering (NLMS)` |
| **Hardware & EDA** | `KiCad` `LTspice` `FreeCAD` `Discrete TTL Logic (50+ ICs)` |
| **Languages & Systems** | `Python` `C/C++` `MATLAB` `Bash` |

---

<details>
<summary>📚 <strong>Academic Archives & Coursework Portfolio</strong></summary>

<br />

* **[solar-pv-system-design](https://github.com/IamOumarIbrahim/solar-pv-system-design)** — Commercial solar PV system simulation using NREL SAM.
* **[adaptive-noise-cancellation-dsp](https://github.com/IamOumarIbrahim/adaptive-noise-cancellation-dsp)** — MATLAB NLMS adaptive noise cancellation (+5.14 dB SNR boost).
* **[am-modulation-demodulation-matlab](https://github.com/IamOumarIbrahim/am-modulation-demodulation-matlab)** — Transceiver simulation with coherent demodulation and 5th-order Butterworth LPF.
* **[ttl-vending-machine](https://github.com/IamOumarIbrahim/ttl-vending-machine)** — Discrete 50+ TTL IC hardware vending machine designed from scratch.

</details>

---

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-10B981?style=flat-square" alt="MIT License" />
</p>
