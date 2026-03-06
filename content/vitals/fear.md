# Mechanism: [[mechanisms/fear|Fear]]

![[assets/overlays/fear.png|300]]


## Overview
Fear is a psychological status system added on March 5, 2026. it tracks the mental strain of exploring the darkness.

## Accumulation & Recovery
- **Darkness Increase**: Entering dark tiles (no [[mechanisms/infrastructure|Power Pole]] or Base light) without an active [[mechanisms/items|Lamp]] increases Fear.
- **Safe Recovery**: Fear decreases over time when the player is **Resting** on a lit tile.

## Penalties
Fear imposes significant penalties on player efficiency:
- **[[mechanisms/scavenging|Scavenging]] (Search)**: -10% success chance per Fear point (added to the base darkness penalty).
- **[[mechanisms/skills|Skill Checks]]**: -5% success chance per Fear point for all non-search skill checks.

## Panic State
Exceeding **Fear Max** triggers a panic-loss condition. (Exact mechanics are currently being verified; see [[mechanisms/inferred_mechanics|Inferred Mechanics]] for theories).

## Technical Details
- **HUD**: Features a segmented Fear bar and a high-risk visual pulse near the limit.
- **Persistence**: `fear_current` and `fear_max` are persisted in player data across sessions.
- **Sync**: Fear levels are included in movement acknowledgements and state synchronization.
