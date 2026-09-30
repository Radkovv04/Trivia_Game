# Trivia Conquest: Legacy Alpha

Welcome to the Alpha version of our historic/geopolitics trivia game. This repository serves as the stable baseline of the project—originally conceived as a university project—before its transition into a fully-fledged Live Service mobile game.

## 📌 About This Version
This branch represents the core engine and mechanics of the game in its initial phase. It features a robust matchmaking system, custom UI elements, and a functioning database architecture for competitive trivia.

## 🚀 Current Features
*   **Ranked & Normal Modes:** ELO-based matchmaking for competitive play and casual lobbies for practice.
*   **Immersive UI:** Full-screen portrait mode with custom-built layouts (Action Bar removed for a clean, historic aesthetic).
*   **Dynamic Question Difficulty:** System allows toggling question difficulty (Currently tied to user settings, migrating to ELO-based dynamic scaling).
*   **Firebase Integration:** Real-time database operations for matchmaking, user profiles, and score tracking.

## 🛠 Tech Stack
*   **Platform:** Android (Java/Kotlin)
*   **Backend:** Firebase Realtime Database / Authentication
*   **Architecture:** Standard Android Activities (Pre-refactoring)

## 🗺 What's Next (The V2 Roadmap)
This codebase is currently undergoing a massive structural refactoring to support modern mobile gaming standards. Upcoming features in the main development branch include:
*   **Modern Navigation:** Migration to a `BottomNavigationView` with Fragment-based architecture.
*   **Guild System (Дружини):** Clan mechanics where players farm resources ("Bricks") via active play to build and upgrade their Citadel.
*   **Live Service Economy:** Introduction of a Battle Pass, dual-currency system (Silver/Gold), and seasonal resets (Hall of Fame).
*   **Territory Conquest Mode:** A hex-based global map where guilds battle for regions via asynchronous trivia sieges.
*   **Room Codes:** Custom lobby generation for direct friend challenges and streamer integration.

---
*Note: Due to security reasons, `google-services.json` is excluded from this repository. To run this project locally, you must provide your own Firebase configuration file.*
