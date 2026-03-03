# Hex Survival Documentation Project

This project tracks reviews, ideas, mechanisms, and bugs for the game [Hex Survival](https://hex-survival.onrender.com/). Hex Survival is a collaborative, persistent-world survival game where players work together in hexagonal "towns" to survive the existential threat of "The Darkness."

## Project Structure
- **[[mechanisms/verification_list|Mechanisms]]**: Technical and gameplay rules.
  - *Core*: [[mechanisms/light_and_darkness|Light and Darkness]], [[mechanisms/action_points|Action Points]], [[mechanisms/infrastructure|Infrastructure]], [[mechanisms/scavenging|Scavenging]].
  - *Data*: [[mechanisms/items|Items]], [[mechanisms/crafting_and_recipes.md|Crafting & Recipes]], [[mechanisms/world_and_tiles|World & Tiles]].
  - *Tracking*: [[mechanisms/verification_list|Verification List (Testing)]], [[mechanisms/inferred_mechanics|Inferred Mechanics]].
- **[[guides/getting_started|Guides]]**: Player manuals and tutorials.
  - *Featured*: [[guides/getting_started|Getting Started Guide]].
- **[[ideas/strategic_suggestions|Ideas & Strategies]]**: Strategic suggestions and developer feedback.
  - *Featured*: [[ideas/strategic_suggestions|Strategic Suggestions]], [[ideas/dev_feedback_suggestions|Dev Feedback]].
- **[[bugs/item_overlay|Bug Tracking]]**: Reported issues and reproduction steps.
  - *Current*: [[bugs/item_overlay|Item Overlay Bug]].
- **`reviews/`**: Critical analysis and user feedback.
- **`tools/`** and **`.gemini/commands/`**: Automation scripts and custom CLI commands (`/init`, `/update`, `/end`).

## Project Goals
1. **Mechanism Clarification**: Document all confirmed game rules, including skill progressions (Lvl 1=1h, Lvl 5=30d), base infrastructure (0-radius light range), and objective prerequisites.
2. **Data-Driven Strategy**: Formulate optimal playstyles based on exact loot weights (e.g., Farm Facility Rations 90%) and efficient Power Grid growth.
3. **Tracking & Verification**: Maintain a live list of confirmed vs. unverified mechanics to assist the community.
4. **Knowledge Sharing**: Provide clear, accessible guides and a synchronized Wiki for both new and veteran players.

## Core Themes
- **Light vs. Darkness**: The primary existential threat requires constant grid management and lamp awareness.
- **Collaborative Logistics**: Banking resources and specialized roles are mandatory for survival.
- **Real-Time Specialization**: Skills take days/weeks to train, forcing players to choose distinct professions.
- **Infrastructure Strategy**: Constructing Base builds like the Watchtower and Signal Booster is critical for discovery.

## Mandate for Gemini CLI
Every time a new session starts, read `GEMINI.md` and the latest files in this repository to stay updated on the project's state. Keep all files updated after each interaction.
