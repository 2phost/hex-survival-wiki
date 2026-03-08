# Mechanism: [[mechanisms/fear|Fear]]

![[assets/overlays/fear.png|300]]


## Overview
Fear is a psychological status system added on March 5, 2026. it tracks the mental strain of exploring the darkness.

## Accumulation & Recovery
- **Darkness Increase**: Entering dark tiles (no [[items/power_pole|Power Pole]] or Base light) without an active [[items/starter_lamp|Lamp]] increases Fear.
- **Safe Recovery**: Fear decreases over time when the player is **Resting** on a lit tile.

## Penalties
Fear imposes significant penalties on player efficiency:
- **[[mechanisms/scavenging|Scavenging]] (Search)**: -10% success chance per Fear point (added to the base darkness penalty).
- **[[mechanisms/skills|Skill Checks]]**: -5% success chance per Fear point for all non-search skill checks.

## Fear Death
The Fear meter consists of **3 bars**.
- **Max Fear**: Reaching 3/3 Fear results in immediate death: **"Consumed by darkness."**
- **Mental Strain**: This represents the final collapse of the survivor's psyche when lost in the void without light.

## Technical Details
- **HUD**: Features a 3-segment Fear bar and a high-risk visual pulse near the limit.
- **Persistence**: `fear_current` and `fear_max` are persisted in player data across sessions.
- **Sync**: Fear levels are included in movement acknowledgements and state synchronization.
