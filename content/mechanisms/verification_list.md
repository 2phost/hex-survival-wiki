# Mechanism: [[mechanisms/verification_list|Verification List]] (Required Testing)

These are the "known unknowns" that require testing to confirm how the game's internal logic works.

## 1. Confirmed Mechanics
- **Movement**: Consumes 1 [[mechanisms/action_points|AP]] per hex (uniform for all tiles).
- **[[mechanisms/skills|Skills]]**: 0 [[mechanisms/action_points|AP]] to start/pause. Can pause progress to switch research. Level 1 skills (like Stim Conditioning and [[mechanisms/action_points|AP]] Capacity) take 1 hour of real time. Level 2 ([[mechanisms/action_points|AP]] Capacity) takes 24 hours.
- **Inventory**: 0 [[mechanisms/action_points|AP]] to drop, consume, or combine.
- **[[mechanisms/infrastructure|Infrastructure]]**: [[Power Poles]] only light their own hex (1-tile range). Must be placed adjacent to a lit tile.
- **Activities**: Starting/stopping scavenging is free (0 [[mechanisms/action_points|AP]]) and doesn't drain [[mechanisms/action_points|AP]]. Resting restores 1 [[mechanisms/action_points|AP]] per hour.
- **Vitals & Consumables**: Stim Packs restore 2 [[mechanisms/action_points|AP]] (requires Stim Conditioning Lvl 1). Any [[mechanisms/action_points|AP]] over max capacity is lost.
- **[[Midnight]] Lamp Expiration**: Lamps expire at [[Midnight]]. Standing in an unlit hex (no pole) during expiration results in instant death.

## 2. Vitals & The "[[Midnight]] Toll"
- **Drain Rate**: How much [[Hunger]] and [[Thirst]] is lost per hour?
- **[[Midnight]] Event**: Confirm if [[Hunger]]/[[Thirst]] drops significantly at [[Midnight]] (the "Daily Consumption").
- **Death by Vitals**: What happens when [[Hunger]] or [[Thirst]] reaches 0%? Is it instant death or a health drain?
- **Health Recovery**: How is "Health" restored? Does "Resting" heal you, or only "Medicine"?

## 3. Power & [[mechanisms/infrastructure|Infrastructure]]
- **Base Power Drain**: If the town has 72% power, how much does it drop every hour/day?
- **Generator Output**: How much Power (%) does a Gasoline Generator or Solar Cell add to the town total?
- **Industrial Facility**: What is the "production" output once "Grid Power: Online"?

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
