# Mechanism: [[mechanisms/facility_fabrication|Facility Fabrication]]

## Overview
**Fabrication** is a specialized on-tile action that allows players to produce specific items at advanced facilities. Unlike [[mechanisms/scavenging_logic|Scavenging]], which is probabilistic and immediate, Fabrication is guaranteed but requires a full daily cycle to complete.

## The Fabrication Cycle
1. **Start Project**: A player must physically stand on a facility tile and select the **Fabricate** action.
2. **Select Product**: Choose an item from the available list based on the facility type and your skill level.
3. **Midnight Completion**: The item is processed throughout the day. At **[[mechanisms/midnight_cycle|Midnight]]**, the fabrication finishes.
4. **Retrieve Item**: The completed item appears **on the ground** at the facility tile. It is not automatically banked.

## Fabrication Locations & Products

### [[biomes/farm_facility|Human Farm Facility]]
- **Skill Required**: None.
- **Products**: 
    - <img src="../assets/items/rations.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[items/rations|Rations]]
    - <img src="../assets/items/salad.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[items/salad|Salad]]

### [[biomes/industrial|Industrial Zone]]
- **Skill Required**: **[[skills/field_engineering|Field Engineering]]**.
- **Products**:
    - <img src="../assets/items/alloy_plate.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[items/alloy_plate|Alloy Plate]] (Requires Lvl 1)
    - <img src="../assets/items/hydraulic_piston.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[items/hydraulic_piston|Hydraulic Piston]] (Requires Lvl 2)

### [[biomes/electronic_lab|Electronic Store - Lab]]
- **Skill Required**: **[[skills/field_engineering|Field Engineering]]**.
- **Products**:
    - <img src="../assets/items/logic_core.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[items/logic_core|Logic Core]] (Requires Lvl 2)
    - <img src="../assets/items/signal_emitter.png" width="20" style="vertical-align: middle; margin-right: 4px;"> [[items/signal_emitter|Signal Emitter]] (Requires Lvl 3)

## Operational Rules
- **One Per Tile**: Only one fabrication project can be active on a single hex at any given time.
- **Global Concurrent Production**: A town can have multiple fabrications active simultaneously across the map (e.g., one player starting Alloy in the Industrial Zone and another starting Rations at the Farm).
- **AP Cost**: Starting a fabrication costs **0 AP**.
- **Persistence**: Projects persist through the Midnight cycle as long as the town has power. **Note**: If town power reaches **0%**, the current town session ends.
