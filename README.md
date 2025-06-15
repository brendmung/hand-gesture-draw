# 🎨 Gesture Drawing Studio

**Draw with your hands in the air!** A personal exploration of computer vision and gesture recognition using MediaPipe and TensorFlow.js.

🌐 **[Try it live: hand-gesture-draw.vercel.app](https://hand-gesture-draw.vercel.app)**

![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands-blue)
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-4.2.0-orange)
![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-yellow)

## 🎯 What This Demonstrates

This project showcases how modern web technologies can create intuitive, gesture-based interactions:

- **Computer Vision in Browser** - Real-time hand tracking with MediaPipe
- **Gesture Recognition** - Custom algorithms to detect hand poses
- **Canvas Drawing** - Smooth, responsive drawing with HTML5 Canvas
- **No Backend Required** - Pure client-side implementation

## ✨ Gesture Controls

- **👉 Point** - Draw with index finger
- **🖐️ Open Hand** - Erase mode
- **✊ Fist** - Move cursor without drawing  
- **✌️ Peace Sign** - Navigate mode
- **👍👎 Thumbs Up/Down** - Adjust brush size

## 🛠️ Built With

- **MediaPipe Hands** - Hand landmark detection
- **TensorFlow.js** - ML framework for gesture classification
- **HTML5 Canvas** - Drawing surface
- **Vanilla JavaScript** - No frameworks, pure JS implementation
- **WebRTC** - Camera access

## 🚀 Try It

**Online:** Visit [hand-gesture-draw.vercel.app](https://hand-gesture-draw.vercel.app)

**Locally:**
1. Clone this repository
2. Open `index.html` in a modern browser
3. Allow camera permissions
4. Hold your hand 12-18 inches from camera
5. Start drawing with gestures!

## 💡 Technical Highlights

**Gesture Recognition Pipeline:**
- Hand landmark detection using MediaPipe
- Custom finger extension algorithms
- Gesture smoothing and confidence filtering
- Real-time drawing state management

**Performance Optimizations:**
- Gesture buffering to reduce noise
- Movement thresholds for smooth lines
- Efficient canvas operations
- Error handling and recovery

## 🎨 Features

- 8 color palette
- Adjustable brush sizes (2-20px)
- Download artwork as PNG
- Responsive design
- Real-time visual feedback

---

*A demonstration of how computer vision can create natural, intuitive interfaces for creative applications.*
