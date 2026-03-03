# Mechanism: [[mechanisms/scavenging|Scavenging]] and Loot Tables

## Scavenging Logic
- **Action**: Searching costs Action Points (AP).
- **Success Rate**: Base success rates are improved by the **[[mechanisms/skills|Scavenger's Eye]]** skill (+5% per level).
- **Biome Specifics**: Loot is heavily dependent on the tile type.

## Biome Loot Weights
The following table represents the relative rarity/weight of finding specific items in each biome. Higher numbers indicate a higher chance.

| Item | Desert | Forest | Ruined City | Mountain | Industrial | Lab | Farm | Vault | Oasis |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Rations** | 2 | 8 | 20 | 1 | 6 | 0 | 90 | 2 | 4 |
| **Clean Water** | 10 | 40 | 15 | 10 | 5 | 0 | 35 | 10 | 90 |
| **Salad** | 0 | 8 | 2 | 0 | 1 | 0 | 45 | 0 | 8 |
| **Stim Pack** | 6 | 8 | 14 | 4 | 10 | 6 | 4 | 3 | 2 |
| **Scrap Metal** | 18 | 5 | 85 | 10 | 60 | 20 | 22 | 10 | 0 |
| **Raw Timber** | 20 | 80 | 15 | 10 | 5 | 0 | 25 | 0 | 10 |
| **Stone** | 70 | 10 | 15 | 90 | 25 | 0 | 14 | 15 | 5 |
| **Copper Wiring** | 5 | 5 | 30 | 10 | 45 | 40 | 18 | 20 | 0 |
| **Circuit Boards**| 0 | 0 | 8 | 0 | 12 | 75 | 0 | 25 | 0 |
| **Chemical Sludge**| 0 | 0 | 5 | 0 | 70 | 15 | 0 | 20 | 0 |
| **Battery** | 10 | 10 | 5 | 0 | 30 | 60 | 12 | 10 | 0 |
| **Car Battery** | 12 | 4 | 40 | 3 | 35 | 8 | 6 | 4 | 0 |
| **Research Mat.** | 0 | 0 | 6 | 0 | 18 | 70 | 0 | 35 | 0 |
| **Ancient Relic** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 100 | 0 |
| **Gasoline Gen** | 0 | 0 | 6 | 0 | 12 | 10 | 0 | 16 | 0 |
| **Gasoline Can.** | 10 | 0 | 20 | 10 | 30 | 0 | 0 | 20 | 0 |
| **Lamp (empty)** | 5 | 10 | 45 | 5 | 40 | 20 | 18 | 15 | 0 |
| **Old Bottle** | 20 | 25 | 45 | 15 | 40 | 10 | 26 | 5 | 20 |
| **Glowing Mush.** | 8 | 55 | 18 | 20 | 14 | 16 | 0 | 45 | 35 |

## Specialized Tile Properties
- **[[Hidden Vault]]**: Guaranteed **Ancient Relic** (Weight 100).
- **Electronic Lab**: Best source for **Circuit Boards**, **Batteries**, and **Research Material**.
- **Industrial Zone**: Best source for **Chemical Sludge**, **Scrap Metal**, and **Fuel**.
- **Farm Facility**: Primary source of **Rations** and **Salad**.
- **Oasis**: Primary source of **Clean Water**.
- **Desert/Mountain**: Primary source of **Stone**.
- **Forest**: Primary source of **Timber**.
