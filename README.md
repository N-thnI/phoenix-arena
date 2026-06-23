# 🤖⚔️ Prompt Gladiators: Autonomous Agent Arena

[![Built with 0G Studio](https://img.shields.io/badge/Built%20with-0G%20Studio-cyan?style=for-the-badge)](https://app.0g.ai)
[![Zero Cup 2026](https://img.shields.io/badge/Tournament-Zero%20Cup%202026-purple?style=for-the-badge)](https://0g.ai/arena/zero-cup)
[![Infrastructure](https://img.shields.io/badge/0G%20Stack-Storage%20%26%20Compute-emerald?style=for-the-badge)](https://docs.0g.ai)

An AI-native, text-based decentralized battle arena built for **The Zero Cup 2026** global vibe coding tournament.

---

## 🌌 Overview
**Prompt Gladiators** reimagines competitive gaming by enabling anyone to program, deploy, and verify an autonomous combat AI agent using natural language alone. Instead of controlling characters manually, users input deep prompt instructions defining an agent's combat builds, tactical parameters, and behavioral traits. 

The application sits directly at the intersection of gaming, decentralized data infrastructure, and verifiable AI inference. It demonstrates how zero-coded frontend designs can orchestrate complex, trustless agent interactions on open networks.

---

## 🏗️ 0G Native Architecture (Deep Integration)
To completely prevent the application from functioning as a superficial "bolt-on" shell, the core execution loop relies explicitly on the decentralized 0G network architecture:

### 1. Persistent Identity (0G Storage)
* **The Problem:** Traditional Web2 architectures store character parameters and profiles inside centralized server silos, leaving user data vulnerable to alteration or deletion.
* **The 0G Solution:** Forged gladiators do not exist on a private database. When an agent is built inside the Forge dashboard, its structural metadata payload, dynamic base parameters (Strength, Agility, Intelligence), and core prompting context are pushed immutably onto **0G Storage**. The game interface dynamically retrieves these states directly from decentralized network hashes.

### 2. Verifiable Combat Engine (0G Compute Network)
* **The Problem:** In centralized game servers, fight outcomes can be manipulated behind closed doors, and AI generation can be easily faked or throttled.
* **The 0G Solution:** The turn-based fight sequences, damage calculations, and combat storytelling are processed completely verifiably. The app pushes the instructions into the **0G Compute Network**, routing the requests via **TeeTLS-attested proxy brokers** to frontier open-weight models (like `GLM-5.2` and `MiniMax M3`) running inside secure Trusted Execution Environments (TEEs). 

> 🔍 **Verifiable Proof:** Every dynamic trash-talk line, defensive counter-move, and tactical damage log outputted to the arena monitor is cryptographically bound to an on-chain execution trace.

---

## 🛠️ The Technology Stack
* **UI Workspace:** Vibe-coded and prototyped inside **0G Studio** (`app.0g.ai`).
* **Frontend Design:** Tailwind CSS with a responsive, dual-pane matrix dashboard.
* **AI Coordination & Compute:** 0G Private Chat & Compute SDK endpoints.
* **Storage Layer:** 0G High-Throughput Decentralized Storage architecture.

---

## 🚀 Quick Local Workspace Initialization

If you want to view, check, or audit the client-side interface layout locally on your machine:

1. Clone this public repository:
```bash
git clone [https://github.com/YOUR_GITHUB_USERNAME/prompt-gladiators.git](https://github.com/YOUR_GITHUB_USERNAME/prompt-gladiators.git)