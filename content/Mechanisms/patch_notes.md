---
title: "Patch Notes"
---

# [[Mechanisms/patch_notes|Patch Notes]]

## Monday, Jun 22, 2026: Escort Consumables
* **Follower Needs**: Consumables can now be dragged onto follower needs to use them more naturally.
* **Group Items**: Group consumable use works more reliably from the needs area.
* **Inventory Smoothing**: Inventory interactions around needs and consumables should feel smoother.
* **Engine Refresh**: The game engine and build tools were refreshed as part of routine maintenance.

---

## Wednesday, Jun 24, 2026: Notifications & Death Summary
* **Notification UI**: The notification button now returns properly after permission prompts.
* **Notification Fix**: Notification permission checks are less likely to hang.
* **Achievements**: Run achievement summaries are preserved more reliably.
* **Death Summary Scroll**: The death summary can now scroll when there are many achievements or details.
* **Network Packages**: Connection and real-time messaging packages were refreshed for stability.

---

## Thursday, Jun 25, 2026: Workshops & Timers
* **Search Timers**: Search timers now better match the current workshop bonuses.
* **Cooldown Timers**: Scavenge cooldown timing is shown more accurately in the UI.
* **Milling**: The Scrap Workshop can now mill Charred Planks.
* **Combining**: Workshop combining options are easier to find from the Workshop panel.

---

## Saturday, Jun 27, 2026: Mobile Display
* **Canvas Reliability**: The game canvas now appears more reliably after login.
* **Touch Input**: Touch input on mobile devices should behave more consistently.
* **Browser Settings**: The game now chooses safer display settings across different browsers.
* **Chrome Mobile**: Chrome mobile received additional fixes for display and input problems.

---

## Sunday, Jun 28, 2026: Mobile Login Fixes
* **Mobile Login**: Mobile login and connection flow is smoother after signing in.
* **Chrome Mobile Fix**: Chrome mobile should be less likely to show a black screen after login.
* **Return Flow**: Returning from login to the game is more reliable on phones.

---

## Monday, Jun 29, 2026: Mobile Connectivity
* **Connection UI**: Connection screens are less likely to block you from reaching the game.
* **Error States**: Startup failures now show clearer information instead of leaving the page stuck.
* **Loading Reliability**: Loading into the game should be more reliable, especially on mobile.
* **Mobile UX**: Touch and graphics behavior on mobile devices has been improved.
* **Compatibility**: Browser compatibility was refreshed as part of routine maintenance.

---

## Tuesday, Jun 30, 2026: Mobile Polish
* **Resume Prompts**: Active-run resume prompts are easier to see on Chrome mobile.
* **Mobile Startup**: Mobile startup should get stuck behind loading or auth screens less often.
* **Mobile Lighting**: Lighting on mobile has been adjusted for better compatibility.

---

## Wednesday, Jul 1, 2026: Health & Troubleshooting
* **Health System**: Health and injury systems were added, including healing items and supporting UI.
* **Incapacitation**: Players can now become incapacitated and recover through the new health flow.
* **Debug Panel**: A Debug Options panel was added for testing and troubleshooting during playtests.
* **Mobile Rendering**: Mobile rendering is more reliable, especially on Chrome and devices with limited graphics support.
* **Canvas Fallbacks**: The game now has extra safeguards for cases where the canvas fails to display correctly.
* **Diagnostics**: Mobile diagnostics were improved to make display problems easier to report and fix.

---

## Thursday, Jul 2, 2026: Player Data
* **Safe Loading**: Older player records now load more safely when health data is missing.

---

## Friday, Jul 3, 2026: Stability & Under-the-Hood Fixes
* **Map Rendering**: The game is less likely to interrupt play if the map display has trouble recovering.
* **Network Stability**: Chat, forum posts, suggestions, and other multiplayer features should feel steadier behind the scenes.
* **Health HUD**: Health is easier to understand, with clearer HUD labeling and improved tutorial text for injuries and healing.
* **Menu Scrolling**: Town resource history now stays inside its panel and scrolls more reliably.
* **Menu Lists**: Long base-upgrade lists are easier to browse without text or rows spilling outside the window.
* **Browser Performance**: General maintenance should make the game a little more stable across browsers.

---

## Sunday, Jul 12, 2026: UI & Quality of Life
* **Friends UI**: Friends controls now show helpful hover hints and no longer darken the rest of the game when the Friends panel is open.
* **Escort UI**: Escorted followers can now look at the group's carried items without seeing leader-only Search and Attack controls.
* **AP Refresh**: Action Points now refresh more reliably at midnight for players who are already online.
* **Ground Items**: Ground item lists fit inside the inventory panel more cleanly, so items are easier to read and pick up.
* **Login Polish**: Signing in should feel smoother, with fewer cases where the loading screen gets in the way of the login form.
* **ACTION Bar Redesign**: The ACTION bar has a new look: Health, AP, Fear, and your current activity now live inside the bar, with your stats shown right on the frame.
* **Panel Closing**: Close buttons on panels are easier to spot, with a clearer red X in the corner.
* **Tutorial Hints**: The final tutorial tip now shows how to run the tips again: open MENU, choose NOTIFICATIONS, then tap Reset Tutorial.
* **Tutorial Z-Index**: That last tutorial tip now stays visible above the Notifications panel instead of hiding behind it.
* **Modal Backgrounds**: Opening Notifications no longer dims the whole game behind the panel.
* **Responsive HUD**: The HUD scales down on smaller PC windows so buttons and gauges stay readable without switching to the phone layout.
* **Loading Screen**: The loading screen now shows a progress bar and status text while the game starts up.

---

## Monday, Jul 13, 2026: Skills & Menus
* **New Skills**: New Leadership skills improve escort group coordination and follower readiness, while the new Vitality skill helps improve your personal health.
* **Escort Inventory**: Escort group inventory is easier to manage, with clearer carried-item lists and smoother follower item transfers.
* **Menu UX**: Inventory and crafting panels are easier to use, with better scrolling, cleaner item handling, and fewer panel interaction hiccups.
* **Crafting Progression**: Town combining now unlocks through the Assembly Bench, making the town upgrade path clearer for shared crafting.
* **Town UI Polish**: Town store and chat areas are easier to read and interact with during busy play sessions.
* **Panel Management**: Map finder, forum, suggestions, and other foreground panels close and layer more reliably over the HUD.
* **HUD Alignment**: The action HUD is better aligned and keeps key survival stats easier to scan while playing.

---

## Tuesday, Jul 14, 2026: Incapacitation Refinements
* **Revives**: Teammates on your tile can use healing items to revive you when you are incapacitated, so a downed survivor is not stuck waiting alone.
* **Item Retention**: Becoming incapacitated no longer dumps your carried items on the ground — your pack stays with you while you are down.
* **Bug Fix**: Logging back in no longer flashes a confusing damage toast from your saved health state.

---

## Wednesday, Jul 15, 2026: Rest Abilities, Camp Gear & Crafting Overhaul
* **Active Resting**: Rest is now an active ability: press R (or choose Rest on the tile menu) to start and stop resting. Searching no longer automatically switches you into rest when it finishes.
* **Rest Mechanics**: You cannot move while resting. Press R again to stand up before walking to a new hex.
* **Activity Switching**: You can switch directly between searching and resting — press E to search or R to rest without stopping the other activity first.
* **HUD Hints**: When you are idle, the ACTION bar shows keyboard hints ('R' = rest · 'E' = search) instead of an empty progress bar. The timer only appears while search, rest, camp, or fear calming is actually running.
* **Group Rest**: Escort leaders can start or stop Rest for followers in the Group panel, the same way as Search.
* **Movement Cancels Rest**: Moving with your escort group now cancels follower rest, matching how search stops when the group moves.
* **Camp Gear Mechanics**: Camp gear now works like your other worn equipment: put a bedroll, shelter, or tent in the Camp slot and it automatically helps while you rest, giving you a better chance to earn bonus Action Points each hour.
* **Camp Items**: Three camp items can be found in the wild — Field Bedroll, Survival Shelter, and Expedition Tent — with stronger gear offering bigger rest bonuses. They are reusable but can wear out over time.
* **Camping Visibility**: When you are resting with camp gear equipped, other players can see that you are camping.
* **Consumable Update**: Alien Vegetable now restores 1 Action Point when eaten.
* **Town Vaults**: Towns can activate a sealed Vault depot: stash supplies there, keep power running if the town falls, and move items between the vault cache and your inventory with drag and drop.
* **Drone Loading**: Cargo drones are easier to load and send, and gear you are wearing can no longer be loaded into a drone by mistake.
* **Pole Damage**: Monsters can damage power poles, and poles that are badly hurt flicker so you can spot grid trouble before the lights go out.
* **Crafting UI**: The Crafting Book has a cleaner recipe layout: each row shows the result on the left and requirements on the right, with ingredient counts aligned for quick scanning.
* **Recipe Sorting**: Recipes you can craft right now sort to the top of the Crafting Book, so ready combines are easier to find.
* **Workshop Tab**: After you build the Scrap Workshop in town, the Crafting Book gains a Workshop tab listing all town combine recipes for reference — even while you are away from town. Crafting still happens at town; the tab is view-only.
* **Field Tab**: Field recipes stay on the Field tab and can still be crafted from your carried inventory.
* **Recipe Change**: Milling Charred Planks into Timber now requires the Assembly Bench instead of the Scrap Workshop.
* **Tab Switching Fix**: Switching between Field and Workshop tabs in the Crafting Book now works reliably at any scroll position.
* **Resizable Panels**: Most floating panels — inventory, help, friends, crafting book, forum, and others — now have a corner resize handle so you can scale them to fit your screen.
* **Scrolling Fix**: Scroll-wheel panel scaling was removed; use the corner handle instead.
* **Panel Reset**: Notification settings now include Reset All Panel Sizes to restore every panel to its default scale.
* **Achievements UI**: The Achievements panel now matches other HUD modals: no screen dimming, and you can drag and resize it like inventory or help.
* **Forum Panel Fix**: The forum panel no longer blocks dragging or resizing other UI while it is open.
* **Power Controls**: Base power controls stay on the Overview tab, with a simpler layout for checking and upgrading town power.
* **Group Inventory Polish**: Moving items in escort group inventory is more reliable, with drag icons that stay visible while you hand things off.

---

## Thursday, Jul 16, 2026: Keybinds & Locate Improvements
* **Custom Shortcuts**: Settings now includes keyboard shortcut customization — rebind common actions to keys you prefer, and put any shortcut back to its default if you change your mind.
* **Locate Markers**: Locate Tile lets you mark several important tiles at once, and the button shows how many you have selected.
* **Locate Menu**: The Locate Tile menu remembers where you left the panel, and its layout is cleaner for quick scanning.
* **Pole Repairs**: Damaged power poles can be repaired from the tile actions, so you can restore grid light without tearing them down.
* **Salvage Scaling**: Taking down a damaged power pole returns fewer materials based on how hurt it is — healthy poles still give the full salvage.
* **Camp Durability**: Camp gear durability was tuned so bedrolls, shelters, and tents wear out at a fairer pace while still rewarding careful use.
* **Journal Focus**: The Command Journal focuses more on the reports that matter for your run, with the old executive summary section removed.
* **Group Inventory**: The Group panel no longer shows ground-item slots, so escort inventory stays focused on what people are carrying.

---

## Friday, Jul 17, 2026: Crafting & UI Polish
* **Medical Visuals**: Medical item icons got a visual refresh so healing supplies are easier to recognize at a glance.
* **Facility Tooltips**: Inspecting a town facility tile now shows which goods it can produce, so you can plan fabrication without guessing.
* **Item Breakdown**: Breaking down a Thermal Coil can now yield useful parts such as ionized filaments, copper wiring, scrap, and occasionally a battery.
* **Production Focus**: Farm and Electronics Lab production lists were tightened: salad and circuit boards are no longer facility outputs, keeping those lines focused on the remaining recipes.
* **Tribunal UI**: The Tribunal panel is easier to read during votes and case reviews.
* **Run Gear Screens**: Run Gear screens are cleaner and easier to scan when you check what you have unlocked.
* **Settings Reorganization**: Account options and debug tools now live under Settings, so those controls sit in one familiar place.
* **Menu Cleanup**: The Keyboard Shortcuts popout looks cleaner, and Settings dropped leftover helper text that cluttered the panel.
* **Panel Scaling**: Text stays sharper after you resize floating panels.
* **Mobile Enhancements**: On mobile, the Command Journal scrolls more reliably, and chat is easier to close when you are done reading.

---

## Saturday, Jul 18, 2026: Mobile UI & Menus
* **Mobile Map Zoom**: On phones, the map starts zoomed out farther so you can see more of the surrounding area at once.
* **Mobile Panels**: Town panels on mobile fit the screen better, so categories, research lists, and other town menus stay usable without awkward clipping.
* **Menu Scrolling**: Long base-upgrade lists scroll sideways more reliably when there are many options to browse.
* **Medical Item Sorting**: Healing supplies such as gauze, bandages, first aid kits, and trauma stabilizers are now listed under Medical, making them easier to find when someone is hurt.
* **Loading Bar Fix**: The game no longer shows two loading bars stacked on top of each other while it starts up and connects.

---

## Sunday, Jul 19, 2026: Drones, Gear, & HUD Upgrades
* **Drone Deliveries**: Drone Operator Level 4 lets you choose where a field cargo drone goes: send the load to town storage, or deliver it straight to another player in your town.
* **Offline Delivery**: Cargo drone deliveries to players who are offline now arrive correctly in their inventory when they next play.
* **Guard Armor**: New Guard armor run gear covers head, chest, legs, hands, feet, and charm slots. Equipping it reduces damage from monsters fighting back, and stronger pieces also raise your max health.
* **Healing Springs**: Rare Healing Spring tiles now appear on newly generated maps. Rest on one to restore +10 health each rest cycle, and the ACTION bar shows Resting and healing while that recovery is active.
* **Full AP Healing**: You can rest on a Healing Spring to recover health even when your Action Points are already full.
* **Spring Scavenging**: Healing Spring tiles use oasis scavenger finds for now, so searching one feels like searching an Oasis.
* **Lighting Updates**: Lit areas around your base and power poles look brighter and warmer at night, with a soft glow that makes nearby tiles easier to read without washing out the center hex.
* **Survival Warnings**: Hunger and Thirst now warn you from 60% upward with a pulsing red readout and a clear alert, since staying that high means you will not survive the next midnight without food or water.
* **Crafting Search**: The Crafting Book now has a search box next to the Field and Workshop tabs — type to find recipes or items by name.
* **Text Rendering**: On-screen text is clearer and sharper, especially on smaller windows and lower-resolution displays.
* **Panel Contrast**: Dark panels like Inventory and the Crafting Book use brighter secondary text so labels and descriptions are easier to read.
* **ACTION Bar Visuals**: Health, AP, Fear, Thirst, and Hunger labels on the ACTION bar are brighter and easier to read, and the main activity progress bar fills its frame more cleanly.
* **MENU Button**: The top-right MENU button has a cleaner look so it stands out more clearly against the map.
* **Reward Clarity**: The Command Journal more clearly explains run gear rewards: new unlocks for your next survivor, or salvage when you already own a duplicate.
* **Offline Combat Harm**: If followers take combat damage while you are offline, that harm now saves correctly so their health matches when you reconnect.
* **Website Media**: The marketing website now shows its gameplay and character images again instead of blank placeholders.

---

## Monday, Jul 20, 2026: Escorts & Medical
* **Group Attacks**: Escort leaders can now order a group attack on a tile — your followers strike together, and monsters fight back once against the group instead of punishing each person separately.
* **Incapacitation Rules**: While you are incapacitated you can no longer heal yourself with items; a teammate has to revive you, and the ACTION bar clearly shows that you need an ally heal.
* **Locate Tile Updates**: Locate Tile no longer lists town buildings, and the tile list is laid out in two columns so important sites are easier to pick.
* **Skill Icons**: New skill icons for Field Medicine, Vitality Training, Escort Leadership, and Field Pull make those abilities easier to recognize in the skill tree.

---

## Wednesday, Jul 22, 2026: UI
* **Gear Rarity**: Run gear on the survivor setup screen is now color-coded by rarity, so stronger unlocks stand out when you kit out a new survivor.

---

## Thursday, Jul 23, 2026: Journal Rebuild & Medical
* **Command Journal**: The Command Journal has been rebuilt as a clearer daily briefing: mission results, overnight recovery, and station status are easier to scan in one place.
* **Objective Rewards**: Completed objectives now show the rewards you earned, and unfinished ones spell out the consequences more clearly.
* **Recovery Summaries**: Recovery summaries include item icons and clearer totals so you can see what the outpost brought in overnight at a glance.
* **Survivor Profiles**: Hover a survivor's name in town chat or the Town Survivors list to see a quick profile with career points, achievements, and when their account was created.
* **Field Bandage**: You can craft a Field Bandage by sterilizing salvaged fabric with a Bottle of Alcohol — a new uncommon medical find out in the world.
* **Bug Fix**: Fixed a rare issue that could wipe a survivor's career points and achievements after a town fell while reconnecting.

---

## Saturday, Jul 25, 2026: Cargo Drones
* **Travel Time**: Cargo drones no longer arrive instantly — sending one to town or another player now takes hours of real travel time.
* **Locked Cargo**: While a drone is in the air, its cargo is locked in transit: you cannot use those items from your inventory or the town bank until it lands.
* **Tracking**: You can watch cargo drones fly across the map toward their destination, with a countdown showing how long until delivery.
* **Drone Logistics**: A new skill after Drone Operator, Drone Logistics, shortens cargo drone travel time — deliveries still take hours even when fully trained.

---

## Sunday, Jul 26, 2026: Food & Drink Variety
* **New Consumables**: Survivors can now find a wider variety of food and drink out in the world — from canned goods and trail snacks to herbal tea, mineral water, and other scavenged refreshments.
* **AP Restoration**: Eating and drinking still ease hunger and thirst, and these finds also help restore Action Points so you can keep moving.

---

## Monday, Jul 27, 2026: Guilds
* **Persistent Guilds**: Guilds let survivors join a persistent group that stays with you across towns — not just the outpost you are standing in today.
* **Guild Management**: Open Guild from the menu or press G to create a guild, browse existing ones, or ask to join. Guild leaders approve new members, and each survivor can only belong to one guild at a time.
* **Guild Chat**: Guild chat is a private channel for your members, alongside Town and Global chat, so you can coordinate without filling the town channel.
* **Guild Forum**: The Guild Forum is a shared board for your group to plan routes, share discoveries, and leave notes between play sessions.
* **Guild Identity**: When you belong to a guild, its name appears under your survivor name above your character on the map, so allies and strangers can see who runs together.

---

## Wednesday, Jul 29, 2026: Forums & Resource Logs
* **Forum Search**: Town, World, and Guild forums now have search — use the magnifying glass to find threads by title, who posted, or words in the conversation, including replies from people who did not start the thread.
* **Forum Reactions**: You can react to forum posts with emoji: tap an existing reaction to add yours, or use + to pick one when you want to acknowledge a tip, cheer a find, or show you read it.
* **Resource Log Filters**: The Town Resource Log has filters for day, survivor, action type, and resource, so you can quickly see who deposited, withdrew, or spent what without scrolling the whole history.
* **UI Scaling**: Menus and panels scale more cleanly on high-resolution screens and large monitors, so text and buttons stay comfortable to read instead of shrinking into the corner.

---

## Thursday, Jul 30, 2026: Buildings & Communications
* **The Forge**: The Forge is a new town building you can construct after the Logistics Uplink. Use it to turn scrap metal into fortified rebar at town, unlocking stronger crafting recipes for your outpost.
* **New Resource**: Ceramic pots can be scavenged from the world and broken down into ceramic shards for crafting.
* **Town Chat Enhancements**: Town chat now opens in the same draggable, resizable panel style as your inventory and other menus, with more room for messages and clearer tabs for Local, Global, and Guild.
* **Chat Notifications**: Chat tabs glow when you have unread messages on any channel, so you can spot new Local, Global, or Guild traffic at a glance.
* **VIP Marking**: You can mark players as VIP from Global or Guild chat even when they belong to another town.
* **Mobile Escort Feature**: On mobile, escort leaders can use food, drink, and medical items on followers directly from the group inventory.

---

## Saturday, Aug 1, 2026: Terrain & Map Features
* **Lakes**: New maps can include lake clusters — open water you cannot walk across, with shore framing so the water reads clearly against land and void.
* **Map Profiles**: Existing towns keep their current layout; lakes only appear on newer map profiles.

---

## Sunday, Aug 2, 2026: UI Navigation
* **Combine Tab Filters**: The town Combine tab has category filters so you can narrow recipes by output type instead of scrolling the full list.
* **Command Journal**: The Command Journal remembers yesterday's resolved briefing after midnight until today's report is ready, then opens on today's briefing once you are caught up.

---

## Monday, Aug 3, 2026: Performance & Crafting
* **Town Crafting**: You can craft and combine at town from any town tile — you no longer need to stand on a specific workshop hex to use town recipes.
* **Map Rendering**: Map panning and world updates hitch less: the hex grid reuses sprites instead of rebuilding from scratch, and full redraws wait until you finish dragging.
* **Markers Update**: Monster and facility markers refresh on their own layers when they change, so ordinary multiplayer movement no longer forces a full map rebuild.
* **HUD Freezing**: The HUD freezes more cleanly while you pan, and joining a town coalesces early redraws so the first look at the world stutters less.

---

## Wednesday, Aug 5, 2026: Phase 2 Objectives & Consumables
* **Phase 2 Victory Conditions**: After the Command storyline completes, surviving towns enter Phase 2: commit to Protocol Evac (raise an extraction beacon and hold power through three activation midnights) or Protocol Purge (seal corruption relays and survive the Omega siege). Completing either hard victory earns a score bonus and a Hall of Fame record.
* **Objective Balancing**: Command directives no longer ask you to deposit clean water or rations. Purification and triage objectives now take scavenged supplies instead, and Command releases water and rations as rewards when you succeed.
* **Task Tracking**: When you clear a main or side Command objective during the day, it stays visible in the task panel and day HUD with a completed status, so you can see what is done and what is still due before midnight.
* **New Consumable**: Vital Stasis Patch is a new medical consumable that can stabilize a survivor when health is critically low.

---

## Thursday, Aug 6, 2026: Run Summaries & Gear Updates
* **Death Screen Summaries**: Death screen run summaries now count ground pickups, deposits, quests, and monster kills correctly — including when you spent most of the run in escort mode.
* **Final Transmission Text**: Final transmission text no longer invents stat counts; it appends an accurate run log from your saved progress.
* **Achievements**: Achievements on the death screen no longer mark your whole career as new when career data was missing at town fall.
* **Leaderboards**: Fallen towns are archived for the town rankings as soon as they fall, so outposts that clean up quickly still show on the leaderboard.
* **Survivor Setup Screen**: Run gear on the survivor setup screen shows stats in the dropdown list, keeps the closed selection as name and rarity only, and stacks duplicate bonuses in the run summary line.
* **In-game Run Gear Overview**: The in-game Run Gear overview (P) now shows item name, rarity, and full stat lines instead of truncated flavor text.
* **Swift March Boots**: Swift March Boots and higher-tier speed boots now add small fear-penalty bonuses at the same AP tier instead of repeating the same stats as the common pair.

---

## Saturday, Aug 8, 2026: Tooltips & Quality of Life
* **Tooltips**: Map, item, mission, construction, skill, and HUD tooltips are clearer and easier to scan, with status, costs, and meters up front.
* **Ground Items**: Ground items on a tile are listed with icons instead of a long text dump.
* **Escort Invites**: When invited to an escort group, you can choose Always to join and trust that friend for future invites.
* **Day Header Info**: Defense and power on the day header show tonight's attack versus defense and power use versus your stored reserve.
* **Live Score Estimate**: Other survivors' profiles show a live score estimate for their current run while they are still alive.

---

## Friday, Aug 7, 2026: Exploration & Objectives
* **Exploration**: Exploring terrain now also reveals any lake water along its shoreline, so discovered land no longer leaves adjacent water hidden.
* **Story Progression**: Command daily objectives now follow the main story arc more closely, with expanded mission tasks and progress that stays synchronized as your town builds and deposits resources.
* **Mission UX**: Task tooltips now include each mission’s flavor text and present rewards and failure consequences more clearly.
* **Command Journal**: The Command Journal now separates supplies recovered overnight from ground items destroyed, making scavenging totals easier to understand.
* **Inventory Panel**: The Inventory panel has a cleaner header with the redundant “Gear and Resources” subtitle removed.

---

## Sunday, Aug 9, 2026: Inventory Workflow
* **Item Dropping**: Double-click an item in your inventory or a follower's pack to drop it on the ground, and double-click a ground item in the inventory panel to pick it up.
* **Ground Transfers**: Drag items directly between the ground list and escort group inventories without moving them through your own pack first.
* **Item Swapping**: Dropping an item onto another survivor's occupied inventory slot swaps the two items, including between group members even when packs are full.
* **Tutorial UI**: Onboarding tutorial tips now match the look of the game's other tooltips.
* **Selection Feedback**: Selecting items in your inventory no longer jiggles — selection feedback matches the group inventory panel.

---

## Monday, Aug 10, 2026: Specimen Research & Monster Loot
* **Monster Drops**: Monsters can drop specimen parts onto the ground when killed — chitin, sinew, glands, bone, and cores across common through mythic rarities. Pick them up like other loot and deposit them into town stores.
* **Specimen Analysis Bay**: Build the Specimen Analysis Bay (after the Research Lab) to unlock High Command donations. From the Donate tab, move monster parts from the stockpile into a donation pile; Command returns a random reward crate into town stores based on what you offered.
* **Specimen Research**: New specimen research projects spend those monster parts (not research material) for town-wide combat benefits: stronger weapon damage against monsters, better part drop rates, and related defensive doctrines. Open Base Upgrades → Research to start them once the lab is built.
* **Command Objectives**: High Command side objectives can now require harvested specimens, so scavenging parts also feeds daily Command progress.

---

## Tuesday, Aug 11, 2026: Performance & Mobile UX
* **Drone Reliability**: Cargo drones sent to town or another survivor are much more likely to survive server restarts and deploys — in-flight cargo should no longer vanish mid-route when the world comes back up.
* **Load Times**: The game loads lighter and faster: map tiles and marketing art use smaller WebP images, and item, build, skill, and objective icons load when you need them instead of all at once.
* **Mobile Fullscreen**: On phones, inventory and escort group sheets lock to a true fullscreen layout and fill the screen edge-to-edge, including over safe areas, without leaving gaps or bleed.
* **Mobile Tooltips**: Mobile map and inventory interactions are cleaner — fewer accidental tooltip pop-ups while you tap and drag.
* **Journal Accuracy**: Command Journal effect text now matches the actual rewards and penalties for each outcome.
* **Mission HUD**: Mission and directive HUD rows show the correct building icons again when a task asks you to construct or power a facility.

---

## Wednesday, Aug 12, 2026: Balance, Vault Survival, & Power
* **Power Pole Nerf**: We're sorry about the nerf — standard power poles now illuminate only their own tile and the six neighbors around them, instead of reaching two rings out. Reinforced power poles still cast a wider glow, and you can craft a Pole Upgrade Kit to reinforce an existing pole in place.
* **Vault Survival**: When your town falls, survivors who are still alive keep playing — you are no longer wiped with the hub. Fallen towns enter vault survival, and you can reconnect and continue the run from the lobby.
* **Achievements UI**: The Achievements panel is easier to browse: unlocked feats are grouped by category (Crafting, Exploration, Combat, and more), each with its own icon, unlock count, and the date you earned it.
* **Town Rankings**: Town Rankings uses the same draggable panel style as Achievements and Friends, with cleaner player and town leaderboard rows.
* **Pole Upgrade Kit**: Craft a Pole Upgrade Kit at town (Power Infrastructure Lv 3) and install it on a standard pole to upgrade it to a Reinforced Power Pole with longer cable reach and a wider light radius.
* **Vault Map Icons**: Activated evacuation vaults show a green status light on the map so you can spot your fallback base at a glance.
* **Monster Health & Previews**: Monsters on the map now show health pips, and Command Journal mission outcomes preview rewards as item slots with tooltips.
* **Connection Resilience**: Lost connections automatically retry for up to a minute before giving up, so brief Wi-Fi drops are less likely to boot you from town.
* **Construction Costs**: All town building construction costs are roughly doubled to slow early expansion and stretch the mid-game.
* **Storage Sorting**: Monster parts in town stores are grouped in their own category instead of mixed with general supplies.
* **UI Layering Fixes**: Fixed town chat, group panel, and modal layering so open panels stack correctly and chat chrome renders again.
* **Tooltip Fix**: Dragging a panel no longer leaves tooltips stuck on screen underneath your cursor.
* **Lamp Durability**: Portable lamps on the ground now burn out over time as their durability ticks down each midnight, including while you are offline.

---

## Thursday, Aug 13, 2026: Construction Brief Skill & HUD
* **Construction Brief Skill**: New Construction Brief skill (Field Pull Lv 3): pin one unfinished town build's material checklist to everyone's HUD below mission objectives so the crew knows what to deposit.
* **Pinning Builds**: Open Construction and right-click a build node to pin or unpin it; pinned builds show a green PIN badge on the tree.
* **Collapsible HUD**: Mission and Construction HUD sections can be collapsed — click a section title (▼/▶) to hide or show its detail rows. Your preference is remembered between sessions.
* **HUD Fixes**: The pinned construction list no longer overlaps the left action buttons, and collapsing sections correctly hides item icons instead of leaving stray sprites on screen.

---

## Friday, Aug 14, 2026: Map Interaction & UI Polish
* **Map Clicks**: Map clicks and tile tooltips work across the full playfield again, including under HUD chrome and at the screen edges.
* **Mission HUD Artwork**: Mission HUD facility-queue rows (farm and similar) now use the same objective artwork as the tooltip instead of the map tile.
* **Command Journal Bonus**: Command Journal shows today's daily bonus beside the morning report, and missing daily objective icons are filled in.
* **Research UI**: Research cards drop the extra duration block and status badges — in-progress work uses a time bar with total and remaining, and "what it does" is the description only.
* **Power Bar & Logs**: Base power's current/max percent is centered on the bar, and the town resource log packs more entries on screen with search sitting in the table header.

---
## Tuesday, Mar 24, 2026: Journal & Quest Refinement
* **Journal Updates**: Refreshed Journal graphics and disabled auto-opening on every login for a cleaner start.
* **Quest & Objective UX**: 
    * Updated quest interface and centered the mission objectives panel layout.
    * Moved the story-quest unread indicator onto the main action button for better visibility.
* **Morning Briefing Enhancements**: Improved reliability and detail by preferring resolved daily reports and showing the full recovered-item dataset in salvage summaries.
* **Expanded Map Controls**: Added additional zoom-out range on the world map.

---

## Monday, Mar 23, 2026: Preparedness & Mental Fortitude
* **Preparedness Skill**: Added the **[[Skills/preparedness|Preparedness]]** skill. New survivors now start with gear based on their skill level (Starter Lamp -> Rations/Water -> Stim Pack -> Shiv -> Salvager Pack).
* **Mental Fortitude Skill**: Added the **[[Skills/mental_fortitude|Mental Fortitude]]** skill, raising a survivor's maximum fear cap by up to three points.
* **Command Objective Balancing**: Rebalanced early-game tasks to require fewer materials and rely on more common finds.
* **Task Notification Persistence**: Daily "new task" notifications now persist through refreshes and reconnects for the current day.
* **Fear Reset**: Joining a new town now correctly resets Fear to 0.
* **Multiplayer Stability**: Improved presence handoff during reconnects to reduce interference between old and active survivor states.
* **Scavenging Pacing**: Adjusted tile depletion so scavenging pressure ramps more smoothly.
* **Forum Enhancements**: Rebuilt composer with emoji shortcut buttons and refined picker control sizing.
* **Visual Map Feedback**: Clicking shared map tiles from chat now gives clearer visual jump feedback.
* **Loot Visibility**: Map loot markers now display stack counts directly, and the inventory panel shows total items on the current tile.

---

## Friday, Mar 20, 2026: Faction & Supply Reports
* **Town Faction System**: Added a new **[[Mechanisms/faction_system|Town Faction]]** system tied to daily command objectives. Each completed main or side task grants faction for the town.
* **HQ Supply Reports**: Introduced headquarters supply reports at midnight on Days 5, 10, 15, and 20. Reports grade task completion and deliver scaling rewards (Common -> Mythic).
* **Morning Briefing Update**: Briefings now explain the faction system, showing faction gained, total standing, and HQ shipment details.

---

## Tuesday, Mar 17, 2026: Morning Report & Story Expansion
* **Daily Status Loop**: Expanded Morning Report access via both the action button and a global hotkey. Wired additional GameScene/debug paths to keep report state in sync.
* **Hardened Death Reporting**: Offline midnight deaths are now announced back to the originating town more reliably.
* **Morning Report & Forum UX**: Refined panel behavior, improved input handling, and server-side report flow cleanup.
* **Resource Sidebar Expansion**: Town resource sidebar icons now use the full available width, improving scanability.
* **Power-Pole Robustness**: Fixed state preservation across server restarts and corrected transparency/rendering edge cases.
* **Story Content Push**: Substantial update to command story data, extended task/story progression logic, and narrative event surface consistency.
* **Internal Tooling Upgrades**: Major UI/UX improvements in the tools app (layout, styling, richer interactions) and server/tooling integration updates for faster iteration.
* **General Upkeep**: Broad data/config upkeep across items, skill-tree touchpoints, and related server logic.

---

## Sunday, Mar 15, 2026: Game Architecture & Town Reporting
* **GameScene Refactor**: Large-scale modularization of scene logic (init, update, player state, day cycle, etc.) for better maintainability.
* **Enhanced UI Orchestration**: Improved ownership and management of inventory, town-fallen, and base-upgrade overlays.
* **Reliable Town-Fall Reporting**: Hardened server-side reporting to prevent duplicate announcements and ensure town-fall death summaries are explicitly posted in town chat.

---

## Saturday, Mar 14, 2026: Shared Intel & Communication
* **Eidetic Memory & Visibility**: Reworked the visibility model with the **[[Skills/eidetic_memory|Eidetic Memory]]** skill. Exploration information is now shared, day-scoped, and features Lit, Remembered, and Dark tile states.
* **Town Forums**: Added persisted threads and replies for long-term coordination within towns.
* **Communication UX**: 
 * **Item/Tile Chat Linking**: Players can now link specific items or tiles directly in the chat.
 * **Clickable Tile References**: Clicking a tile link in chat centers the map on that location.
* **Inventory Workflow Updates**: 
 * **Recipe Book View**: Centralized interface for managing crafting and viewing combinations.
 * **Smoother Logistics**: Relocated deposit, deliver, and drop-all actions for better town management.
* **Power Stability**: Resolved issues where poles could disappear silently and fixed cable rendering between connected nodes.

---

## Friday, Mar 13, 2026: Grid Expansion & Monster Tracking
* **Reinforced Power Pole (MK2)**: Introduced the **[[Items/Power/power_pole_mk2|Reinforced Power Pole]]** with extended 3-tile range and adjacent-tile illumination.
* **Power Infrastructure Skill**: Added the **[[Skills/power_infrastructure|Power Infrastructure]]** skill to gate advanced grid operations.
 * **Level 1**: Placing basic power poles.
 * **Level 2**: Dismantling existing poles.
 * **Level 3**: Placing Reinforced (MK2) poles.
* **Midnight Horde Reporting**: Total monster spawn counts are now automatically announced in the town chat every midnight.

---

## Thursday, Mar 12, 2026: Logistics & Defense Update
* **Cargo Drone Logistics**: Introduced autonomous courier drones for field-to-base transfers. Requires **[[Skills/drone_operator|Drone Operator Lvl 2]]**.
* **Backpack Tiers**: Rare craftable backpacks added to expand inventory beyond base capacity.
 * **[[Items/Unknown/salvager_pack|Salvager Pack]]** (+2 slots)
 * **[[Items/Unknown/expedition_pack|Expedition Pack]]** (+3 slots)
 * **[[Items/Unknown/hauler_pack|Hauler Pack]]** (+4 slots)
* **Base Defense Overhaul**: Massive expansion to town perimeter defenses with 10 new sequential builds.
* **UI/UX Improvements**:
 * Enhanced Base Upgrade menu with better spacing, scrolling, and build-effect descriptions.
 * Monster markers on the map are now larger, render more reliably, and no longer overlap with player icons.

---

## Monday, Mar 09, 2026: Monster Siege Update
* **Monster Horde System**: **[[Biomes/corrupted_1|Corrupted Tiles]]** now act as active spawning grounds for organized monster hordes.
 * **Horde Life Cycle**: Hordes spawn at Midnight, spend one night **Gathering**, and then begin **Marching** (1 hex per night) directly toward the town.
 * **Environmental Damage**: Advancing hordes consume all ground loot and destroy any **[[Items/Power/power_pole|Power Poles]]** in their path, severing loot highways.
 * **Escalation**: A global **Spawn Bonus** increases nightly, ensuring the threat grows in intensity over time.
* **Corrupted Relays**: Introduction of relay nodes that, if left corrupted, impose a severe **town-wide search penalty**. Disabling them requires 2 AP and coordinated effort.
* **Town Sieges**: Active defense is now mandatory. If a horde reaches the base, its strength is tested against the town's built defenses at Midnight.
* **Combat Skill Tree**: New specializations added: **[[Skills/weapon_maintenance|Weapon Maintenance]]**, **[[Skills/sweeping_strikes|Sweeping Strikes]]**, and **[[Skills/critical_hits|Critical Hits]]**.
* **Weaponized Items**: Industrial items like **[[Items/Unknown/alloy_plate|Alloy Plates]]** and **[[Items/Unknown/rusty_tool|Rusty Tools]]** can now be used as improvised weapons with unique damage and break stats.

---
