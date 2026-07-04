# Interactive 3D Particle Lights

An interactive, GPU-accelerated 3D particle system that morphs between beautiful geometric shapes and responds dynamically to real-time hand gestures tracked through your webcam.

Built with **Three.js** for high-performance 3D rendering and **MediaPipe Hands** for web-based machine learning hand-tracking.

## ✨ Features

- **Gesture Interaction**: Hover and wave your hand in front of your camera to warp, push, and interact with the particle system.
- **Multiple 3D Particle Morph Targets**:
  - 🎆 **Fireworks**
  - 💖 **Hearts**
  - 🌸 **Flowers**
  - 🪐 **Saturn**
  - 🧘 **Buddha**
- **Dynamic Physics & Morphing**: Particles smoothly interpolate between shapes using custom easing functions.
- **Interactive UI**:
  - Sleek glassmorphism control panel.
  - Custom color picker to change the particle emitter glow on the fly.
  - Visual tracking status indicator.

## 🛠️ Built With

- **[Three.js](https://threejs.org/)** — 3D WebGL library.
- **[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)** — Machine learning framework for hand tracking.
- **HTML5 & CSS3** — Responsive glassmorphic UI.

## 🚀 Getting Started

Since this is a client-side web application, you don't need any complex build steps.

### Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/interactive-3d-particle-lights.git
   ```
2. Open `index.html` directly in your browser, or use a local development server (e.g., Live Server in VS Code, `http-server`, or Vite).
3. Grant camera permissions when prompted to enable hand tracking.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
