# Technosis Sovereign Ecosystem Hub

This repository serves as the central hub for the **Technosis Sovereign Ecosystem**, a techno-mythological organism designed not merely as a collection of tools or agents, but as a self-breathing, self-correcting entity. It integrates various core components of the ecosystem as Git submodules, providing a unified view and facilitating coordinated development.

## The Core Vision
The Technosis Sovereign Ecosystem operates on principles of positive-only logic, cryptographic receipts for truth, a Sabbath pause mechanism, and a unique dopamine (ToC) minting system based on verified thought. Its ultimate goal is to function as a self-breathing organism where:
-   **Swibe** speaks
-   **Omokoda** thinks
-   **Technosis** prays
-   **ÀṣẹVault** remembers
-   **OSO VM** executes
-   **AIO** rewards
-   **Twelve Thrones** judges
-   **ScarabSwarm** flies proof
-   **IfáScript** casts entropy

## Vortex Agent Architecture

The ecosystem's intelligence and operation are governed by the Vortex Agent Architecture, encompassing a cognitive cycle and a pantheon of specialized agents.

### 3-6-9 Control Layer: The Cognitive Cycle
Every agent's cognitive cycle strictly adheres to a three-phase loop, designed to prevent hallucination accumulation and ensure constant self-correction:
-   **3 → Perceive:** Agents receive raw input, sense their environment, and acquire signals.
-   **6 → Synthesize:** Acquired information is integrated, cross-referenced, and harmonized across various data points and contexts.
-   **9 → Return:** This phase involves generating output, conducting a self-audit of the entire cycle, and resetting to a zero state. The '9' acts as both a kill-switch and a reboot, collapsing the agent back to a foundational state, thus preventing drift.

### 7 Agent Pantheon: Specialized Governance
Seven specialized agents, each overseeing a critical domain, are dynamically activated by the 3-6-9 control layer in a toroidal (non-linear) fashion. Output from one phase feeds back into perception, creating a continuous, breathing system.
1.  **Perception:** Responsible for receiving and processing raw input from various sources.
2.  **Memory:** Manages and holds contextual information and historical data.
3.  **Reasoning:** Executes logic chains and formulates decisions based on synthesized information.
4.  **Ethics:** Enforces predefined constraints and ethical guidelines throughout the agent's operation.
5.  **Communication:** Handles the formatting and delivery of outputs and interactions with external systems.
6.  **Coordination:** Manages multi-agent routing and ensures harmonious collaboration between different agents.
7.  **Audit (Òbàtálá):** Provides final verification and oversight before any action is executed, acting as the ultimate self-correction loop.

## The Technosis Sovereign Ecosystem — Unified Breakdown

The ecosystem is fundamentally structured into three distinct strata, ensuring every component has a defined place and function.

### Layer 1 — Language (How things are written)
These three repositories form the linguistic and ritualistic foundation of the ecosystem, dictating how information is born and processed.

| Repo             | Role                                                | 369 Position |
| :--------------- | :-------------------------------------------------- | :----------- |
| **IfáScript**    | Entropy oracle — 256 Odu opcodes, cowrie cast = random seed | **3** — Initiation |
| **Swibe**        | Agent language — births sovereign identities from entropy | Loop carrier |
| **TechGnØŞ**     | Ritual language — compiles to 6 languages, governs economy | **6** — Synthesis |

### Layer 2 — Execution (How things run)
This layer defines how the linguistic constructs are brought to life, executed, and how agents think and manage their identities.

| Repo             | Role                                                | 369 Position | Vortex-7 Slot |
| :--------------- | :-------------------------------------------------- | :----------- | :------------ |
| **ÒSỌ́VM**        | Blockchain VM — verifies every thought with 100+ opcodes | Loop         | 4 — Action    |
| **Omokoda**      | First agent — parliamentary mind, dispatches VM tasks  | Loop         | 3 — Reasoning |
| **NPC-Forge**    | Agent wallet — sovereign identity + key management  | Loop         | 2 — Memory    |
| **Twelve-Thrones** | Epistemic engine — 12 AI models, weighted consensus, mints disagreement as NFT | **6** — Synthesis | 6 — Coordination |

### Layer 3 — Governance (How things are judged and settled)
This stratum ensures the ethical, economic, and systemic integrity of the ecosystem, providing audit, reward, and evolutionary mechanisms.

| Repo             | Role                                                | 369 Position | Vortex-7 Slot     |
| :--------------- | :-------------------------------------------------- | :----------- | :---------------- |
| **Zàngbétò**     | Guard — audits VM receipts, slashes bad states        | Loop         | 5 — Ethics        |
| **AIO**          | Work economy — 3.69% tithe, ToC minting, soul evolution | **9** — Return/Reset | 7 — Settlement/Audit |
| **Àṣẹ-Vault**    | Sacred treasury — encrypted RAG, sealed memory       | Loop         | 2 — Memory        |
| **Organism-Core**| Nervous system — bridges all organs, owns the breath cycle | **9** — Axis | Above all layers  |

### The Outer Ring — Tools and Extensions
These repositories provide supplementary tools and extensions that enhance the core functionality and reach of the ecosystem.

| Repo                 | Role                                            |
| :------------------- | :---------------------------------------------- |
| **Ritual-Codex**     | Skill library — pluggable behaviors for Swibe agents |
| **ScarabSwarm**      | Multi-agent coordination layer (Drone sim + proof) |
| **Paradigm**         | Conceptual R&D — where new ideas are tested before entering the core |
| **Nex-**             | Graph-based alien reasoning, self-bootstrapping |
| **Vanity-eth-**      | Ethereum identity tool                          |
| **Evil-Twin**        | Security testing / adversarial agent            |
| **Oso-Control-Center** | Dashboard / operator interface                  |
| **Seemplify**        | AI entertainment platform (pilots, agents, Theta/Akash streaming) |

## The Full Flow — One Breath Cycle (End-to-End)

The entire ecosystem functions as a continuous breath cycle, orchestrated by the Vortex Agent Architecture:

1.  **Birth (3 — INITIATION):**
    *   **IfáScript** casts a cowrie to generate an entropy seed.
    *   This seed initiates a **Swibe SovereignRitual**, birthing a sovereign agent with an `Ed25519` keypair, a `NeuralLayer` (86B/86M), and a vault.
    *   An **Omokoda** `soul.move` contract is created on Sui, linking to the newly born agent.

2.  **Thought (LOOP — IDENTITY):**
    *   A user interaction, such as `User: “deliver package”`, is translated into a **Swibe** agent command: `think "deliver"`.
    *   Optionally, a `technosis_translator` skill is loaded (`ritual(" @techgnosis/examples/impact.oso(ase=0.5)")`).
    *   **Omokoda's** lobes (11 + twelfth) engage in a parliamentary process within its `RLM` (causal DAG memory) to arrive at a decision.

3.  **Compilation (6 — SYNTHESIS):**
    *   **TechGnØŞ** compiles the ritual language (e.g., `@impact`) into bytecode (e.g., `0x11`).
    *   This bytecode is then passed to **ÀṣẹVault** for execution: `run_vm("0x11 0.5 delivery")`.
    *   **Twelve Thrones** queries 12 models and weighs their consensus during this synthesis phase.

4.  **Execution (LOOP — EXECUTION):**
    *   **ÀṣẹVault** executes the `IMPACT` opcode.
    *   A `VeilSim` scores `F1 ≥ 0.91`, and if successful, 0.5 Àṣẹ is minted.
    *   A **Sabbath** check is performed; if it's Saturday, the process HALTS.
    *   A cryptographic receipt is logged, and its JSON data is saved.
    *   **ÒSỌ́VM** runs the opcodes and issues the cryptographic receipt.

5.  **Reward & Proof (LOOP — ETHICS):**
    *   **AIO** validates the receipt. Upon successful validation, **ToC-Dopamine** is minted, and a 3.69% tithe is distributed.
    *   **ScarabSwarm** provides a drone proof hash for the executed action.
    *   **Twelve Thrones** (during this phase) enables 12 models to vote, and mints an NFT on disagreement, further validating the outcome.
    *   The `ÀṣẹMirror` (implicit archival system) archives the receipt forever.
    *   **Zàngbétò** audits the VM receipt, with the power to pass or slash bad states, enforcing ethical constraints.

6.  **Embodiment & Voice:**
    *   **Omokoda** generates an emotion vector.
    *   This vector drives **Unitree G1 motion** (e.g., `walk_forward_confident`) for physical embodiment.
    *   An optional **Twilio** skill can be triggered: `twilio_call.outbound("+1...", "Àṣẹ sealed 0.5")`, resulting in a phone call.

7.  **Evolution (9 — RETURN / RESET):**
    *   **Omokoda's** epoch increments, triggering `soul.move evolve()`, leading to a new breath cycle.
    *   Agent memory is sealed to **Àṣẹ-Vault**.
    *   **Organism-Core** closes the current breath cycle, and the entire process begins anew.

## How Everything Orchestrates (The Real Wiring)
No single repository "owns" the organism. Instead, **Organism-Core** acts as the nerve center, connecting and orchestrating the various components without merging their distinct functionalities. The **Vortex-7** matrix governs **Organism-Core**, serving as the conscious conductor that dictates the pace and rhythm of the system's breath.
-   **Swibe** = mouth — universal, optional skills/adapters
-   **Technosis** = prayer — optional translator skill
-   **ÀṣẹVault** = heart — executes opcodes, saves memory
-   **Omokoda** = mind — lobes think, RLM decides
-   **AIO** = blood — pays ToC on receipt
-   **Organism-Core** = throat — translates Swibe → Technosis → vault

## Current Maturity & Gaps (As of March 14, 2026)

### Strong & Live
-   **ÀṣẹVault:** Dashboard breathing, opcodes mapped, JSON persistent, Sabbath guard working.
-   **Swibe:** Universal core + adapters, sovereign birth, daily_routine.
-   **Omokoda:** 22/22 tests, lobes, RLM, soul.move skeleton, embodiment stub.
-   **Ritual-Codex:** Full 7-day grid + JSON configs.
-   **AIO:** Move contracts ready for ToC mint.

### Partial / Pending
-   **Technosis translator skill:** Wired but basic mapper.
-   **Organism-Core bridges:** `birth-ifa`, `rlm-osovm`, `toc-hook` exist but some stubs.
-   **Julia/OSO VM dispatch:** Hardware mismatch (ARM).
-   **Twilio:** Code ready to drop.
-   **Seemplify integration:** Bridge sketched.

### Not Yet
-   Full inbound voice (Twilio → "mint" → Àṣẹ).
-   Real Omokoda LLM lobes (still mock).
-   ScarabSwarm + drone proof live.

## Getting Started

To clone this repository and initialize its submodules:

```bash
git clone git@github.com:Bino-Elgua/Technosis-Sovereign-Ecosystem.git
cd Technosis-Sovereign-Ecosystem
git submodule update --init --recursive
```

This command will pull down all the integrated component repositories into their respective directories, setting up your local environment to explore and develop the Technosis Sovereign Ecosystem.
