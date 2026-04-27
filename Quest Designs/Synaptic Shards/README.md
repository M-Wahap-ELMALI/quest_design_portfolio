# Quest Design Document: Synaptic Shards

## 1. Project Overview
* **Title:** Synaptic Shards
* **Format:** Interactive Fiction / Cyberpunk Narrative RPG
* **Theme:** Neuro-technological decay, the price of loyalty, and the fragmentation of memory.

## 2. Narrative Summary
The story begins in a rain-slicked Kabuki dive bar. The protagonist, Kael, must reunite a fractured specialist crew for a high-stakes vault extraction. To locate them, Kael first meets Eddie, an informant whose mind is "glitched" due to severe neural damage. After retrieving high-grade **Chronos-V** from a Scavenger nest to "re-sync" Eddie’s memories, Kael receives the coordinates for his team. The mission then shifts into a series of recruitment "loyalty loops": rescuing Mick from a neuro-torture chair, extracting Slim from a garbage shaft, and settling corporate debts for Iron Pete.

## 3. Design Philosophy
This quest focuses on **Multi-Objective Exploration** and **Pragmatic Resource Management**:
* **The "Math vs. Mercy" Mechanic:** Kael’s philosophy is "math, not mercy." Every recruitment choice involves a trade-off between spending Eddies (currency), risking combat, or abandoning "dead weight" assets.
* **Environment as a Narrative Tool:** Each location (the Flooded District, the North Oak shaft, the Badlands bar) reflects the decay and specialized skills of the crew member found there.
* **Consequence-Driven Assembly:** The final crew composition at the safehouse depends entirely on player choices—deciding who is worth saving and who is expendable.

## 4. Scene Structure & Logic
The quest is organized by the following node structure as defined in the technical script:

| Scene ID | Narrative Role | Key Outcome |
| :--- | :--- | :--- |
| **SCENE 1-3** | **The Hook** | Secure Chronos-V and unlock Eddie’s scrambled coordinates. |
| **SCENE 4** | **The Deceiver** | Rescue Mick from the Moxes (Payment, Combat, or Technical Bluff). |
| **SCENE 5** | **The Weight** | Extract Slim from the trash shaft or leave him as "dead weight." |
| **SCENE 6** | **The Tools** | Unseal Iron Pete’s workshop by hacking corporate tax servers. |
| **SCENE 7** | **The Muscle** | Recruit the twins (Jax & Dax) via an arm-wrestling QTE or bribery. |
| **SCENE 8** | **The Assembly** | Final briefing at the safehouse and initiating the vault heist. |

## 5. Branching Logic Map
[📊 Logic Flowchart (Image)](./logic_flow.png)

## 6. Major Endings & Variations
* **The Perfect Run:** All four specialists are functional; the vault heist proceeds with maximum support.
* **The Broken Band:** Key members are missing or injured; the final encounter with the security AI becomes significantly more difficult.
* **The Professional:** Kael pays all debts (~16,000 Eddies), resulting in a loyal but costly crew.

## 7. Project Links
* **[🕹️ Play Interactive Version (abridged version)](https://m-wahap-elmali.github.io/quest_design_portfolio/Quest%20Designs/Synaptic%20Shards/)**
* **[📄 Download Full Narrative Script (PDF)](./Synaptic%20Shards.pdf)**
* **[📄 Read Full Narrative Script (Markdown)](./SCRIPT.md)**
* **[📊 Logic Flowchart (Image)](./logic_flow.png)**

---
* **originally created for TTRPG session, adapted into a Cyberpunk Narrative Script.**
* **Created by [M-Wahap-ELMALI]**