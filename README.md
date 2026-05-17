# Jean-Benoit Pilon

**Head of IT · Enterprise Infrastructure · Autonomous Systems**

Greystones, Co. Wicklow, Ireland &nbsp;·&nbsp; [![LinkedIn](https://img.shields.io/badge/LinkedIn-jean--benoit--pilon-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/jean-benoit-pilon)

---

## Career Arc

```mermaid
flowchart LR
    EDU["Engineering Foundation<br/>──────────────<br/>BAC STI Électrotechnique<br/>BTS IRIS · Thales · AFTI"]
    BANK["Banking IT — Paris<br/>──────────────<br/>BNP Paribas · Natixis<br/>2012 – 2014"]
    MED["Medical IT<br/>──────────────<br/>Diagnostica STAGO<br/>2,200 users · 2014 – 2016"]
    HEAD["Head of IT<br/>──────────────<br/>TCOAG · Stago Group<br/>Bray, Ireland · 2016 – Present"]
    SYS["Autonomous Systems<br/>──────────────<br/>Python · AI Agents<br/>Orchestration Layers"]
    EDU --> BANK --> MED --> HEAD --> SYS
```

---

## Public Projects

### IoT & Device Control
- **[Roborock S5 → Valetudo](https://github.com/Stoneface30/roborock-s5-valetudo)** — Complete UART root + dual A/B partition flash to Valetudo 2026.02.0. 22× faster flashing via optimized block writes, zero cloud dependency, MQTT Home Assistant integration, custom GLaDOS voice pack. Full technical journey with blockers documented.

### AI & Automation
- **[StonyClaw Showcase](https://github.com/Stoneface30/stonyclaw-showcase)** — Live 30-agent AI system building a pixel-art kingdom in real-time. Watch it evolve at [showcase.conchita.uk](https://showcase.conchita.uk/showcase)

- **[Quake Legacy](https://github.com/Stoneface30/quake-legacy)** — AI-powered fragmovie production system for Quake Live. Demo parsing, pattern recognition, automated rendering pipeline.

---

## Sovereign OS — Personal AI Stack

> Local AI orchestration: Claude Code + Ollama + Qdrant + n8n + multi-agent crews. Everything runs on-prem. No cloud dependency.

<p align="center">
  <img src="assets/sovereign-os-demo-v6.gif" alt="Sovereign OS — live demo" width="100%">
</p>

---

## Private Systems & Infrastructure

I also maintain a range of private systems for personal infrastructure, experimentation, and autonomous decision-making:

**AI & Autonomous Systems**
- **Sovereign OS** — Personal AI operating layer on Claude Code — sequential Ollama review chain (qwen→gemma), 3-layer memory (Qdrant · RuFlo · Obsidian Vault), 163 active learning rules, pipeline status visible on every edit
- **Polymarket Bot** — Autonomous multi-engine prediction market system with capital allocation, verification gates, and fail-safe execution
- **Binance Bot** — Algorithmic crypto trading with multi-strategy execution and risk management
- **Pantry AI** — Household decision engine combining structured inventory data, meal planning, recipe sourcing, and real-time price intelligence

**Hardware & Home Automation**
- **GARDEN_CLAUDED** — Plant monitoring system with automated irrigation and sensor telemetry (Raspberry Pi, MQTT)
- **ESP32_CLAUDED** — Embedded systems lab with 3 experimental boards and custom firmware
- **Magic Mirror** — Embedded information display integrating Home Assistant, MQTT, and AI-curated feeds (Raspberry Pi)
- **MEDIA_HUB_CLAUDED** — Plex setup with Real-Debrid + Zurg + Riven for unified media consumption
- **NEST_CAM_CLAUDED** — De-Google Nest Cam Doorbell (local fallback + privacy layer)
- **SAMSUNG_TV_CLAUDED** — Samsung Q80T developer access & PCM audio investigation
- **Home Assistant** — Large-scale home automation platform with entity orchestration, presence logic, energy-aware control

**Systems & Documentation**
- **Finance App** — Local-first financial analysis system for transaction normalisation and multi-account tracking
- **email-intelligence** — Intelligent email processing and insights system
- **Repo-Work** — Engineering documentation and procedures for industrial system recovery projects
- **portfolio** — Professional portfolio system

> Private systems are not accessible. Descriptions reflect current architecture and purpose. All systems emphasize local-first, zero-cloud-dependency design.

---

## How I Work

Every development session runs through **Sovereign OS** — a wiring harness on top of Claude Code:

- Sequential Ollama review chain per edit: qwen2.5-coder:7b (code patterns) then gemma4:e4b (reasoning), each loaded → reviewed → unloaded. Cross-process lock keeps multi-tab sessions VRAM-safe. Gemini 2.5 Pro and Codex run in parallel alongside.
- Every hook event emits a visible status line — no silent failures, no flying blind on which reviewers fired
- Prompt primer injects project context, active constraints, and stack info before every response
- Three-layer memory (Qdrant semantic search · RuFlo HNSW · Obsidian Vault) keeps context across sessions
- n8n automates file-change ingestion, session saves, and PR notifications via Telegram

The practical result: full project context at session start, no repeated mistakes, automated review on every change.

---

## Stack

**Infrastructure & Operations**
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D6?style=flat-square&logo=microsoft&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![Azure AD](https://img.shields.io/badge/Azure_AD-0078D6?style=flat-square&logo=microsoftazure&logoColor=white)
![SCCM](https://img.shields.io/badge/SCCM-0078D4?style=flat-square&logo=microsoft&logoColor=white)

**Security & Networking**
![Cortex XDR](https://img.shields.io/badge/Cortex_XDR-FF6C37?style=flat-square&logo=paloaltonetworks&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![VPN](https://img.shields.io/badge/VPN%20%2F%20VLAN%20%2F%20NAC-555?style=flat-square)

**Python & Async Systems**
![Python](https://img.shields.io/badge/Python_3.14-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python&logoColor=white)

**Automation & AI**
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

**Embedded & Home Systems**
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home_Assistant-41BDF5?style=flat-square&logo=homeassistant&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

---

*14 years of enterprise IT across banking, medical diagnostics, and regulated environments.*
*Building autonomous systems at home, in Python, because the problems are worth solving.*
