# Mechanism: [[mechanisms/player_status|Player Status]] and Vitals

## Vitals
The player must manage several primary status bars to survive:
1. **Hunger**: Replenished by food/rations.
2. **Thirst**: Replenished by fresh drinking water.
3. **Health**: Managed by finding **Medicine** and recovery items.
4. **[[mechanisms/action_points|Action Points]] ([[mechanisms/action_points|AP]])**: Currency for performing active tasks on the map.
5. **Activity Status**: Displays current state (Resting, [[mechanisms/scavenging|Scavenging]]).

## Activity Types
- **Resting**: The default state when not performing other tasks. Restores **1 [[mechanisms/action_points|AP]] per hour**.
- **[[mechanisms/scavenging|Scavenging]]**: The act of searching a hex for resources. 
    - **[[mechanisms/action_points|AP]] Cost**: **0 [[mechanisms/action_points|AP]] to start or stop.** The activity itself does **not** drain [[mechanisms/action_points|AP]] over time.
    - **Recovery**: [[mechanisms/action_points|AP]] regeneration is **paused** while scavenging; you cannot rest and scavenge simultaneously.
    - **Loot**: [[mechanisms/items|Items]] are discovered at hourly intervals based on a percentage roll.
