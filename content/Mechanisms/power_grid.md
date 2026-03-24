---
title: "Power Grid"
---

# Mechanism: [[Mechanisms/power_grid|Power Grid]]

The Power Grid is the network of light and energy that keeps the town alive.

## [[Items/power_pole|Power Poles]]
### Basic Power Pole
- **Function**: Places a relay pole on your current tile.
- **Requirement**: 1 Copper Wiring, scrap metal.
- **Light Range**: A powered pole illuminates only the **current tile (0-hex radius)**.
- **Connection Range**: Up to 2 tiles.

### Reinforced Power Pole (MK2)
- **Function**: Advanced relay pole with superior coverage.
- **Extended Range**: Can connect to other poles up to **3 tiles** away.
- **Superior Illumination**: Illuminates its **own tile PLUS all 6 adjacent tiles** (1-hex radius).

## Skill Requirements
The following levels in the **[[Skills/power_infrastructure|Power Infrastructure]]** skill are required for grid management:
- **Placing Basic Power Poles**: Level 1
- **Removing Power Poles**: Level 2
- **Placing Reinforced Power Poles (MK2)**: Level 3

## Grid Maintenance
- **Industrial Support**: Powered poles adjacent to industrial tiles (Industrial, Electronic Store - Lab) allow those tiles to be powered for production.
- **Sustainability**: Expansion of the grid increases the total daily power drain. This must be offset by building **[[Base/constructions#SolarPanels|Solar Panels]]** or refueling via the **[[Skills/generator_operations|Generator Operations]]** skill.
- **Town Failure**: If the town's power level reaches **0%**, the town instance ends for all players.
