# 🥊 Gesture-Controlled Boxing Game

A fun and interactive Python project where you control a boxing game using real-time hand and face gestures via your webcam.

## 🎮 What It Does
- Detects left/right punches, uppercuts, and blocking motions using your hands.
- Translates gestures into keyboard inputs using PyAutoGUI.
- Works seamlessly with a browser-based boxing game.

🎮 Features
🎥 Real-time hand and face tracking using MediaPipe
✊ Detects left/right punches based on wrist velocity
👊 Uppercut detection when hands are raised above face
🛡️ Blocking gesture detection when both hands near face
🕹️ Simulates keyboard inputs using PyAutoGUI
🧠 Intuitive gesture-based game interaction
🌐 Opens and plays directly in a browser window

## 📸 Demo

Watch the full demo: [https://www.linkedin.com/posts/deepak-m-bbb0b7278_gesture-controlled-boxing-game-team-activity-7324104541417672704-qCfX?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEOlcP8BElzOBcCgmU2vOmM65SL9B0avD3M]

## 🧰 Tech Stack
- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- Webbrowser module

  🧪 Key Concepts Used
Landmark-based wrist tracking
Euclidean distance and velocity thresholding
Face box overlay for gesture comparison
Keystroke emulation for game interaction
Time-based cooldowns to avoid repeat triggers

