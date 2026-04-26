# Quest Design Document: Wraith of The Savior

## 1. Project Overview
* **Title:** Wraith of The Savior
* **Format:** Interactive Fiction / Narrative RPG
* **Theme:** Deception, mutation, and the mirrors of monstrosity.

## 2. Narrative Summary
In a settlement gripped by silence and fear, a Witcher investigates the "Wraith of Zorandor," a legendary ancestor said to be haunting Baron Dearg’s estate. However, the investigation reveals a darker truth: the Baron has been experimenting on sentient monsters to achieve power, and the "wraith" is actually a vengeful Doppler seeking justice for its murdered kin. The player must decide whether to protect a corrupt human, aid a grieving monster, or walk away from the chaos entirely.

## 3. Design Philosophy
This quest focuses on **Investigation-led Revelation** and **Subverting Tropes**:
* **The Twist:** What begins as a standard ghost hunt shifts into a moral conflict involving a Doppler and a mutated Baron.
* **The Mirror:** The Witcher is forced to confront the Baron’s view that Witchers and mutated humans are functionally the same.
* **Moral Ambiguity:** Players must weigh the Doppler’s murder of an innocent caretaker against the Baron’s systemic torture of monsters.

## 4. Scene Structure & Logic
The quest is organized by the following node structure as defined in the technical script:

| Scene ID | Narrative Role | Key Outcome |
| :--- | :--- | :--- |
| **Intro** | The Hook | Player finds the contract or enters the silent settlement. |
| **Scene 3-5** | Gathering Intel | Interrogating the Innkeeper via Orens or AXII to learn of Zorandor. |
| **Scene 6-9** | Estate Entry | Convincing guards and the "Caretaker" to grant access to the graveyard. |
| **Scene 11-14**| The Crypt | Discovering the real Caretaker's body and the missing ancestral sword. |
| **Scene 15-16**| The Confrontation| Rushing to the manor to find the Doppler confronting the Baron. |
| **Scene 17-22**| The Resolution | Siding with the Baron, the Doppler, or remaining neutral. |

## 5. Branching Logic Map
* **Path A (Pro-Order):** Kill the Doppler. Receive a reward and a mutation formula from the Baron.
* **Path B (Pro-Justice):** Assist the Doppler in killing the Baron. The Doppler assumes the Baron's identity.
* **Path C (Neutral):** Refuse to choose between "two evils". The Doppler kills the Baron while the Witcher walks away.

## 6. Project Links
* **[🕹️ Play Interactive Version](https://m-wahap-elmali.github.io/quest_design_portfolio/Quest%20Designs/Wraith%20of%20The%20Savior/)**
* **[📄 Read The Full Narrative Script](./SCRIPT.md)**
* **[📊 Logic Flowchart](./logic_flow.png)**

---
* **Developed as a portfolio piece for narrative design, originally created for TTRPG.**
* **Created by [M-Wahap-ELMALI]*