> **Electrical & Computer Engineer** building open-source AI developer tooling, Model Context Protocol (MCP) integrations, and 6G / DSP signal processing research.

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C.svg?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![MCP Standard](https://img.shields.io/badge/MCP-1.0.0-purple.svg?style=flat-square)](https://modelcontextprotocol.io/)
[![KiCad](https://img.shields.io/badge/KiCad-10.0-3146B5.svg?style=flat-square)](https://kicad.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)

---

## ⚡ Flagship Open-Source Projects

### 🔌 [MCPntt](https://github.com/IamOumarIbrahim/MCPntt)
> **The Unified Model Context Protocol (MCP) Server for Desktop CAD, EDA & SPICE**

Connecting Claude Desktop, Antigravity, and AI agents directly to **KiCad**, **FreeCAD**, **LTspice**, and workspace files.

```json
// Add to claude_desktop_config.json
{
  "mcpServers": {
    "mcpntt": {
      "command": "uvx",
      "args": ["mcpntt"]
    }
  }
}
```
[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/MCPntt?style=social)](https://github.com/IamOumarIbrahim/MCPntt)

---

### 🖊️ [handrolled](https://github.com/IamOumarIbrahim/handrolled)
> **A Claude Skill that transforms AI slop into clean, procedural student-style code**

Strips away robotic comments, unnecessary function abstractions, and boilerplate, forcing Claude to write unrolled, explicit code.

```bash
# Install in 1 command
mkdir -p ~/.claude/skills && curl -o ~/.claude/skills/handrolled.md https://raw.githubusercontent.com/IamOumarIbrahim/handrolled/main/SKILL.md
```
[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/handrolled?style=social)](https://github.com/IamOumarIbrahim/handrolled)

---

### 🐍 [mamba-isac](https://github.com/IamOumarIbrahim/mamba-isac)
> **Selective State-Space Architecture for 6G OFDM ISAC Channel Estimation**

PyTorch benchmark framework evaluating Mamba (SSMs) vs. Transformers for joint channel and target parameter estimation in wireless communication.

```bash
git clone https://github.com/IamOumarIbrahim/mamba-isac.git && cd mamba-isac
pip install -r requirements.txt && python eval/evaluate_all.py
```
[![Stars](https://img.shields.io/github/stars/IamOumarIbrahim/mamba-isac?style=social)](https://github.com/IamOumarIbrahim/mamba-isac)

---

## 📡 Signal Processing & Hardware Systems

* 🥟 [**WokStation**](https://github.com/IamOumarIbrahim/WokStation): Windows TUI manager orchestrating local offline AI coding models (Qwen, Kimi, DeepSeek) via Ollama with prompt broadcasting and crash recovery.
* 📡 [**counter-uas-fmcw-radar**](https://github.com/IamOumarIbrahim/counter-uas-fmcw-radar): X-band FMCW radar pipeline simulation featuring 2D CA-CFAR detection, MVDR jammer nulling, and micro-Doppler STFT classification.

---

<details>
<summary>📚 <strong>Academic Archives & Coursework Portfolio</strong></summary>

<br />

* ☀️ [**solar-pv-system-design**](https://github.com/IamOumarIbrahim/solar-pv-system-design): Commercial solar PV system simulation using NREL SAM.
* 🔊 [**adaptive-noise-cancellation-dsp**](https://github.com/IamOumarIbrahim/adaptive-noise-cancellation-dsp): MATLAB NLMS adaptive noise cancellation (+5.14 dB SNR boost).
* 📻 [**am-modulation-demodulation-matlab**](https://github.com/IamOumarIbrahim/am-modulation-demodulation-matlab): Transceiver simulation with coherent demodulation and 5th-order Butterworth LPF.
* 🥤 [**ttl-vending-machine**](https://github.com/IamOumarIbrahim/ttl-vending-machine): Discrete 50+ TTL IC hardware vending machine built from scratch.

</details>
