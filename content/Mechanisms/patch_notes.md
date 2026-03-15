---
title: "Patch Notes"
---

# [[Mechanisms/patch_notes|Patch Notes]]

## Sunday, Mar 15, 2026: Game Architecture & Town Reporting
* **GameScene Refactor**: Large-scale modularization of scene logic (init, update, player state, day cycle, etc.) for better maintainability.
* **Enhanced UI Orchestration**: Improved ownership and management of inventory, town-fallen, and base-upgrade overlays.
* **Reliable Town-Fall Reporting**: Hardened server-side reporting to prevent duplicate announcements and ensure town-fall death summaries are explicitly posted in town chat.

---

## Saturday, Mar 14, 2026: Shared Intel & Communication
* **Eidetic Memory & Visibility**: Reworked the visibility model with the **[[Skills/eidetic_memory|Eidetic Memory]]** skill. Exploration information is now shared, day-scoped, and features Lit, Remembered, and Dark tile states.
* **Town Forums**: Added persisted threads and replies for long-term coordination within towns.
* **Communication UX**: 
 * **Item/Tile Chat Linking**: Players can now link specific items or tiles directly in the chat.
 * **Clickable Tile References**: Clicking a tile link in chat centers the map on that location.
* **Inventory Workflow Updates**: 
 * **Recipe Book View**: Centralized interface for managing crafting and viewing combinations.
 * **Smoother Logistics**: Relocated deposit, deliver, and drop-all actions for better town management.
* **Power Stability**: Resolved issues where poles could disappear silently and fixed cable rendering between connected nodes.

---

## Friday, Mar 13, 2026: Grid Expansion & Monster Tracking
* **Reinforced Power Pole (MK2)**: Introduced the **[[Items/power_pole_mk2|Reinforced Power Pole]]** with extended 3-tile range and adjacent-tile illumination.
* **Power Infrastructure Skill**: Added the **[[Skills/power_infrastructure|Power Infrastructure]]** skill to gate advanced grid operations.
 * **Level 1**: Placing basic power poles.
 * **Level 2**: Dismantling existing poles.
 * **Level 3**: Placing Reinforced (MK2) poles.
* **Midnight Horde Reporting**: Total monster spawn counts are now automatically announced in the town chat every midnight.

---

## Thursday, Mar 12, 2026: Logistics & Defense Update
* **Cargo Drone Logistics**: Introduced autonomous courier drones for field-to-base transfers. Requires **[[Skills/drone_operator|Drone Operator Lvl 2]]**.
* **Backpack Tiers**: Rare craftable backpacks added to expand inventory beyond base capacity.
 * **[[Items/salvager_pack|Salvager Pack]]** (+2 slots)
 * **[[Items/expedition_pack|Expedition Pack]]** (+3 slots)
 * **[[Items/hauler_pack|Hauler Pack]]** (+4 slots)
* **Base Defense Overhaul**: Massive expansion to town perimeter defenses with 10 new sequential builds.
* **UI/UX Improvements**:
 * Enhanced Base Upgrade menu with better spacing, scrolling, and build-effect descriptions.
 * Monster markers on the map are now larger, render more reliably, and no longer overlap with player icons.

---

## Monday, Mar 09, 2026: Monster Siege Update
* **Monster Horde System**: **[[Biomes/corrupted_1|Corrupted Tiles]]** now act as active spawning grounds for organized monster hordes.
 * **Horde Life Cycle**: Hordes spawn at Midnight, spend one night **Gathering**, and then begin **Marching** (1 hex per night) directly toward the town.
 * **Environmental Damage**: Advancing hordes consume all ground loot and destroy any **[[Items/power_pole|Power Poles]]** in their path, severing loot highways.
 * **Escalation**: A global **Spawn Bonus** increases nightly, ensuring the threat grows in intensity over time.
* **Corrupted Relays**: Introduction of relay nodes that, if left corrupted, impose a severe **town-wide search penalty**. Disabling them requires 2 AP and coordinated effort.
* **Town Sieges**: Active defense is now mandatory. If a horde reaches the base, its strength is tested against the town's built defenses at Midnight.
* **Combat Skill Tree**: New specializations added: **[[Skills/weapon_maintenance|Weapon Maintenance]]**, **[[Skills/sweeping_strikes|Sweeping Strikes]]**, and **[[Skills/critical_hits|Critical Hits]]**.
* **Weaponized Items**: Industrial items like **[[Items/alloy_plate|Alloy Plates]]** and **[[Items/rusty_tool|Rusty Tools]]** can now be used as improvised weapons with unique damage and break stats.

---
