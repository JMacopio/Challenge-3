# Challenge 3 – Balloons, Bombs, & Booleans

A Unity challenge where a balloon floats through town, collecting tokens while avoiding explosives. This project was built as part of the **Create with Code** curriculum, applying knowledge of physics, scrolling backgrounds, and special effects while practicing troubleshooting skills to fix a project riddled with errors.

## 🎮 Game Overview

You control a balloon that floats upward through a scrolling town. Your goal is to **collect Money tokens** while **avoiding Bombs**. The game tests your reflexes and timing as you navigate through the sky. The challenge also emphasizes debugging skills—the project is intentionally filled with errors that need to be identified and fixed.

This challenge demonstrates:
- **Physics-based movement** – Using Unity physics for balloon float mechanics
- **Scrolling backgrounds** – Seamless repeating backgrounds to simulate movement
- **Special effects** – Particles and sound effects for collisions
- **Boolean logic** – Controlling game states and conditions
- **Troubleshooting** – Identifying and fixing errors in a pre-built project

## ✨ Key Features

- **Balloon Float Mechanics** – Hold the **Spacebar** to make the balloon float upward.
- **Seamless Background** – The background repeats endlessly, simulating the balloon's movement through town.
- **Random Spawning** – Bombs and Money tokens spawn randomly on a timer.
- **Money Collection** – Colliding with Money triggers a particle effect and sound effect.
- **Bomb Explosion** – Colliding with a Bomb triggers an explosion, and the background stops moving.
- **Troubleshooting Focus** – The project is intentionally filled with errors, making it a great debugging exercise.

## 🛠️ Technologies Used

- **Unity Editor** – Game engine and development environment.
- **C#** – All game logic, including movement, spawning, and collision handling.
- **Unity Physics** – For balloon movement and collision detection.
- **Unity Audio System** – For sound effects on collisions.
- **Unity Particle System** – For visual effects on Money collection and Bomb explosions.

## 🚀 Getting Started

### Prerequisites

- Unity Hub with Unity Editor installed (any recent version).
- Git (optional, for cloning).

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/JMacopio/Challenge-3.git
   ```
2. Open Unity Hub, click **Add**, and select the cloned project folder.
3. Once the project loads, navigate to `Assets/Scenes/` and open the main scene.
4. Press the **Play** button in the Editor to start the challenge.

## 🎮 How To Play

1. **Float the Balloon** – Hold the **Spacebar** to make the balloon float upward through the town.
2. **Collect Money** – Fly into the Money tokens to collect them. Each collection triggers a particle effect and sound.
3. **Avoid Bombs** – Stay away from the Bombs! Colliding with one triggers an explosion and stops the background.
4. **Survive** – Keep collecting Money while dodging Bombs for as long as you can.
5. **Debug** – If something isn't working, the project is intentionally filled with errors—find and fix them!

## 📁 Project Structure

```plaintext
Challenge-3/
├── Assets/
│   ├── Scenes/               – The main game scene
│   ├── Scripts/              – All C# logic
│   │   ├── PlayerController.cs – Handles balloon movement (float up with Spacebar)
│   │   ├── SpawnManager.cs   – Controls random spawning of Bombs and Money
│   │   ├── BackgroundManager.cs – Manages seamless scrolling backgrounds
│   │   ├── Collectible.cs    – Handles Money collection (particles, sound)
│   │   ├── Bomb.cs           – Handles Bomb collisions (explosion, background stop)
│   │   └── (other scripts)   – Additional logic as needed
│   ├── Prefabs/              – Reusable objects (balloon, bombs, money)
│   ├── Audio/                – Sound effect files
│   ├── Particles/            – Particle system prefabs
│   └── ...
├── Packages/                 – Unity dependency manifests
├── ProjectSettings/          – Editor and player settings
└── README.md
```

## 🧠 What I Learned

- Applying **physics-based movement** to create smooth, realistic balloon float mechanics.
- Implementing **seamless scrolling backgrounds** to simulate endless movement.
- Using **random spawning** on a timer to create dynamic gameplay.
- Adding **particle effects** and **sound effects** for collision feedback.
- Using **boolean logic** to control game states (e.g., background moving/stopped).
- **Troubleshooting** and debugging a project filled with intentional errors.

## 🤝 Contributing

This is a coursework challenge, but feel free to fork it, experiment, and submit pull requests with improvements or new features.

## 📄 License

All rights reserved. For educational use only – please contact the author for permissions beyond personal learning.

## 👨‍💻 Author

**Jorge Matthew Acopio** ([JMacopio](https://github.com/JMacopio))

---

*Built in May 2026 as part of the Create with Code Unity course – Challenge 3: Balloons, Bombs, & Booleans.*
```
