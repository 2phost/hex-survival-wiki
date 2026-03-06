# Project Mandate: Hex Survival Documentation

This file serves as the persistent memory for Gemini CLI regarding the Hex Survival project.

## Core Responsibilities
1. **Synchronize Context:** Always read this file and relevant subdirectories at the start of a session (or use `/init`).
2. **Update Files:** Ensure all documentation (mechanisms, reviews, ideas, bugs) is kept up-to-date following every interaction (or use `/update`).
3. **Strict Data Separation**: Ensure a clear distinction between **Confirmed** mechanics and **Inferred** logic. Move all hypothetical data to `mechanisms/inferred_mechanics.md`.
4. **Markdown Format:** Maintain a clean, consistent Markdown structure for all project files.
5. **Community Wiki Sync:** Maintain the `hex-survival-wiki` Quartz repository, ensuring it stays physically synchronized with this project's content in the `content/` folder.

## Project Context
- **URL:** https://hex-survival.onrender.com/
- **Wiki URL:** https://2phost.github.io/hex-survival-wiki/
- **Current State:** Comprehensive documentation of a collaborative, persistent-world survival game. The primary existential threat is 'The Darkness'.
- **Key Themes**: Power Grid Strategy (Loot Highways), Collaborative Logistics (Town Bank), Real-Time Skill Specialization, and Light-based Exploration (0-hex radius poles).

## Guidelines
- Extract and document core mechanics: exploration, vitals, AP costs, crafting, infrastructure, and base constructions.
- Focus specifically on the "Light vs. Darkness" loop, power management, skill progressions, and collaborative base building.
- Track bugs (e.g., Item Overlay) with reproduction steps.
- Maintain a "Verification List" of confirmed vs. to-be-tested mechanics.
- Use **Deep-Linking Strategy** ([[path|Title]]) in all Markdown files to ensure full Graph View functionality in the Quartz wiki.

## Custom Commands
- `/init`: Synchronize internal context with the current project state at the start of a session.
- `/update`: Perform a multi-phase synchronization of all documentation to ensure consistency.
- `/end`: Synthesize session discoveries, update context, and optimize commands.
