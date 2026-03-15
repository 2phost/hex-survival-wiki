---
title: "Exploration Logic"
---

# Mechanism: Exploration Logic

Exploration is the high-risk process of uncovering the fog of war and identifying critical facilities.

## Visibility Model
The world is initially unknown, but visibility is now categorized into three distinct states:

- **Lit Tiles**: Fully visible and safe for movement. These are hexes illuminated by the **[[Base/overview|Base]]** or **[[Items/power_pole|Power Poles]]**.
- **Remembered Tiles**: Previously explored tiles that are currently unlit. They appear faintly in an expanding ring around the player. The radius of this ring is determined by the player's **[[Skills/eidetic_memory|Eidetic Memory]]** level.
- **Dark Tiles**: Unlit and unexplored (or unremembered) tiles. These are hidden by default and represent the true "Fog of War."

## Scouting Mechanics
- **Movement Cost**: Moving between hexes costs **1 [[Vitals/action_points|AP]]**.
- **Darkness Risk**: Moving into an unlit tile without a **[[Items/starter_lamp|Lamp]]** results in immediate death.
- **[[Vitals/fear|Fear]] Accumulation**: Exploration in darkness increases the player's Fear stat, imposing penalties on survival activities.
- **Shared Intelligence**: Exploration information is shared among all town members. However, this data is **day-scoped**, meaning the collective memory of the wasteland resets or shifts with the passage of time.

## Eidetic Memory
The **[[Skills/eidetic_memory|Eidetic Memory]]** skill allows players to retain a mental map of unlit areas they have previously visited. Higher levels of this skill increase the radius of "Remembered Tiles" visible around the player, reducing the need for constant re-exploration of established routes.

## Establishing Infrastructure
To explore deep into the wasteland, players must build **[[Items/power_pole|Power Pole]]** highways from the **[[Base/overview|Base]]** to create safe, lit corridors.
