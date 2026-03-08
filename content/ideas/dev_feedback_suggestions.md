# Ideas: Game Development Suggestions (Tester Feedback)

These suggestions are intended for the developers to improve the player experience, balance the survival loop, and solve emerging issues.

## 1. Quality of Life (QoL) & UI
- **Shared Storage Building**: To solve the "[[ideas/dev_feedback_suggestions#Item Overlay|Item Overlay]] Bug" and the 5-slot inventory limit, add a "Storage Crate" or "Warehouse" building at the Base. This provides a clean UI for shared resources rather than dropping items on the floor.
- **Map Pinging System**: In a collaborative game, players need to "ping" a hex (e.g., "Found Oasis here" or "Need Power Pole here"). A simple alt-click on a tile could broadcast a coordinate to the town chat.
- **Stim Buff Tracking**: With the addition of high-tier **[[items/stim_injector|Stim Injectors]]** and **[[items/stim_overdrive|Stim Overdrive]]**, a clear status icon should show the remaining duration of any active buffs and the "Conditioning" level required to use them.
- **Action Queueing**: For repetitive tasks like scavenging or "Resting," allow players to queue up a certain amount of [[vitals/action_points|AP]]/time so they don't have to click "Start" repeatedly.

## 2. [[mechanisms/infrastructure|Infrastructure]] & Base Building
- **Rechargeable Batteries**: Instead of **Batteries** being one-time use, allow the **[[biomes/electronic_lab|Electronic Store - Lab]]** to have a "Charging Station" that uses town Power to refuel empty batteries.
- **Advanced Research Visualization**: The **[[mechanisms/infrastructure|Research Lab II]]** (+20% speed) should provide a clear progress bar for the second research slot to help the town coordinate long-term projects.
- **Power Grid Map**: A dedicated overlay that shows the "connectedness" of the town's grid, making it clear where the next **[[items/power_pole|Power Pole]]** should be placed.

## 3. Light & Darkness Refinement
- **Fear Implementation Note**: The Fear vital is now active (March 5, 2026). Refinements focus on managing its penalties. When full, the player dies or suffers severe [[vitals/action_points|AP]] penalties. This gives a small window (2-3 seconds) to realize a mistake and move back.
- **Flares/Glowsticks**: A cheap, one-time use item that provides light to a single hex for 5-10 minutes. Useful for "scouting" ahead before committing a permanent Power Pole.
- **Fear Resistance Items**: Add a "Calming Herbal Tea" (crafted from Oasis plants) or "Weighted Vest" (crafted from Scrap) that slows the rate of Fear accumulation in the dark.

## 4. Collaborative Roles (The "Job" System)
...

## 7. Environmental Dynamics
- **Biome Hazards**: Introduce biome-specific threats like "Sandstorms" (Desert) that drain AP/thirst faster, or "Toxic Mist" (Industrial) that increases Fear even in the light.
- **Power Pole Upgrades**: Allow players to upgrade a **Power Pole** (using Circuit Boards) from a 0-hex radius to a 1-hex radius. This would provide a massive late-game reward for technical progression.
- **The "Solar Eclipse"**: A rare world event where all solar power generation stops for 24 hours, forcing the town to rely entirely on stored fuel and manual scavenging.
- **Social HUD**: Allow players to see the **Fear** levels of their teammates in the chat or on the map. This lets "Survivors" know who needs an escort back to base.
- **Specialization Buffs**: If a player has a high level in a skill (e.g., Field Engineering Lvl 3), give them a unique "Title" in chat and a small passive bonus to everyone nearby (e.g., "Expert Engineer: -10% build cost for allies in same hex").
- **Town Goals**: A "Message Board" at the Base where players can vote on the next major project (e.g., "Build Solar Array" vs "Expand to Human Farm").

## 5. Narrative & Discovery
- **"Log" [[items/index|Items]]**: [[mechanisms/scavenging|Scavenging]] in the "Ruined City" should occasionally drop "Data Logs" or "Journal Scraps" that provide world-building lore about the "Darkness" and the "Human Farm."
- **Visual Evolution**: As the town's Power level increases, the Base should visually upgrade (e.g., more lights, cleaner textures) to give players a sense of "winning" against the wasteland.

## 8. Reported Technical Issues (Bug-Suggestions)
The following issues have been identified by testers and are being tracked through the suggestions feature for developer review.

### Item Overlay/Overflow (Improved Mar 6)
- **Description**: When too many items are dropped on a single hex, the visual representation of those items begins to overlay or bleed into adjacent tiles.
- **Patch Note (Mar 6, 2026)**: Improved handling for overflowing tile icons to reduce visual clutter.
- **Symptoms**: Visual clutter in high-activity areas (like the Base or popular scavenging spots); difficulty clicking on or interacting with the underlying tile or other items due to visual overlap.
- **Tester Recommendation**: Implement a "Stacked Item" UI where multiple items on one tile are represented by a single icon with a counter (e.g., "x5 Items").
