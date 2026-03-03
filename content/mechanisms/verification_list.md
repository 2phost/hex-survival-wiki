# Mechanism: [[mechanisms/verification_list|Verification List]] (Required Testing)

These are the "known unknowns" that require testing to confirm how the game's internal logic works.

## 1. Confirmed Mechanics
- **Movement**: Consumes 1 [[mechanisms/action_points|AP]] per hex (uniform for all tiles).
- **[[mechanisms/skills|Skills]]**: 0 [[mechanisms/action_points|AP]] to start/pause. Can pause progress to switch research. Level 1 skills (like Stim Conditioning and [[mechanisms/action_points|AP]] Capacity) take 1 hour of real time. Level 2 skills ([[mechanisms/action_points|AP]] Capacity and Stim Conditioning) take 24 hours.
- **[[mechanisms/expedition_objectives|Expedition Objectives]]**: **[[Watchtower]]** reveals objective headings. Relays are hidden until the Watchtower is built.
- **Base Restrictions**: **Scavenging is impossible** in the Base hex.
- **Inventory**: 0 [[mechanisms/action_points|AP]] to drop, consume, or combine.
- **[[mechanisms/infrastructure|Infrastructure]]**: [[Power Poles]] only light their own hex (1-tile range). Must be placed adjacent to a lit tile.
- **Activities**: Starting/stopping scavenging is free (0 [[mechanisms/action_points|AP]]) and doesn't drain [[mechanisms/action_points|AP]]. Resting restores 1 [[mechanisms/action_points|AP]] per hour.
- **Vitals & Consumables**: Stim Packs restore 2 [[mechanisms/action_points|AP]] (requires Stim Conditioning Lvl 1). Any [[mechanisms/action_points|AP]] over max capacity is lost.
- **[[Midnight]] Lamp Expiration**: Lamps expire at [[Midnight]]. Standing in an unlit hex (no pole) during expiration results in instant death.
- **Base Menu**: Standing on the Base tile unlocks the "Enter Base" button.
- **Town Bank**: Items can be deposited/withdrawn from the town bank via the Base menu.
- **Town Status**: Power levels (Light & Survival bar) and Night Use drain are visible in the Base menu.
- **Base Constructions**: Advanced buildings (Watchtower, Well, etc.) are built via the Base menu using banked resources.

## 2. Vitals & The "[[Midnight]] Toll"
- **Drain Rate**: How much [[Hunger]] and [[Thirst]] is lost per hour?
- **[[Midnight]] Event**: Confirm if [[Hunger]]/[[Thirst]] drops significantly at [[Midnight]] (the "Daily Consumption").
- **Resource Generation**: Confirm the Well produces exactly 10 water at midnight and Hydroponic Patch produces rations/salad.
- **Death by Vitals**: What happens when [[Hunger]] or [[Thirst]] reaches 0%? Is it instant death or a health drain?
- **Health Recovery**: How is "Health" restored? Does "Resting" heal you, or only "Medicine"?

## 3. Power & [[mechanisms/infrastructure|Infrastructure]]
- **Base Power Drain**: How much does "Night Use" increase per Power Pole placed?
- **Power Failure**: Does reaching 0% power immediately end the game for all players in the town?
- **Solar Efficiency**: Confirm the 10% reduction from Solar Panels is multiplicative or additive with other bonuses.
- **Watchtower Range**: Does the Watchtower reveal *all* active objectives or just the closest one?


## 4. Resource Depletion
- **Threshold**: After how many hourly "loot drops" does a hex become "Depleted"?
- **Regeneration**: Do depleted hexes ever recover over time (e.g., after 24 hours)?

## 5. [[mechanisms/exploration|Exploration]] & Map
- **Map Size**: Is there an edge to the world? (Try walking in one direction until you hit a boundary).
- **Visual Range**: Can you see the tile type of an adjacent hex *before* you move into it?

## 6. Death & Persistence
- **Inventory Loss**: Upon death, are items on your person lost forever, or can you find your "corpse" in the next town?
- **Skill Training**: Does dying cancel your currently training skill?
- **Corpse Mechanics**: Can other players loot your items if you die in a shared hex?
