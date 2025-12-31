# Unreal Engine 5: Lab Level Design
**University Year 1 | Semester 1 | Game Creation (Assessment 2)**

A first-person horror experience set within an abandoned laboratory, engineered to balance technical systems with atmospheric level design. This project focuses on resource management, interactive physics puzzles, and AI-driven tension.

> **[🔗 View the full technical breakdown on my Portfolio](https://sites.google.com/view/myles-coleman/projects/unreal-engine-level-design)**

## 📺 Video Showcase
[![The Lab: Level Design Showcase](https://img.youtube.com/vi/ljJ7hkl3i04&t=5s/0.jpg)](https://www.youtube.com/watch?v=ljJ7hkl3i04&t=5s)
*Click the image above to view the gameplay walkthrough, featuring the flashlight mechanics and AI encounters.*

## 🕹️ Project Overview
"The Lab" provides a curated horror experience where the environment serves as both a hazard and a guide. Developed with total creative freedom, the project highlights the integration of custom Visual Scripting (Blueprints) and modular 3D assets to create a cohesive, high-stakes atmosphere.

## 🛠️ Key Technical Features

### Resource & Material Systems
* **Dynamic Flashlight Mechanics:** Implemented a toggleable flashlight system with limited battery life. The battery passively regenerates when deactivated, forcing strategic resource management.
* **Advanced Material Management:** Visualised battery depletion directly on the torch model using a **Dynamic Material Instance**, transitioning the texture from yellow to black in real-time.

### Gameplay & Level Logic
* **Physics-Based Puzzles:** Designed environmental puzzles requiring the player to manipulate physics actors (crates) to access elevated areas like air ducts.
* **AI & Combat:** Developed enemy AI utilising Unreal’s **NavMesh System**. Enemies chase the player upon detection and deal progressive damage. Players can defend themselves with close-range combat (R), with defeated enemies dropping life-syringes.
* **Hazards & Health:** Implemented electrified water hazards and a dynamic HUD health bar. Reaching zero health triggers a level restart, with health restored via collectible syringes.
* **Character Controller:** Modified a custom controller to support more complex mechanics, including crouching logic that dynamically adjusts the player's hitbox and movement speed.

### Level Design Strategy
* **Intuitive Guidance:** Used lighting and environmental geometry to narrow player choices and guide them toward objectives without explicit markers.
* **Mechanical Foreshadowing:** Introduced hazards (electrified water) and items in safe zones early in the level to teach mechanics before high-tension encounters.

## 🎨 Asset Pipeline
* **Modular Environments:** Modelled a suite of modular assets in **Autodesk Maya**, including padded walls, desks, air ducts, and medical props (syringes).
* **Texture Workflow:** Reused and adapted textures created in **Substance 3D**, including a custom glossy glass texture and environment-specific materials.

## 💻 Technical Specs
* **Engine:** Unreal Engine 5
* **Language:** Blueprint Visual Scripting
* **Core Systems:** UMG (HUD), AI Navigation (NavMesh), Event-Driven Logic
* **Tools:** Maya, Adobe Substance 3D Painter, GitHub, Trello
