# 🐍 Python GUI Applications Collection

## 📖 About This Repository
This repository contains a suite of three interactive desktop applications built using **Python** and **Tkinter**. Developed as a comprehensive assessment of GUI programming, Object-Oriented design, and data management, these projects showcase advanced UI techniques including frame-by-frame GIF animation, audio integration, and full CRUD file operations.

---

## 🚀 Project 1: Mind Matrix - Space Arithmetic Quest
An interactive, animated space-exploration math game where players solve arithmetic challenges to advance ranks.
* **Animated UI:** Fully animated GIF backgrounds and glowing sci-fi interfaces using Pillow.
* **Dynamic Audio:** Background ambient music and reactive sound effects via Pygame.
* **Adaptive Gameplay:** Multiple difficulty tiers, dynamic scoring based on attempts, and a progressive ranking system.
* **Performance Tracking:** Real-time progress bars and custom end-of-mission performance reports.

## 🤖 Project 2: Alexa JokeMatrix - Animated Joke Terminal
A futuristic, glitch-themed AI terminal that simulates a "humor core booting sequence" to deliver jokes.
* **Hacker Aesthetic:** Smooth terminal animations, neon cyan text, and a custom boot-up sequence.
* **Audio & Voice:** Integrates text-to-speech (gTTS) to read jokes aloud, paired with delayed laughter sound effects.
* **Smart File Parsing:** Dynamically fetches and parses setup/punchline structures from external `.txt` files.
* **Clean State Management:** Utilizes a custom `wipe()` function to seamlessly transition between UI screens.

## 🎓 Project 3: Student Manager App - CRUD Database System
A beautifully designed student records manager that handles coursework marks, exam scores, and system analytics.
* **Full CRUD Functionality:** Add, Update, Delete, and Read student records, automatically syncing and writing to local `.txt` databases.
* **Live Search & Sort:** Real-time search filtering and multi-parameter sorting (by name, percentage, total score, etc.).
* **Automated Analytics:** Automatically computes letter grades, class averages, and identifies highest/lowest scoring students.
* **Polished UX:** Custom background images, intuitive sidebar navigation, and robust input validation.

---

## ⚙️ Shared Tech Stack
* **Language:** Python 3.x
* **GUI Framework:** Tkinter, `ttk` (Treeview)
* **Media Handling:** Pillow (PIL) for image/GIF rendering, Pygame for audio engine
* **Data Persistence:** Python OS module and native File I/O (`.txt`)
* **Architecture:** Modular Object-Oriented Programming (OOP)

## 🛠️ How to Run
1. Clone this repository to your local machine.
2. Install the required dependencies: `pip install Pillow pygame gTTS`
3. Navigate to the specific project folder (e.g., `cd Mind_Matrix`).
4. Run the main python file (e.g., `python main.py`).
