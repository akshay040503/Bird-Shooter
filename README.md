# 🐦 Bird Shooter — Hand Tracking Arcade Game

An interactive, AI-powered web game where your hand is the controller. Aim with your finger and pinch to shoot!

---

## 🚀 Overview

Bird Shooter is a modern take on classic arcade shooters, built entirely with web technologies. It uses **MediaPipe's Hand Tracking** to detect user gestures through a webcam, providing a "kinect-like" experience without the need for specialized hardware.

## ✨ Features

* **AI Hand Tracking:** Real-time gesture recognition (pointing to aim, pinching to shoot).
* **Dynamic Difficulty:** Leveling system that increases bird speed and frequency.
* **Combo System:** Multiply your score by hitting consecutive targets.
* **Retro-Modern Aesthetic:** Smooth HTML5 Canvas animations with a dark, starry atmosphere.
* **Responsive HUD:** Real-time score tracking, life bars, and level progression.
* **Zero Install:** Runs directly in the browser using CDN-hosted MediaPipe models.

## 🛠️ Tech Stack

* **HTML5 & CSS3:** For game structure and high-end UI styling.
* **JavaScript (ES6):** Core game engine and logic.
* **[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands):** For real-time hand landmark detection.
* **Canvas API:** For high-performance 2D rendering.

## 🎮 How to Play

1.  **Allow Camera Access:** When prompted, give the browser permission to use your webcam.
2.  **Aim:** Point your index finger at the screen. A glowing crosshair will follow your fingertip.
3.  **Shoot:** Quickly pinch your thumb and index finger together to fire.
4.  **Objective:** Hit the birds to score points. Don't let them fly across the screen, or you'll lose a life!
5.  **Combos:** Hit multiple birds in short succession to trigger score multipliers.

## 📦 Installation & Usage

Since this is a standalone HTML file, no complex installation is required:

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/bird-shooter.git](https://github.com/YOUR_USERNAME/bird-shooter.git)
    ```
2.  Navigate to the folder:
    ```bash
    cd bird-shooter
    ```
3.  Open `index.html` in any modern web browser (Chrome or Edge recommended for best MediaPipe performance).

> **Note:** A stable internet connection is required to load the MediaPipe AI models from the CDN.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
