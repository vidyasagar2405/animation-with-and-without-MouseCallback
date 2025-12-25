# Particle Orbit & Mouse-Tracking Reptile Animations using OpenCV

This repository contains two real-time animation demos built using **Python + OpenCV**.  
The goal was to explore interactive rendering, motion physics, particle systems, and kinematic chains using only OpenCV's drawing APIs.

---

## 🎆 1. Magical Orbit Animation

A particle-based orbit system rendered in real time.

### **Features**
- 100+ particles with randomized:
  - radius  
  - angle  
  - velocity  
  - color  
  - size  
- Circular orbit motion using trigonometric functions  
- Trail persistence using exponential frame decay  
- Dynamic “twinkle” color variation  
- Glowing center effect  
- Runtime text overlay  
- Automatic stop timer or `q` key exit  

### **Core Concepts Used**
- `cv2.circle()` for particle rendering  
- Motion updates: `angle += speed`  
- Frame fading: `frame = (trail * 0.92)`  
- Real-time animation loop with `cv2.imshow()`  

---

## 🐍 2. Mouse-Tracking Reptile Animation

A kinematic chain that follows the mouse pointer smoothly.

### **Features**
- Segment-based body system  
- Each segment follows the previous one using angle computation  
- Real-time mouse tracking using:
  ```python
  cv2.EVENT_MOUSEMOVE


## **Demo Video**
## [Video](https://youtu.be/jrNEF7GAPZQ)
