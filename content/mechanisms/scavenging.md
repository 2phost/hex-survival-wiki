# Mechanism: [[mechanisms/scavenging|Scavenging]]

## Description
[[mechanisms/scavenging|Scavenging]] is the primary method of resource gathering in Hex Survival. Each zone on the map is represented as a hexagon.

## Rules
- **Hexagonal Zones**: Every zone is a hexagon that can be interacted with for scavenging.
- **Base Restriction**: **[[Tile: Base|Scavenging is impossible in the Base.]]** The Base is a safe zone for management and storage, not resource gathering.
- **Activity Status**: [[mechanisms/scavenging|Scavenging]] is tracked as an active state in the player's status bar, distinguishing it from other states like "Resting".
- **Toggle [[mechanisms/scavenging|Scavenging]]**: Players can start and stop the scavenging process at any time, as many times as they want. **This action is free and consumes 0 [[mechanisms/action_points|AP]].**
- **Resource Depletion**: Zones have a limited resource pool. After a certain number of searches, a zone will become depleted.
## Loot Timing
[[mechanisms/scavenging|Scavenging]] is a persistent, time-based activity rather than a single click.
- **Hourly Checks**: While the scavenging state is active, the game performs a loot "roll" every hour of real time.
- **Probability**: There is a set probability of an item "dropping" (appearing on the ground or in the inventory) at each hourly interval.
- **Skill Synergy**: The **Scavenger's Eye** skill (+5% loot chance per level) directly improves this hourly roll.

## Biome Loot Tables (Primary Drops)
The probability of finding specific items varies significantly based on the tile's biome:

| Resource | Best Biome | Prob. | Other Biomes |
| :--- | :--- | :--- | :--- |
| **Clean Water** | **Oasis** | 90% | Forest (40%), Farm Facility (35%) |
| **Rations** | **Farm Facility** | 90% | Ruined City (20%), Forest (8%) |
| **Timber** | **Forest** | 80% | Farm Facility (25%), Desert (20%) |
| **Scrap Metal** | **Ruined City** | 85% | Industrial (60%), Electronic Lab (20%) |
| **Stone** | **Mountain** | 90% | Desert (70%), Industrial (25%) |
| **Circuit Boards** | **Electronic Lab** | 75% | Hidden Vault (25%), Industrial (12%) |
| **Chemical Sludge**| **Industrial** | 70% | Hidden Vault (20%), Electronic Lab (15%) |
| **Research Mat.** | **Electronic Lab** | 70% | Hidden Vault (35%), Industrial (18%) |
| **Battery** | **Electronic Lab** | 60% | Industrial (30%), Farm Facility (12%) |
| **Ancient Relic** | **Hidden Vault** | 100% | (Only found in Vaults) |

## Notes
- The ability to start and stop scavenging suggests a time-based or progress-based system that persists even when interrupted.
- Depletion mechanics likely force players to move and explore new hexes.
- **Electronic Labs** and **Industrial Zones** are the primary hubs for advanced tech materials.
- **Farm Facilities** and **Oases** are critical for survival vitals (Food/Water).
