# Mechanism: Scavenging Logic

**Scavenging** is the primary method for gathering resources from the wasteland.

## 1. The Search Action
- **AP Cost**: **0 Action Points**. Starting and stopping scavenging is free.
- **Hourly Intervals**: While scavenging, the server performs a loot check every hour of real time.
- **AP Recovery**: Passive AP regeneration is **paused** while scavenging. To recover AP, you must be in the **Resting** state.

## 2. Success Rates
Your chance of finding an item is influenced by:
- **[[skills/scavenger_eye|Scavenger's Eye]]**: Increases base success chance by +5% per level.
- **Darkness Penalty**: Searching in dark tiles (unlit by Base or Poles) suffers a massive penalty.
- **[[vitals/fear|Fear]] Penalty**: Each point of Fear reduces search success by **-10%**.
- **Corrupted Relays**: Active relays on the map can impose a town-wide search penalty.

## 3. Loot Distribution
Loot is determined by the **[[biomes/index|Biome]]** of the current tile.
- **Weights**: Each biome has a unique probability table for items.
- **Item Details**: For a full list of all discoverable items and their properties, see the **[[items/index|Item Directory]]**.
- **Biome Specifics**: To see exactly what each tile type yields, see the **[[biomes/index|Biome Index]]**.
