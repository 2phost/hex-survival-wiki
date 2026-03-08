---
title: "Facility Fabrication"
---

# Mechanism: [[Mechanisms/facility_fabrication|Facility Fabrication]]

## Overview
**Fabrication** is a specialized on-tile action that allows players to produce specific items at advanced facilities. Unlike [[Mechanisms/scavenging_logic|Scavenging]], which is probabilistic and immediate, Fabrication is guaranteed but requires a full daily cycle to complete.

## The Fabrication Cycle
1. **Start Project**: A player must physically stand on a facility tile and select the **Fabricate** action.
2. **Select Product**: Choose an item from the available list based on the facility type and your skill level.
3. **Midnight Completion**: The item is processed throughout the day. At **[[Mechanisms/midnight_cycle|Midnight]]**, the fabrication finishes.
4. **Retrieve Item**: The completed item appears **on the ground** at the facility tile. It is not automatically banked.

## Fabrication Locations & Products

### [[Biomes/farm_facility|Human Farm Facility]]
- **Skill Required**: None.
- **Products**: 
    - <img src="../assets/items/rations.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[Items/rations|Rations]]
    - <img src="../assets/items/salad.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[Items/salad|Salad]]

### [[Biomes/industrial|Industrial Zone]]
- **Skill Required**: **[[Skills/field_engineering|Field Engineering]]**.
- **Products**:
    - <img src="../assets/items/alloy_plate.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[Items/alloy_plate|Alloy Plate]] (Requires Lvl 1)
    - <img src="../assets/items/hydraulic_piston.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[Items/hydraulic_piston|Hydraulic Piston]] (Requires Lvl 2)

### [[Biomes/electronic_lab|Electronic Store - Lab]]
- **Skill Required**: **[[Skills/field_engineering|Field Engineering]]**.
- **Products**:
    - <img src="../assets/items/logic_core.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[Items/logic_core|Logic Core]] (Requires Lvl 2)
    - <img src="../assets/items/signal_emitter.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[Items/signal_emitter|Signal Emitter]] (Requires Lvl 3)

## Operational Rules
- **One Per Tile**: Only one fabrication project can be active on a single hex at any given time.
- **Global Concurrent Production**: A town can have multiple fabrications active simultaneously across the map.
- **AP Cost**: Starting a fabrication costs **0 AP**.
- **Power Cost**: Each active fabrication project increases the town's **daily power drain by 20%** until it completes at Midnight.
- **Persistence**: Projects persist through the Midnight cycle as long as the town has power. **Note**: If town power reaches **0%**, the current town session ends.
