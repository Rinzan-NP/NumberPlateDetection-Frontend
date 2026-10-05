# 🚗 AuraPlate ANPR Frontend (React + Tailwind CSS)

[![React](https://img.shields.io/badge/React-19.2-blue.svg)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.4-646CFF.svg)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38B2AC.svg)](https://tailwindcss.com/)
[![Theme](https://img.shields.io/badge/Theme-Light%20Modern-brightgreen.svg)]()

> **The official web dashboard for AuraPlate ANPR. Features a clean, high-contrast light theme, visual inspection mode switcher (Bounding Box vs. Neural Heatmap vs. Side-by-Side), and realistic Indian High Security Registration Plate (HSRP) badges.**

---

## ✨ Features

- 🎨 **Modern Light Theme**: Clean white panels, soft shadows, and emerald accents designed for high-contrast presentation and readability.
- ⚡ **1-Click Vehicle Presets**: Instant testing with pre-loaded cars, tempos, and auto-rickshaws.
- 🔄 **Visual Mode Switcher**:
  - 🎯 **Bounding Box Mode**: Visualizes YOLOv8 localization rectangle and detection confidence.
  - 🔥 **Neural Heatmap Mode**: Overlays the 2D spatial Gaussian attention energy map (JET colormap).
  - 🔀 **Side-by-Side Mode**: Compares the detection box alongside the neural attention heatmap.
- 🇮🇳 **Realistic HSRP Badge**: Recreates the physical Indian registration plate with embossed blue `IND` international code, Ashok Chakra circle, and stamped typography.
- 🔬 **Dedicated Heatmap Tab**: Step-by-step visual walkthrough explaining how convolutional feature pyramids and character saliency function.
- ⚙️ **Dataset & Training Hub**: Live telemetry tracker displaying real-time epoch progress, training loss, mAP@50, and precision.

---

## 🚀 Getting Started

### 1. Prerequisites
- Node.js (v18+)
- npm or yarn

### 2. Installation
```bash
# Clone the repository
git clone https://github.com/Rinzan-NP/Frontend.git
cd Frontend

# Install dependencies
npm install
```

### 3. Run Development Server
```bash
npm run dev
# Dashboard opens on http://localhost:5174
```

> **Note:** The Vite configuration proxies `/api` requests automatically to the backend on `http://localhost:8000`. Ensure the backend server is running!

---

## 📜 License

MIT License.
