# 🖐️ Presentation Controller using Hand Gestures

Control your presentation slides seamlessly using only your hand gestures with the help of OpenCV and CVZone. This tool enables a touchless and intuitive presentation experience using your webcam.

---

## 🎯 Features

- Navigate slides using simple hand gestures.
- Annotate or draw directly on slides in real-time.
- Undo annotations with a single gesture.
- See yourself live in a picture-in-picture view.

---

## ✋ Hand Gestures Guide

| Gesture                          | Action                    |
|----------------------------------|---------------------------|
| 👉 Pinky finger (right)          | Next Slide                |
| 👍 Thumb (left)                  | Previous Slide            |
| 🤟 3 Fingers Up (Index, Middle, Ring) | Undo Last Annotation     |
| ✌️ 2 Fingers Up (Index, Middle) | Move Cursor (No Drawing)  |
| ☝️ 1 Finger Up (Index)          | Start Drawing/Annotating  |

> All gestures must be made **above the green threshold line** to register navigation commands (e.g., next/previous slide). Drawing gestures can be done below the line.

---

## 🧠 How It Works

- Uses OpenCV to capture video and detect your hand.
- CVZone's `HandDetector` identifies fingers and landmarks.
- Custom logic maps gestures to slide navigation and annotation.
- Annotations are drawn in real-time using finger tracking.

## How to run it and place the files.

- Download the files provided in the repository.
- Arrange the files in such a way that it is in this order
Gesture Presentation/Presentation/whatsapp images
and also main.py and tempcoderunner.py should be under the Gesture Presentation folder.
- Run main.py file in any compiler. Make sure to have cvzone, mediapipe, opencv and python installed in your system.
