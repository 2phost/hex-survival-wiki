---
title: "Patch Notes"
---

# Mechanism: [[Mechanisms/patch_notes|Patch Notes]]

Official updates and changelogs for Hex Survival.

## Monday, Mar 9, 2026: The Siege Update
- **New Monster Horde System**: Corrupted tiles now spawn monster hordes at midnight.
- **Horde Phases**: Fresh hordes spend one night **Gathering**, then start **Marching** one hex toward town each midnight.
- **Global Escalation**: The global spawn bonus increases every night, causing newly spawned hordes to grow larger if left unchecked.
- **World Destruction**: Hordes now consume ground loot and destroy built **[[Items/power_pole|Power Poles]]** when advancing into a tile.
- **Town Siege**: At midnight, any horde reaching the base contributes its count to **Attack Strength**. If Attack Strength is greater than Town Defense, the town is overrun.
- **Combat Mechanics**: Added **Attack Monsters** action. Weapon damage converts to kills; weapons can break during combat. Full details in **[[Mechanisms/combat_and_defense|Combat & Defense]]**.
- **Defensive Strategy**: Clear corrupted zones early and build defensive base upgrades (Barbed Wire, Bulkheads, Sentry) to increase Town Defense.
- **UI Support**: Monster markers now display stacked counts per hex and phase information (Gathering vs. Marching).
- **New Combat Skills**: Added **[[Skills/weapon_maintenance|Weapon Maintenance]]**, **[[Skills/sweeping_strikes|Sweeping Strikes]]**, and **[[Skills/critical_hits|Critical Hits]]**.
- **New Item**: Added **[[Items/restored_binoculars|Restored Binoculars]]** (Reveal adjacent biomes while moving).

## Friday, Mar 6, 2026: Tactical & UI Refinement
- **Town Tracking**: Added initial support for tracking town-wide statistics and progress.
- **Player Scoring**: Added first iteration of scoring that calculates upon player death.
- **UI Upgrades**: 
    - Improved handling for overflowing tile icons to reduce visual clutter.
    - Upgraded inventory and base management UI layouts.
    - Adjusted town resource UI to display a wider range of items.
    - Added a right-hand backlog column in the suggestions panel.
    - Fixed base panel item tooltips to remain stable while moving the pointer.
- **Chat Improvements**: Fixed town chat to automatically open on the latest message.
- **Persistence & Reloads**: Corrected player reload handling to use persisted row fields.
- **Asset Cleanup**: Reused the existing binoculars icon asset for restored binoculars and removed duplicate binary icons.
- **Backend**: Hidden the expedition debug input layer outside development builds.

## Thursday, Mar 5, 2026: The Fear Update
- **Fear System**: Added a new psychological vital. Exploring dark tiles increases Fear.
- **Fear Death**: Reaching **3 bars** of Fear results in death ("Consumed by darkness").
- **Recovery**: Fear recovers while resting on lit tiles.
- **HUD Update**: Added Fear meter and high-risk visual pulsing.

## Wednesday, Mar 4, 2026: Infrastructure Update
- **Bank-based Refueling**: The "Refuel" button now appears in the Base menu if fuel is in the Town Bank.
- **Power Pole Connectivity**: Confirmed poles light their tile and carry power from the grid.
- **Item Deconstruction**: Added salvage yields for all materials.
