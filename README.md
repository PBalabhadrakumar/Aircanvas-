# ✨ Air Canvas – Draw in the Air with Your Finger ✨

Air Canvas is an AI-based virtual drawing tool that lets users draw on screen by waving their **index finger** in the air—no physical touch or stylus required. This interactive system uses **OpenCV** and **MediaPipe** for real-time hand tracking and gesture recognition, enabling a smooth and fun drawing experience.

---

## 🧠 Features

- Draw in the air using your **index finger**
- Real-time hand and finger detection
- Gesture-controlled color selection (Blue, Green, Red, Yellow)
- "Clear Canvas" option using gestures
- Tracks finger movement and draws on both canvas and live video feed

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **MediaPipe**
- **NumPy**

---

## 🚀 How It Works

1. **MediaPipe Hands** detects the user's hand and landmarks in real-time.
2. It tracks the position of the **index fingertip** to draw on the canvas.
3. Touching the top bar area triggers actions like:
   - Color selection
   - Clearing the canvas
4. Lifting the thumb signals to stop drawing (gesture detection).

---

## 📸 UI Components

- 🖼️ Top menu bar:
  - CLEAR | BLUE | GREEN | RED | YELLOW
- 🖐️ Draw by pointing your **index finger**
- 🎨 Drawing appears both on webcam feed and a separate canvas

---

## 🖥️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/air-canvas.git
   cd air-canvas
