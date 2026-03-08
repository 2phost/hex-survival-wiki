---
title: "Action Points (AP)"
---

# Vital: [[Vitals/action_points|Action Points]] (AP)

## Description
**Action Points (AP)** are the primary currency for performing specific tasks on the map. It is displayed as one of the four main status bars.

## Usage
- **Disabling Threats**: Specific quest actions (e.g., disabling a Corrupted Relay) require a set amount of AP (e.g., 2 AP).
- **Movement**: Consumes **1 AP per hex**. This cost is uniform across all tile types.
- **[[Mechanisms/scavenging_logic|Scavenging]]**: Does **not** consume AP over time; starting and stopping the activity is also free (0 AP).
- **Inventory & [[Skills/index|Skills]]**: Opening the inventory, consuming items, or starting/pausing a skill consumes **0 AP**.
- **Restoration**: 
    - **Passive Regeneration**: While the player is in the **Resting** state (not scavenging), they restore **1 AP every hour** of real time.
    - **Skill Bonus**: The **[[Skills/rest_recovery|Rest Recovery]]** skill provides a chance to gain an additional +1 AP during this hourly window.
    - **Consumables**: 
        - **Stimulants**: Restored by **[[Items/stim_pack|Stim Packs]]** (+2 AP), **[[Items/stim_injector|Stim Injectors]]** (+4 AP), and **[[Items/stim_overdrive|Stim Overdrive]]** (+6 AP).
        - **Food & Water**: **Rations, Water, Salad, and Glowing Mushrooms** now restore **+1 AP** upon consumption.
- **AP Cap**: Any AP gained that exceeds the current maximum capacity (increased via **[[Skills/ap_capacity|AP Capacity]]**) is permanently lost.
