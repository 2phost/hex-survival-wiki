---
title: "Verification List"
---

# Mechanism: [[Mechanisms/verification_list|Verification List]] (Required Testing)

These are the confirmed mechanics and remaining "known unknowns" based on the latest available data.

## 1. Confirmed Mechanics
- **Monster Hordes**: Corrupted tiles spawn hordes; Gathering (1 night) -> Marching (1 hex/night toward town).
- **Siege Rules**: Town overrun if **Attack Strength > Town Defense**.
- **World Damage**: Hordes eat loot and destroy **[[Items/power_pole|Power Poles]]**.
- **Combat Mechanics**: Weapon damage converts directly to kills. Weapons have a break chance.
- **AP Costs**: 1 AP/hex movement. **0 AP** for scavenging/skills/inventory actions.
- **Fear System**: 3-bar max; death at 3/3 Fear. Accumulates in darkness; recovers in light.
- **Skill Timings**: Real-time training (Lvl 1=1h, Lvl 2=24h, Lvl 3=7d, Lvl 4=14d, Lvl 5=30d).
- **Light Radius**: Power Poles and Lamps illuminate only the **current tile (0-radius)**.
- **[[Mechanisms/facility_fabrication|Facility Fabrication]]**: Confirmed "Fabricate" action logic. Each active project = +20% town power drain.
- **Town Failure**: Town ends if power reaches **0%**.
- **Midnight Cycle**: 40% Hunger/Thirst drain at Midnight.
- **Refueling**: Refuel from Town Bank in the Base menu.
- **Binoculars**: **[[Items/restored_binoculars|Restored Binoculars]]** reveal adjacent biome types while moving.

## 2. Vitals & The "[[Mechanisms/midnight_cycle|Midnight]] Toll"
- **Attack Monsters AP**: (Testing) Does the "Attack Monsters" action cost AP?
- **Hourly Drain**: (Testing) Confirm if Hunger/Thirst drains at a fixed hourly rate *in addition* to the 40% Midnight Toll.
- **Restoration Timing**: (Testing) Are Well/Hydroponic resources added *before* or *after* the hunger/thirst check at Midnight?
- **Siege Penalties**: (Testing) If Attack Strength <= Town Defense, does the town still take "damage" (e.g., resource loss)?

## 3. Advanced Mechanisms & Map
- **Beacon Amp Logic**: (Testing) Quantify the "improvement in movement efficiency" in darkness (e.g., is it -0.5 AP cost per hex?).
- **Map Size**: (Testing) Is the world finite or procedurally infinite?
- **Power Pole Connectivity**: (Testing) Confirm if poles *must* be connected to the base grid or if isolated "mini-grids" are possible.
