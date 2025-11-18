# Hand Distance Measurement using Mediapipe

This project measures the real-time distance of a detected hand from the camera using **Mediapipe Hands**, **OpenCV**, and a simple distance estimation formula.  
It also plays a warning **beep sound** when the hand gets too close (less than 20 cm).

---

## 🚀 Features
- Real-time hand detection using Mediapipe  
- Calculates approximate hand distance using palm bounding-box width  
- Visual bounding box and distance display  
- Automatic beep alarm if the hand is too close  
- Runs fully on webcam input  

---

## 📌 How Distance is Calculated

The project uses a basic camera distance formula:

