---
title: "Game Development Suggestions (Tester Feedback)"
---

# Ideas: Game Development Suggestions (Tester Feedback)

These suggestions are intended for the developers to improve the player experience, balance the survival loop, and solve emerging issues.

## 1. Quality of Life (QoL) & UI
- **Map Pinging System**: In a collaborative game, players need to "ping" a hex (e.g., "Found Oasis here" or "Need Power Pole here"). A simple alt-click on a tile could broadcast a coordinate to the town chat.
- **Stim Buff Tracking**: With the addition of high-tier **[[Items/stim_injector|Stim Injectors]]** and **[[Items/stim_overdrive|Stim Overdrive]]**, a clear status icon should show the remaining duration of any active buffs and the "Conditioning" level required to use them.
- **Action Queueing**: For repetitive tasks like scavenging or "Resting," allow players to queue up a certain amount of [[Vitals/action_points|AP]]/time so they don't have to click "Start" repeatedly. This shifts the "Meta" from mechanical persistence to strategic forecasting.

## 2. [[Base/index|Infrastructure]] & Base Building
- **Circular Battery Economy**: Instead of **Batteries** disappearing after use, allow the **[[Biomes/electronic_lab|Electronic Store - Lab]]** to have a "Charging Station." 
    - **Mechanism**: When a lamp expires, it drops an **"Empty Battery"** item. Players carry these to the Lab to "Refuel" them using town Power.
- **Advanced Research Visualization**: The **[[Base/upgrades|Research Lab II]]** (+20% speed) should provide a clear progress bar for the second research slot to help the town coordinate long-term projects.
- **Remote Grid Monitoring**: An upgrade to the Base menu that allows players to see exactly which facilities (Farm, Industrial, Lab) are currently active and drawing the **+20% Power Load**, helping the town "load balance" their power usage.
- **Remote Fabrication**: Add a late-game upgrade to the **[[Base/upgrades|Research Lab]]** that allows players to start **[[Mechanisms/facility_fabrication|Fabrication]]** projects remotely from the Base menu, provided the target facility is powered.

## 3. Light & Darkness Refinement
- **Flares/Glowsticks**: A cheap, one-time use item that provides light to a single hex for 5-10 minutes. Useful for "scouting" ahead before committing a permanent Power Pole.
- **Fear Resistance Items**: Add a "Calming Herbal Tea" (crafted from Oasis plants) or "Weighted Vest" (crafted from Scrap) that slows the rate of Fear accumulation in the dark.

## 4. Resource Production (Fabrication)
- **Fabrication Scaling**: Allow the town to build "Production Arrays" at facility tiles. This would allow for **two** concurrent fabrication projects on a single hex, at the cost of a higher power drain (e.g., +40% total).
- **Automated Retrieval**: A high-tier base upgrade that automatically moves fabricated items from the facility floor to the **[[Base/management|Town Bank]]** at Midnight.

## 5. Implemented / Improved Features
The following suggestions have been addressed in recent patches:
- **Fear System (Implemented Mar 5)**: Instead of instant death in darkness, the **[[Vitals/fear|Fear]]** vital now tracks strain, leading to death only when the 3-bar limit is reached.
- **Item Overlay/Overflow (Improved Mar 6)**: Visual handling for large piles of items on a single hex has been optimized to reduce visual clutter.

## 6. Reported Technical Issues (Bug-Suggestions)
The following issues have been identified by testers and are being tracked through the suggestions feature for developer review.

### Item Overlay/Overflow (Improved Mar 6)
- **Description**: When too many items are dropped on a single hex, the visual representation of those items begins to overlay or bleed into adjacent tiles.
- **Patch Note (Mar 6, 2026)**: Improved handling for overflowing tile icons to reduce visual clutter.
- **Symptoms**: Visual clutter in high-activity areas (like the Base or popular scavenging spots); difficulty clicking on or interacting with the underlying tile or other items due to visual overlap.
- **Tester Recommendation**: Implement a "Stacked Item" UI where multiple items on one tile are represented by a single icon with a counter (e.g., "x5 Items").
