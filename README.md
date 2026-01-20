# 🎥 Real-Time Motion Detection using OpenCV

A real-time computer vision application that detects motion through a webcam using **frame differencing** and **contour analysis**.  
The system highlights motion regions, displays alerts, and automatically saves frames when significant motion is detected.

---

## 🔍 Key Features
- 🎥 Live webcam-based motion detection
- 🧠 Frame differencing using grayscale images
- 📦 Motion region detection using contour analysis
- 🟥 Bounding boxes around detected motion areas
- 💾 Automatic frame capture on motion detection
- ⚡ Lightweight and real-time processing

---

## 🛠️ Tech Stack
- **Python**
- **OpenCV**
- **Computer Vision**

---

## ⚙️ How It Works
1. Captures live frames from the webcam.
2. Converts frames to grayscale for faster processing.
3. Stores a sliding window of frames separated by a fixed gap.
4. Computes absolute difference between older and current frames.
5. Applies thresholding and contour detection to identify motion.
6. Draws bounding boxes and saves frames when motion is detected.

---

## ▶️ How to Run
```bash
pip install opencv-python
