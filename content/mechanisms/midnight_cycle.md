# Mechanism: Midnight Cycle

The **Midnight Cycle** is the heartbeat of Hex Survival, triggering resource consumption, production, and the defensive siege.

## 1. The Real-Time Clock
Hex Survival operates on a real-time 24-hour countdown.
- **Midnight Transition**: When the countdown reaches zero, the day transitions, and the town's survival state is calculated.

## 2. Survival Toll
At the transition, all active players suffer a significant reduction in their **[[vitals/index|Vitals]]**:
- **[[vitals/hunger|Hunger]]**: -40%.
- **[[vitals/thirst|Thirst]]**: -40%.
- **Lamp Expiration**: If a mobile light source (like a **[[items/starter_lamp|Starter Lamp]]**) reaches 0 days during this transition while the player is in darkness, their **[[vitals/fear|Fear]]** will begin to rise rapidly. If the Fear meter fills completely (3 bars), they are **"Consumed by Darkness."**

## 3. Town Power Drain
The town's total energy reserve is reduced based on:
- **Base Consumption**: Passive drain for the Base tile.
- **[[mechanisms/power_grid|Power Grid]] Size**: Each active **[[items/power_pole|Power Pole]]** adds to the daily drain.
- **Offsets**: **[[base/upgrades|Solar Panels]]** reduce this total drain by 10%.

## 4. Resource Production
Automated facilities produce resources at this point:
- **[[base/constructions|Well]]**: Produces 10 water.
- **[[base/constructions|Hydroponic Patch]]**: Produces rations and salad.
- **Facility Production**: Industrial Zone or Electronic Store - Lab components are added to the Bank.

## 5. The Nightly Siege
Midnight triggers a defensive phase where enemies attempt to breach the town perimeter. (Exact breach consequences are being verified; see [[mechanisms/inferred_mechanics|Inferred Mechanics]]).
- **Defense**: **[[base/constructions|Automated Sentries]]** and bulkheads activate to protect the town.
