---
title: "Midnight Cycle"
---

# Mechanism: [[Mechanisms/midnight_cycle|Midnight Cycle]]

The **[[Mechanisms/midnight_cycle|Midnight Cycle]]** is the game's primary heartbeat. At exactly midnight, the server processes all global changes, resets specific player stats, and calculates the town's survival.

## 1. The Survival Toll
The most critical part of the cycle is the survival check.
- **[[Vitals/hunger|Hunger]] Drain**: Every player loses **40% (4 bars)** of their hunger.
- **[[Vitals/thirst|Thirst]] Drain**: Every player loses **40% (4 bars)** of their thirst.

## 2. Monster Activity
The darkness becomes active at midnight:
- **Horde Spawning**: Corrupted tiles may spawn new monster hordes.
- **Horde Progression**: Marching hordes move **one hex closer** to the town base.
- **World Damage**: Hordes consume ground loot and destroy **[[Items/power_pole|Power Poles]]** on tiles they enter.
- **Horde Gathering**: Newly spawned hordes spend one night in place before marching.

## 3. Town Siege & Defense
The final check of the night is the town's security:
- **Attack Calculation**: All hordes on the base tile contribute to the total **Attack Strength**.
- **Defense Check**: If **Attack Strength > Town Defense**, the town is overrun and the game instance ends for all players.

## 4. Production & Logistics
- **Facility Yields**: Resources from the **[[Base/constructions|Well]]** and **[[Base/constructions|Hydroponic Patch]]** are added to the Town Bank.
- **[[Mechanisms/facility_fabrication|Fabrication Completion]]**: Any items currently being fabricated on specific tiles (like Industrial or Electronics) are produced and placed on the ground at that tile.
- **Power Drain**: Daily town power drain is deducted from the generator.

## 5. Global Scaling
- **Spawn Bonus**: The global monster spawn bonus increases every night, ensuring that newly spawned hordes are larger and more dangerous over time.
