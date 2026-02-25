# Squat Break 🍅🏋️‍♂️

**Squat Break** is an open-source productivity and health utility that forces you to take active screen breaks. It combines a Pomodoro focus timer with a computer-vision-powered fitness game. 

When your focus time is up, the only way to silence the alarm and get back to work is to physically stand up and complete a set of squats by playing a body-controlled arcade game.

## ✨ Features
* **Battery & Privacy Optimized:** The camera remains completely **OFF** while the timer runs. It only turns on when it's time for your break.
* **Custom Intervals:** Choose your focus time (15, 25, 45, or 60 minutes).
* **Adjustable Workouts:** Set your squat goal for the break (5, 10, 20, or 50 reps).
* **AI Body Tracking:** Uses advanced pose-estimation to track your movements in real-time. Stand up to make your character jump; squat down to duck.
* **100% Client-Side:** No backend, no accounts, and absolutely no data collection. Everything runs locally in your browser.

## 🎮 How to Use
1. [Open the app](https://brmnkw.github.io/Squad_Bird/).
2. Select your Focus Time and your Squat Goal.
3. Click **Start Focus Timer** and get to work!
4. When the alarm sounds, the camera will activate. Step back so your full body is visible.
5. **Stand Tall and Freeze** for 2.5 seconds to calibrate your height.
6. Dodge the falling pipes by squatting and standing until you reach your goal!

## 🛠 Tech Stack
* **HTML/CSS/JS:** Built in a single, lightweight file.
* **TensorFlow.js & MoveNet:** (`@tensorflow-models/pose-detection`) for lightning-fast, highly accurate pose estimation directly in the browser.
* **Web Speech API:** Provides hands-free audio coaching and score-reading.
* **HTML5 Canvas:** For rendering the minimal, high-contrast game graphics.

## 🔒 Privacy Guarantee
This application respects your privacy by design. The video feed is processed 100% locally on your device via your GPU/CPU. **No video, image, or tracking data is ever saved, recorded, or transmitted to any server.** ## ⚠️ Health & Safety Disclaimer
**Use at your own risk.** This game requires physical exertion. Ensure you are in a safe, clear environment with enough space to move. The creator of this software is not a medical professional and is not responsible for any physical injuries, property damage, or hardware issues that may occur while using this app. Please stretch, listen to your body, and do not push beyond your physical limits!

## 📄 License
This project is open-source and available under the [MIT License](https://github.com/BRMNKW/Squad_Bird/blob/main/MIT%20License). Feel free to fork, modify, and build upon it to create your own fitness utilities!
