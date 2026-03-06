# Mechanism: [[mechanisms/verification_list|Verification List]] (Required Testing)

These are the confirmed mechanics and remaining "known unknowns" based on the latest available data.

## 1. Confirmed Mechanics
- **AP Costs**: 1 AP/hex movement. **0 AP** for scavenging/skills/inventory actions.
- **Skill Timings**: Real-time training (Lvl 1=1h, Lvl 2=24h, Lvl 3=7d, Lvl 4=14d, Lvl 5=30d).
- **[[mechanisms/light_and_darkness|Light Radius]]**: Both Power Poles and Lamps illuminate only the **current tile (0-radius)**.
- **Biome Loot Weights**: Confirmed exact weights for all items in all biomes.
- **Crafting Recipes**: Exact costs and skill locks confirmed for all functional equipment and infrastructure.
- **Salvage Yields**: Exact primary and rare bonus yield probabilities confirmed for all scavengeable items.
- **[[mechanisms/infrastructure|Base Constructions]]**: Exact resource requirements confirmed for all builds.
- **Vitals Restoration**: Exact numerical effects for all consumables confirmed.
- **Stim Conditioning**: Lvl 1/2/3 locks confirmed for Stim Pack/Injector/Overdrive.
- **Generator Operations**: Tier locks confirmed for Gas/Biofuel/Plasma fuels.
- **Facility Production**: Confirmed skill requirements for Alloy Plates (Lvl 1), Logic Cores (Lvl 2), Hydraulic Pistons (Lvl 2), and Signal Emitters (Lvl 3).
- **Signal Booster**: Confirmed effect: Reveals nearest High Value Loot hex every morning.
- **Scrap Workshop**: Confirmed effect: -25% AP cost for Searching within 1 hex of base.
- **Beacon Amp**: Confirmed effect: Improves movement efficiency in darkness.
- **Fuel Refinery**: Confirmed effect: Converts salvaged chemicals into stable generator fuel.
- **Research Lab II**: Confirmed effect: Unlocks second research slot and +20% research speed.
- **Midnight Vital Drain**: Confirmed 40% (4 out of 10 bars) drain for Hunger and Thirst at [[mechanisms/time_and_power|Midnight]].
- **Fear System**: Confirmed Fear accumulation in darkness, recovery while resting in light, and specific penalties (-10% search, -5% other skills).
- **Consumable AP**: Confirmed Rations, Water, Salad, and Glowing Mushrooms now restore 1 AP.
- **Objective Navigation**: Confirmed headings and distances are **relative to the player's current position**.
- **Hourly Regeneration**: Confirmed 1 AP/hour recovery while Resting.
- **Rapid Prototype Request**: Confirmed reward (+2 Research, +2 Scrap) for setting facility production.

## 2. Vitals & The "[[mechanisms/time_and_power|Midnight]] Toll"
- **Hourly Drain**: (Testing) Confirm if Hunger/Thirst drains at a fixed hourly rate *in addition* to the 40% Midnight Toll.
- **Restoration Timing**: Are Well/Hydroponic resources added *before* or *after* the hunger/thirst check at Midnight?
- **Siege Breaches**: Confirm exact consequences of a breach (e.g., is it -10% Town Power per enemy?).
- **Vitals Scaling**: Does the 40% drain scale with town level or number of players?

## 3. Advanced [[mechanisms/infrastructure|Infrastructure]] & Map
- **Beacon Amp Logic**: Quantify the "improvement in movement efficiency" in darkness (e.g., is it -0.5 AP cost per hex?).
- **Facility Production Costs**: Confirm the exact resource costs (e.g., Scrap Metal, Circuit Boards) and production time required to manufacture components at powered Industrial/Lab tiles.
- **Map Size**: Is the world finite or procedurally infinite?
- **Visual Range**: Can players see the biome type of adjacent tiles without moving?
- **Power Pole Connectivity**: Confirm if poles *must* be connected to the base grid or if isolated "mini-grids" are possible.
