# Tactical TTT Framework (Roblox/Luau)

This repository contains the core logic and systems for a "Trouble in Terrorist Town" (TTT) remake developed within Roblox Studio using **Luau**. The project focuses on complex state management, server-side authority, and modular gameplay systems.

## 🚀 Key Features

* **Advanced Round System:** A centralized server-side handler managing the full match lifecycle (Lobby, Preparation, Active Round, and Cleanup).
* **Dynamic Role Distribution:** Secure logic to assign secret roles (Traitor, Innocent, Detective) to players at the start of each match.
* **Server-Side Combat:** Projectile and damage logic handled on the server to ensure game integrity and prevent exploitation.
* **Modular Weapon Framework:** A system designed for easy integration of unique hero abilities and different weapon types.
* **AI Integration:** Includes logic for [hier kurz ergänzen, z.B.: "NPC pathfinding and basic decision making"], reflecting my interest in Artificial Intelligence within game environments.

## 📂 Code Highlights

Since some scripts are quite extensive, here are the most important files to review:

1.  **`RoundSystem.luau`**: The heart of the game. It uses a state-machine approach to handle all round transitions and win conditions.
2.  **`ShootServer.luau`**: Demonstrates my understanding of networked communication and server-side validation.
3.  **`WeaponHandler.luau`**: Shows how I structure modular systems to allow for hero-based gameplay variety.

## 🛠️ Technologies Used
* **Language:** Luau (Roblox's optimized version of Lua)
* **Environment:** Roblox Studio / Engine API
* **Focus:** Game Logic, State Management, Multiplayer Networking
