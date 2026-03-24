---
title: "Multiplayer & Death"
---

# Mechanism: [[Mechanisms/multiplayer_and_death|Multiplayer & Death]]

## Multiplayer (Collaborative)
Hex Survival is a collaborative game where players work together within a shared "Town."

| You | Other Survivors |
| :---: | :---: |
| ![[assets/players/scavanger.png|150]] | ![[assets/players/scavanger_other.png|150]] |

- **Shared Environment**: Multiple players inhabit the same town simultaneously.
- **Resource Management**: Base stores (Rations, Water, Power) are shared or impact the town-wide survival state.
- **Town Tracking**: Initial support for tracking town-wide progress and statistics across sessions.

## Death and Respawn
- **Causes of Death**: 
 - **Darkness (Fear)**: Spending too much time in unlit areas without a light source. When the **[[Vitals/fear|Fear]]** meter reaches its maximum, the player enters **Fear Paralysis** and cannot move until light is found.
 - **Vitals**: Starvation or dehydration (to be confirmed).
- **Player Scoring**: A first iteration of player scoring is active, with scores currently calculated upon death.
- **Town Cycle**: Upon death, players do not necessarily restart the same instance.
- **Joining New Towns**: After dying, the player joins a different town populated by other active survivors.
- **Permanent Progression**: While a specific town run may end, "[[Skills/index|Skills]]" are permanent and carry over between towns.
