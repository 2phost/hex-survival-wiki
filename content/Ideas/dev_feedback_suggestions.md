---
title: "Game Development Suggestions (Tester Feedback)"
---

# Ideas: Game Development Suggestions (Tester Feedback)

These suggestions are intended for the developers to improve the player experience, balance the survival loop, and solve emerging issues.

## 1. Quality of Life (QoL) & UI
- **Map Pinging System**: In a collaborative game, players need to "ping" a hex (e.g., "Found Oasis here" or "Need Power Pole here"). A simple alt-click on a tile could broadcast a coordinate to the town chat.
- **Drone Recovery**: Allow for a low chance to recover a "Crashed Drone" item from the base tile after a launch, which can be repaired for less scrap than crafting a new one.
- **Action Queueing**: For repetitive tasks like scavenging or "Resting," allow players to queue up a certain amount of [[Vitals/action_points|AP]]/time so they don't have to click "Start" repeatedly.

## 2. [[Base/index|Infrastructure]] & Base Building
- **Circular Battery Economy**: Instead of **Batteries** disappearing after use, allow the **[[Biomes/electronic_lab|Electronic Store - Lab]]** to have a "Charging Station." 
- **Remote Fabrication**: Add a late-game upgrade to the **[[Base/constructions#ResearchLab|Research Lab]]** that allows players to start **[[Mechanisms/facility_fabrication|Fabrication]]** projects remotely from the Base menu, provided the target facility is powered.
- **Defense Maintenance**: Introduce a "Repair" action for base defenses that have been damaged during a siege, requiring a fraction of the original build materials.

## 3. Light & Darkness Refinement
- **Flares/Glowsticks**: A cheap, one-time use item that provides light to a single hex for 5-10 minutes. Useful for "scouting" ahead before committing a permanent Power Pole.
- **Fear Resistance Items**: Add a "Calming Herbal Tea" (crafted from Oasis plants) or "Weighted Vest" (crafted from Scrap) that slows the rate of Fear accumulation in the dark.

## 4. Resource Production (Fabrication)
- **Fabrication Scaling**: Allow the town to build "Production Arrays" at facility tiles. This would allow for **two** concurrent fabrication projects on a single hex, at the cost of a higher power drain (e.g., +40% total).
- **Automated Retrieval**: A high-tier base upgrade that automatically moves fabricated items from the facility floor to the **[[Base/management|Town Bank]]** at Midnight.

## 5. Backpack & Inventory
- **Backpack Customization**: Allow players to "Socket" items into backpacks, such as a "Lamp Clip" that prevents the lamp from taking an inventory slot while providing light.
- **Tiered Scrap Yields**: Larger backpacks should yield more scrap or fabric when deconstructed, reflecting their higher crafting costs.

## 6. Implemented / Improved Features
The following suggestions have been addressed in recent patches:
- **Base Upgrade Readability (Implemented Mar 12)**: Improved spacing, scrolling, and effect descriptions in the upgrade menu.
- **Monster Map Clarity (Implemented Mar 12)**: Increased marker size and prevented overlap with player icons.
- **Cargo Drone Logistics (Implemented Mar 12)**: Introduced autonomous field-to-base transfers.
- **Backpack Tiers (Implemented Mar 12)**: Added craftable gear to expand inventory capacity.
- **Fear System (Implemented Mar 5)**: Instead of instant death in darkness, the **[[Vitals/fear|Fear]]** vital now tracks strain.
- **Item Overlay/Overflow (Improved Mar 6)**: Visual handling for large piles of items on a single hex has been optimized.
