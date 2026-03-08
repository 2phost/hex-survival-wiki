# Base: Management & Bank

Management of the town's collective assets is performed through a specialized interface accessible only at the Base.

## The "Enter Base" Menu
When a player is standing on the **[[base/overview|Base]]** hex, a context-sensitive **"Enter Base"** button appears on the main bottom menu. 
- **Purpose**: This menu provides access to the Town Bank, the Refueling system, and the Base Construction project list.

## 1. Town Resources (The Bank)
The Bank is a shared inventory system that allows all survivors in a town to contribute to collective goals.
- **Function**: Items deposited here are available for base construction projects and refueling.
- **Depositing**: Clicking items in your personal inventory while in the Base menu moves them to the Bank.
- **Withdrawing**: Players can withdraw items from the Bank into their limited **[[mechanisms/inventory_management|Personal Inventory]]**.
- **Collaboration**: Banking materials like **Timber**, **Stone**, and **Scrap Metal** is essential for building critical infrastructure like the **[[base/constructions|Watchtower]]**.

## 2. Town Status & Refueling
The top of the Base menu displays the town's current survival status via the **Light & Survival Bar**.

### Refueling Mechanics
When fuel items are in the **Town Bank**, a **"Refuel"** button appears in the Base menu.
- **Skill Requirement**: Requires the **[[mechanisms/skills|Generator Operations]]** skill.
- **Execution**: Clicking "Refuel" consumes the item from the Bank and restores town power immediately.
- **Fuel Efficiency**:
    - **[[items/gasoline_canister|Gasoline Canister]]**: +25% Power (Lvl 1).
    - **[[items/biofuel_cell|Biofuel Cell]]**: +40% Power (Lvl 2).
    - **[[items/plasma_fuel_rod|Plasma Fuel Rod]]**: +60% Power (Lvl 3).

## 3. Power Consumption
The Base menu also displays **"Night Use"**, which indicates the predicted town-wide power drain during the **[[mechanisms/midnight_cycle|Midnight]]** transition. This drain is increased by expansion of the grid and active **[[mechanisms/facility_fabrication|Fabrication]]** projects (+20% each). Keeping the town's power level above this number is the primary survival objective. **If town power hits 0%, the town instance ends.**
