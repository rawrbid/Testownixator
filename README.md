
# Testownixator!! || QuizBattler ⚔️

> An interactive, gamified study application that transforms tedious exam question drilling into animated battle encounters.

[![Play on Itch.io](https://img.shields.io/badge/Itch.io-Download_App-FF0B3A?style=for-the-badge&logo=itch.io&logoColor=white)](https://polarbread.itch.io/quizator)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)](https://polarbread.itch.io/quizator)

<p align="center">
  <img src="assets/menu.png" width="32%" alt="Main Menu" />
  <img src="assets/gameplay.png" width="32%" alt="Gameplay & Combat" />
  <img src="assets/mod_editor.png" width="32%" alt="Character & Mod Editor" />
</p>

---

## 📌 Overview

**Testownixator!! || QuizBattler** is a desktop study application designed to combat study fatigue during exam preparation. Instead of traditional static flashcards, the app embeds typical study workflows into animated battle encounters.

Built with user experience and customization in mind, the application supports legacy question bank formats, custom user mods, and intuitive desktop window controls.

---

## ✨ Key Features

### 🎮 Gamified Exam Drilling
* **Combat-Driven Learning:** Questions power real-time battle interactions. Correct answers trigger character action animations and sound effects, turning exam sets into boss fights.
* **Custom Character & Asset Modding:** Mod support allowing users to load custom sprites and soundpacks for opponents and player characters.

### 📄 Interoperability & File Support
* **Testownik Compatibility:** Native parser support for modern JSON formats as well as legacy **Testownik** files, ensuring zero migration friction for existing question banks.
* **In-App Quiz Creator & Importer:** Built-in editor to create, edit, or import text-based flashcard sets and share them with peers.

### 💻 Custom UX & Window Management
* **Linux-Style Window Control:** Implements ***Alt + Middle-Mouse / Right-Mouse*** drag-and-resize mechanics directly within the application viewport for fast workspace adjustments.

---

## 🚀 Quick Start & Download

1. Download the latest build from the **[Itch.io Release Page](https://polarbread.itch.io/quizator)**.
2. Extract the `.zip` archive to your preferred location.
3. Launch `Quizator.exe`.

> ℹ️ **Windows Defender / SmartScreen Notice:**  
> Because this application is independently built and lacks an expensive Code Signing Certificate, Windows SmartScreen may display an *"Unknown Publisher"* warning on initial launch.  
> * To run: Click **More Info** ➔ **Run Anyway**.  
> * Feel free to inspect or scan the executable before running.

---

## 🛠️ Architecture & Modding

The project follows a modular structure decoupling question state management from the rendering engine:

* **Parser Engine:** Handles data serialization/deserialization across custom JSON schemes and legacy Testownik file structures.
* **Asset & Character System:** Features an in-app character creator along with a dynamic asset loading pipeline supporting `.png` graphics, `.mp3` / `.ogg` audio files, and modular sprite configuration.
* **Battle Controller:** Animates characters and plays sounds after the user answers a question.
* **Custom Window Input Handler:** Intercepts mouse events to provide Linux-like window dragging and resizing without relying on default OS borders.

---

## ⚖️ Disclaimer & Compliance

This software is an independent study tool. User-created content, uploaded question banks, and custom visual mods are the sole responsibility of the individual user. Please ensure all question sets and custom characters comply with local academic integrity standards and copyright laws.
