# Body_Game_Action_Implementor

A real-time computer vision–based system that detects **hand gestures** and translates them into actionable commands for interaction — enabling basic gesture-controlled game play and user input. This project leverages **OpenCV** and **MediaPipe** to track body landmarks and interpret motion logic in live video feeds.

---

## 🎯 Objective

To create an intuitive, contactless system for recognizing hand gestures and mapping them to functional actions, suitable for games or interactive simulations. This project offers an early exploration into **gesture-based interfaces** using real-time computer vision.

---

## 🧠 Tech Stack

- **Language**: Python  
- **Libraries**:
  - OpenCV
  - MediaPipe (for pose and hand tracking)
  - NumPy
- **Platform**: PC / Webcam interface

---

## 🛠️ Features

- 📷 Real-time webcam capture and hand tracking  
- ✋ Static and dynamic hand gesture detection  
- 🎮 Action mapping (e.g., forward, jump, crouch, shoot) from hand poses  
- 🔍 Pose-based calibration to adapt to user’s position  

---

## 🧪 Sample Actions (Mapping Examples)

| Gesture             | Mapped Action       |
|---------------------|---------------------|
| Two Fingers Raised  | Move Forward        |
| Fist                | Shoot               |
| Palm Open           | Idle / Neutral      |
| Thumbs Up           | Confirm Action      |

---

## 📈 Visual Outputs

You can view the output and test runs by uploading screenshots to:




---

## 📁 Folder Structure

```text
body-action-implementor/
├── images/                   # Screenshots of gesture actions
│   ├── gesture_forward.png
│   └── gesture_shoot.png
├── data/                     # Sample gesture data (if applicable)
├── src/
│   ├── gesture_tracking.py   # Main detection script
│   └── action_mapper.py      # Mapping gestures to actions
├── requirements.txt          # Required libraries
└── README.md                 # Project documentation


