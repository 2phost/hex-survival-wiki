# Mechanism: [[mechanisms/verification_list|Verification List]] (Required Testing)

These are the confirmed mechanics and remaining "known unknowns" based on the latest available data.

## 1. Confirmed Mechanics
- **AP Costs**: 1 AP/hex movement. **0 AP** for scavenging/skills/inventory actions.
- **Skill Timings**: Real-time training (Lvl 1=1h, Lvl 2=24h, Lvl 3=7d, Lvl 4=14d, Lvl 5=30d).
- **Light Radius**: Both Power Poles and Lamps illuminate only the **current tile (0-radius)**.
- **Biome Loot Weights**: Confirmed exact weights for all items in all biomes.
- **Crafting Recipes**: Exact costs and skill locks confirmed for all functional equipment and infrastructure.
- **Salvage Yields**: Exact primary and rare bonus yield probabilities confirmed for all scavengeable items.
- **Base Constructions**: Exact resource requirements and names confirmed from content pack.
- **Vitals Restoration**: Exact numerical effects for all consumables confirmed.
- **Stim Conditioning**: Tier locks confirmed for Stim Pack/Injector/Overdrive.
- **Generator Operations**: Tier locks confirmed for Gas/Biofuel/Plasma fuels.
- **Facility Production**: Skill requirements for components (Lvl 1 Alloy, Lvl 2 Logic/Hydraulic, Lvl 3 Signal). One unit produced per Midnight transition if facility is active.
- **Item/Biome Directories**: Exact item properties (Rarity, Category, Consumable Stats, Power Refills) fully audited. Migrated all relative weights to **Absolute Success Probabilities (% per hour)** based on the server roll logic (45/25/5/25). Biome weight tables are now sorted DESC and exclude zero-weight entries.
- **Detailed Item Usage**: Confirmed specific crafting and construction roles for all materials (e.g., Car Battery for Battery Storage, Copper Wiring for Solar Panels).
- **Visual Assets**: Standardized all image embeds to Quartz Wikilink format (![[...]]) with uniform scaling (150px-300px). Embedded high-resolution icons for all items and biome tiles.
- **Table Optimization**: Standardized HTML-based icons (20px) with `vertical-align: middle` across all crafting and deconstruction tables for perfect text alignment.
- **Internal Wiki Structure**: Successfully migrated all legacy links to the new `biomes/` and `items/` directory structures. Fixed broken infrastructure links in base documentation and resized icons for readability.
- **Midnight Cycle**: Confirmed 40% drain for Hunger and Thirst at Midnight.
- **Fear System**: Confirmed Fear accumulation in darkness and recovery while resting in light.
- **Relative Tracking**: Objective navigation data is relative to the player's current position.
- **Player Scoring**: First iteration of scoring (calculated on death) is active.
- **Town Tracking**: Initial support for persistent town statistics is active.
- **Refueling**: Confirmed "Refuel" button appears in the Base menu when fuel is in the Town Bank (requires Generator Operations).
- **Expansion Ideas**: Created 4 new suggestion files ([[ideas/new_items|Items]], [[ideas/new_skills|Skills]], [[ideas/new_constructions|Constructions]], [[ideas/new_combinations|Combinations]]) to track future development goals.

## 2. Vitals & The "[[mechanisms/midnight_cycle|Midnight]] Toll"
- **Hourly Drain**: (Testing) Confirm if Hunger/Thirst drains at a fixed hourly rate *in addition* to the 40% Midnight Toll.
- **Restoration Timing**: (Testing) Are Well/Hydroponic resources added *before* or *after* the hunger/thirst check at Midnight?
- **Siege Breaches**: (Testing) Confirm exact consequences of a breach (e.g., is it -10% Town Power per enemy?).
- **Vitals Scaling**: (Testing) Does the 40% drain scale with town level or number of players?

## 3. Advanced Mechanisms & Map
- **Beacon Amp Logic**: (Testing) Quantify the "improvement in movement efficiency" in darkness (e.g., is it -0.5 AP cost per hex?).
- **Facility Production**: (Testing) Confirm if multiple players at the same facility can increase production rate.
- **Map Size**: (Testing) Is the world finite or procedurally infinite?
- **Visual Range**: (Testing) Can players see the biome type of adjacent tiles without moving?
- **Power Pole Connectivity**: (Testing) Confirm if poles *must* be connected to the base grid or if isolated "mini-grids" are possible.
