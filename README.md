# Elemental Gesture Game

## Overview

Elemental Gesture Game is an interactive computer vision project that combines hand tracking, gesture recognition, particle effects, sound effects, and real-time gameplay.

Using a webcam, the system detects hand gestures through MediaPipe and converts them into elemental powers such as Fire, Water, Lightning, and Air. Players use gestures to attack enemies, score points, and survive as long as possible.

## Features

* Real-time hand tracking using MediaPipe
* Gesture recognition using finger counting
* Four elemental powers:

  * 🔥 Fire
  * 💧 Water
  * ⚡ Lightning
  * 🌬️ Air
* Particle effects and animations
* Sound effects using Pygame
* Enemy spawning and combat system
* Health and score tracking
* Real-time gameplay using OpenCV

## Technologies Used

* Python
* OpenCV
* MediaPipe
* Pygame
* Computer Vision

## Project Structure

```text
Elemental-Gesture-Game/
│
├── main.py
├── sounds/
│   ├── fire.mp3
│   ├── water.mp3
│   ├── air.mp3
│   ├── lightning.mp3
│   └── yay.mp3
│
├── screenshots/
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

```bash
git clone <repository-url>
cd Elemental-Gesture-Game
pip install -r requirements.txt
```

## Run the Project

```bash
python main.py
```

## Controls

| Gesture              | Element     |
| -------------------- | ----------- |
| Closed Fist          | ⚡ Lightning |
| One Finger           | 🔥 Fire     |
| Two Fingers          | 💧 Water    |
| Four or More Fingers | 🌬️ Air     |

## Applications

* Computer Vision
* Gesture Recognition
* Human Computer Interaction
* Interactive Gaming
* AI-Based User Interfaces

## Future Improvements

* Boss Battles
* Multiple Levels
* Special Combo Attacks
* Gesture Training Mode
* Multiplayer Support

## Author

Tanya Singh

B.Tech CSE (AIML)
