# Squatty Dino 🦖 🏋️‍♂️

An experimental, open-source browser game controlled entirely by your physical body movements using computer vision. Turn your webcam into a fitness controller!

No backend, no installations, no data collection. Everything runs locally in your browser.

## 🎮 How to Play
1. Open the [https://brmnkw.github.io/Squad_Bird/].
2. Allow camera access (required for AI tracking).
3. Step back so your entire body is visible.
4. **Stand Tall** to lock in your calibration.
5. **Stand/Jump** to clear low obstacles.
6. **Squat Down** to dodge high obstacles.

## 🛠 Tech Stack
* **HTML5 Canvas** for rendering the Chrome-style minimal graphics.
* **JavaScript** for game logic.
* **TensorFlow.js & MoveNet** (`@tensorflow-models/pose-detection`) for lightning-fast, real-time pose estimation.
* **Web Speech API** for hands-free audio coaching.

## 🔒 Privacy First
This app respects your privacy. The video feed is processed 100% locally on your device via your GPU/CPU. **No video or image data is ever saved, recorded, or sent to any server.**

## ⚠️ Disclaimer
**Use at your own risk.** This game requires physical exertion (squatting and jumping). Ensure you are in a safe environment with enough space to move. The creator of this software is not a medical professional and is not responsible for any physical injuries, property damage, or hardware issues that may occur while playing this game. Please stretch before playing!

## 📄 License
This project is open-source and available under the [MIT License](https://github.com/BRMNKW/Squad_Bird/blob/main/MIT%20License). Feel free to fork, modify, and build upon it!
