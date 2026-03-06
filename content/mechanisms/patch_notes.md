# Mechanism: [[mechanisms/patch_notes|Patch Notes]]

This page tracks the official updates and changes to Hex Survival.

## Friday, Mar 6, 2026

- **Town Tracking**: Added initial town tracking support for persistent statistics.
- **Player Scoring**: First iteration of player scoring active; currently calculates upon death.
- **UI & UX Upgrades**:
    - Improved handling for overflowing tile icons to reduce visual clutter.
    - Upgraded inventory and base management UI for better usability.
    - Adjusted town resource UI to display more items simultaneously.
    - Fixed inventory click-through behavior.
    - Fixed base panel item tooltips while moving the pointer.
- **Suggestions Panel**: Added a right-hand backlog column and fixed backlog status persistence.
- **Chat System**: Fixed town chat to automatically open on the latest message.
- **Technical Fixes**:
    - Corrected player reload handling to use persisted row fields.
    - Reused existing binoculars icon asset; removed duplicate binary icon.
    - Hidden expedition debug input layer outside development builds.

## Thursday, Mar 5, 2026

- Added the **[[mechanisms/fear|Fear System]]** to track psychological strain in darkness.
- Introduced Fear accumulation in dark tiles and recovery on lit tiles.
- Added penalties to scavenging and skill checks based on Fear levels.
