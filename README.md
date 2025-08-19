# Yeet The Slouch

[![PoseNet Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://yashjanakiram.github.io/YeetTheSlouch/)

A cutting-edge browser-based system for real-time human posture detection, powered by ml5.js PoseNet and p5.js. Using your webcam, this tool detects and visualizes body keypoints and skeletons in real-time, offering intuitive confidence feedback and a sleek, responsive user interface.

## Features

- **Live Pose Detection:** Real-time video with all 17 PoseNet keypoints and skeleton
- **Modern UI:** Sleek gradient background, custom fonts, mobile-friendly card layout
- **Live Feedback:** Detection confidence & status displayed instantly
- **Educational:** Perfect for students, teachers, fitness, AI/ML workshops & computer vision demos
- **Fully Browser-Based:** No installs, works instantly on Chrome/Edge/Firefox



## 🛠️ How It Works

- Loads PoseNet model (via ml5.js) in the browser
- Captures webcam video and runs pose estimation on each frame
- Draws keypoints (face, arms, legs, etc.) and skeleton lines
- UI adapts to detection status and confidence

## 🌐 Try It Live

[👉 Click here for the Live Demo](https://asadi18.github.io/Modern-Real-Time-Posture-Detection-System-ml5.js-p5.js-/)

## 📦 Quick Start

1. **Clone or Download:**
   ```bash
   git clone https://github.com/your-github-username/your-repo-name.git
   ```
2. **Open `index.html` in your browser** (no backend required)

3. **Allow webcam access when prompted**

## 📝 Customization

- Colors, fonts, and panel styles can be adjusted in `index.html`
- Add custom posture logic in `script.js` for fitness counters, alerts, etc.

## Tech Stack

- [ml5.js](https://ml5js.org/) (PoseNet)
- [p5.js](https://p5js.org/) (Canvas/UI)
- Vanilla HTML/CSS
---

**Star ⭐ | Fork 🍴 | PRs Welcome!**

---

_For education, research, and demo use. For commercial/medical apps, use official TensorFlow.js PoseNet for production._
