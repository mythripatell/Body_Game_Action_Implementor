# 🕹️ Body Action Game Implementer

A gesture-controlled, camera-based real-time game controller built with **OpenCV**, **MediaPipe**, and **PyAutoGUI**. This project enables full-body interaction with games using hand and body movements instead of traditional input devices.

---

## 📌 Abstract

This system captures player movements via a webcam and converts them into game commands such as **jump**, **roll**, and **move left/right**. It eliminates the need for physical controllers by using gesture recognition, enhancing accessibility and user engagement. The project is ideal for applications in **gaming**, **education**, **fitness**, and **rehabilitation**.

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**:
  - OpenCV (image processing)
  - MediaPipe (pose & hand detection)
  - PyAutoGUI (simulate keyboard actions)
- **Platform**: PC, webcam-enabled

---

## 🔁 Core Features

| Gesture                         | Action            |
|----------------------------------|-------------------|
| ✌️ Victory Sign (Both Hands)     | Start Game        |
| ➡️ Move Shoulder Right            | Move Right        |
| ⬅️ Move Shoulder Left             | Move Left         |
| 🙆 Jump (Vertical Lift)           | Jump              |
| ↩️ Lower Body (Duck/Crouch)       | Roll              |

---

## 📷 Visuals (Screenshots)

![Start Gesture](start_gesture.png)
![Move Left](move_left.png)


```text
images/
├── start_gesture.png
├── move_left.png
├── move_right.png
├── jump.png
├── roll.png

