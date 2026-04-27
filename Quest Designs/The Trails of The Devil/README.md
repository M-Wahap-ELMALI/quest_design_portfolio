# Quest Design Document: The Trails of The Devil

## 1. Project Overview
* **Title:** The Trails of the Devil
* **Format:** Interactive Fiction / Narrative RPG
* **Theme:** Ancient demonic resurgence, the cost of power, and the weight of wishes.

## 2. Narrative Summary
In a snow-lashed tavern, a Witcher is approached by a man named Erdesax with a dire warning: an ancient demon is about to be unleashed. To prevent this, the Witcher must retrieve the heart of a cursed Leshen and an ancient book from a forgotten, mirrored estate. However, the ritual atop the mountain reveals a grand deception: Erdesax is the entity himself, seeking to regain his "true form". The Witcher must decide whether to aid the ritual for a legendary reward or banish the ancient entity back to the void.

## 3. Design Philosophy
This quest focuses on **Multi-Objective Exploration** and **Subverting Expectations**:
* **The Bait and Switch:** The quest mimics a standard "stop the ritual" contract, only to reveal the quest-giver is the antagonist seeking his own freedom.
* **Environment as Puzzle:** The estate requires the player to manipulate light or use a teleportation stone to navigate through mirrors.
* **The "Monkey's Paw" Ending:** Even "positive" endings carry a dark physical or moral stain, emphasizing that dealing with demons always has a price.

## 4. Scene Structure & Logic
The quest is organized by the following node structure as defined in the technical script:

| Scene ID | Narrative Role | Key Outcome |
| :--- | :--- | :--- |
| **SCENE 1-3** | The Hook | Meeting Erdesax and negotiating the contract. |
| **SCENE 4** | The Hunt | Slaying a "half-human" Leshen to obtain its heart. |
| **SCENE 5** | The Investigation | Navigating the mirrored house to retrieve the Book of Old Priests. |
| **SCENE 6-9** | The Ascent | Traveling to the mountain peak and initiating the ritual. |
| **SCENE 10-11**| The Turning Point | Siding with Erdesax’s ascension or attempting to break the ritual. |
| **SCENE 12-14**| The Final Wish | Choosing between banishment, wealth, or the "Fate-Breaker" blade. |

## 5. Branching Logic Map
![Quest Branches](./logic_flow.png)

## 6. Four Different Endings
* **Path A (The Guardian):** Destroy the pillars to stop the ritual; Erdesax is pulled into the void.
* **Path B (The Betrayer):** Complete the ritual, then use the "one wish" to banish him back to hell forever.
* **Path C (The Mercenary):** Complete the ritual for the "Coins of Kovir", resulting in a permanent black stain.
* **Path D (The Dark Hunter):** Request a sword of "solidified darkness" called *Fate-Breaker*.

## 7. Project Links
* **[🕹️ Play Interactive Version](https://m-wahap-elmali.github.io/quest_design_portfolio/Quest%20Designs/The%20Trails%20of%20The%20Devil/)**
* **[📄 Download The Full Narrative Script](./The%20Trails%20of%20The%20Devil.pdf)**
* **[📄 Read The Full Narrative Script](./SCRIPT.md)**
* **[📊 Logic Flowchart](./logic_flow.png)**

---
* **Developed as a portfolio piece for narrative design, originally created for TTRPG.**
* **Created by [M-Wahap-ELMALI]**