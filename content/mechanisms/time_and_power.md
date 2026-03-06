# Mechanism: Time and Power

## Time System
Hex Survival operates on a real-time countdown.
- **Midnight Cycle**: A countdown (e.g., "Midnight in 7h38m") indicates the time remaining until the next day.
- **Midnight Transition**: Survival vitals ([[mechanisms/hunger|Hunger]]/[[mechanisms/thirst|Thirst]]) are deducted, and resource production (Well, Hydroponic Patch) is added at this point.

## The Nightly Siege
Midnight also triggers the **Nightly Siege**, a defensive phase for the town.
- **Threat Level**: Enemies attempt to breach the town's perimeter.
- **Defensive Structures**:
    - **[[mechanisms/infrastructure|Barbed Wire Perimeter]]**: Slows enemy movement by 1 hex; minor chip damage.
    - **[[mechanisms/infrastructure|Reinforced Steel Bulkhead]]**: Massive HP boost; small enemies cannot breach for 2 turns.
    - **[[mechanisms/infrastructure|Automated Sentry]]**: Fires at the nearest enemy. Requires **Ammo: 10/night**.

## Power System: The City's Lifeblood
Power is the most critical resource in Hex Survival. The city survives **only** while it has light.

- **Light & Survival Bar**: A percentage meter tracked in the **[[mechanisms/world_and_tiles|Base]]** menu. **At 0%, the town falls and the run is over.**
- **Night Use**: The town-wide power consumption for the Midnight transition.
- **Power Management**:
    - **[[mechanisms/infrastructure|Solar Panels]]**: Reduces daily drain by **10%**.
    - **[[mechanisms/infrastructure|Battery Storage]]**: Increases max power capacity by **+20%**.
    - **[[mechanisms/infrastructure|Beacon Amplifier]]**: Improves movement efficiency in darkness.

## Generator Fuels
Refills are handled via the **[[mechanisms/skills|Generator Operations]]** skill.

| Fuel Type | Power Refill | Requirement |
| :--- | :--- | :--- |
| **Gasoline Canister** | +25% | Gen. Ops Lvl 1 |
| **Biofuel Cell** | +40% | Gen. Ops Lvl 2 |
| **Plasma Fuel Rod** | +60% | Gen. Ops Lvl 3 |
