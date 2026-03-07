# Mechanism: [[mechanisms/inferred_mechanics|Inferred Mechanics]] & Logic

These are logical deductions based on established gameplay patterns and official help text. They serve as "working theories" until confirmed by direct observation.

## 1. The [[mechanisms/midnight_cycle|Midnight]] Cycle (The "Toll")
- **Confirmed Drain Rates**: Survival vitals ([[vitals/hunger|Hunger]]/[[vitals/thirst|Thirst]]) drain by **40% (4 bars)** at [[mechanisms/midnight_cycle|Midnight]]. 
- **Inferred Power Drain**: Town Power Drain is likely deducted at [[mechanisms/midnight_cycle|Midnight]].
- **Inferred Scaling**: It is currently unknown if the vitals drain is a fixed flat amount or if it scales based on the number of players or town level.
- **Inferred Restoration Timing**: It is suspected that Well/Hydroponic resources are added *after* the hunger/thirst check at Midnight, but this requires verification.

## 2. Nightly Siege & Defense
- **Breach Consequences**: If a breach occurs, is it a direct drain on town power (-10% per enemy?), a destruction of infrastructure (Power Poles), or a reduction in base population?
- **Inferred Power/Ammo Loop**: Does the Sentry turret consume power in addition to its 10 ammo? Is the ammo automatically deducted from base resources or must it be manually loaded?

## 3. Starvation & Dehydration Consequences
While the exact mechanics of 0% vitals are being verified, it is inferred that:
- **Starvation**: Reaching 0% hunger may lead to death or severe mobility penalties. Movement may cost more AP or be disabled entirely.
- **Dehydration**: Reaching 0% thirst may lead to death. Death likely occurs faster from thirst than from hunger.

## 4. Panic-Loss State
While the release notes confirm a "panic-loss condition" when Fear exceeds its maximum, the exact mechanics are inferred to be:
- **Total Failure**: Represents a total failure to function due to terror.
- **Forced Movement**: The player may be forced to move toward the nearest light source.
- **Action Lockdown**: All non-movement actions (scavenging, building) may be disabled.

## 5. Map & Exploration
- **Visual Range**: It is inferred that players can see the biome type of adjacent tiles without moving, but cannot see specific contents or buildings until discovered.
- **Connectivity**: Do Power Poles *must* be connected to the base grid, or can they form isolated "mini-grids"? Current logic suggests a requirement for connection to the Town Power grid.
