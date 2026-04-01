# Agentic Context & Tool-Harness Reconstruction (v2.1.88-Study)

![License](https://img.shields.io/badge/License-Research%20Only-blue.svg) 
![Status](https://img.shields.io/badge/Build-Experimental-red.svg)
![Parity](https://img.shields.io/badge/Parity-Python%2FRust-orange.svg)

> **Core Thesis:** This repository serves as a technical case study into the orchestration logic of high-autonomy CLI agents. This is a **clean-room reconstruction** focused on the multi-language parity between high-speed Rust runtimes and flexible Python-based logic layers.

---

### Executive Summary

This project analyzes the "Think-Act-Observe" cycle used in modern agentic harnesses. By utilizing structural decomposition via the **oh-my-codex (OmX)** workflow, we aim to document the engineering constraints and optimization opportunities in autonomous developer tools.

### Key Architectural Domains Under Study

| Domain | Focus Area | Engineering Objective |
| :--- | :--- | :--- |
| **Tool Orchestration** | `Harness Logic` | Examining security-safe gating of system-level shell operations and granular permission models (Allow/Deny/Prompt). |
| **Context Management** | `Pruning & Compaction` | Analyzing session persistence and the three-layer context compression strategy to maintain long-horizon coherence. |
| **Performance Parity** | `Rust Core vs. Python Scaffold` | Auditing the latency trade-offs between a compiled CLI runtime (~4k lines of Rust) and a metadata scaffold (~1.5k lines of Python). |
| **State Engineering** | `Terminal UI (TUI)` | Observing methods for non-blocking UI state management and "Buddy" (UI-pet) state synchronization. |

### Provenance & Methodology

* **Reconstruction Framework:** Developed through the **oh-my-codex** architectural mapping process.
* **Core Credits:** Foundational engineering patterns and reconstruction effort spearheaded by **Sigrid Jin (@instructkr)**.

### Getting Started (Research Environment)

To replicate the study environment, ensure you have **Rust (cargo)** and **Python 3.10+** installed.

1. **Initialize Environment:**
   ```bash
   pip install -r requirements.txt
