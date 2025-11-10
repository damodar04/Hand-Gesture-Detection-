# 🖐️ Hand Gesture Control System

**Control your entire computer using just your hand gestures — no touch, no mouse, just movement!**  
A Computer Vision + Python project for hands-free control of **volume, brightness, screenshots, apps, and more**.

---

## 🚀 Project Overview

The **Hand Gesture Control System** uses real-time **hand tracking** to interpret gestures and perform computer actions.  
With the power of **OpenCV**, **MediaPipe**, and **PyAutoGUI**, your **webcam** becomes a smart controller —  
allowing you to interact with your PC naturally and efficiently.

---

## ✨ Features

| 💡 Feature | 🎯 Description |
|------------|----------------|
| 🎚️ **Volume Control** | Control system volume using finger distance. |
| 🌞 **Brightness Control** | Adjust screen brightness with simple gestures. |
| 📸 **Screenshot Capture** | Take instant screenshots with a specific hand pose. |
| 🗂️ **App & File Launching** | Open applications or files using gestures. |
| 🔄 **Glove Mode** | Works with or without a glove for accuracy. |
| 🧠 **AI-Powered Detection** | Uses MediaPipe’s hand landmark model for precise gesture tracking. |

---

## 🧩 Project Structure

hand-gesture-control/
├── app.py → Main application entry point
├── Gesture_Controller.py → Core gesture detection and system control
├── Gesture_Controller_Gloved.py→ Gesture detection version for glove input
├── 4bytes.py → Helper or utility script
├── tempCodeRunnerFile.py → Temporary file used during development
├── LICENSE → License file
└── README.md → Project documentation


---

## 🛠️ Technologies Used

| Technology | Purpose |
|-------------|----------|
| 🐍 **Python 3.8+** | Core programming language |
| 👁️ **OpenCV** | Real-time image & video processing |
| ✋ **MediaPipe** | Hand landmark detection & tracking |
| 🖱️ **PyAutoGUI** | System control automation |
| 🔊 **pycaw** | Audio control |
| 💡 **screen-brightness-control** | Brightness management |
| 🔢 **NumPy** | Mathematical computations |

---

## 🧠 How It Works

1. The webcam continuously captures live video frames.  
2. **MediaPipe** identifies **21 hand landmarks** in real time.  
3. Detected gestures (like finger positions or distances) are mapped to specific computer actions.  
4. **PyAutoGUI** executes those system-level tasks like controlling volume, brightness, taking screenshots, etc.

**Examples of Gestures:**

| Gesture | Action |
|----------|---------|
| 🖐️ | Move mouse cursor |
| ✌️ | Capture screenshot |
| 👍 | Increase volume |
| 👎 | Decrease volume |

---

## 🔒 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

## 👨‍💻 Author

**Damodar Bhawsar**  
💼 *Data Science & Automation Enthusiast*  
📧 **damodar.7974@gmail.com**  
🔗 [GitHub Profile](https://github.com/damodar04)

---

## ⭐ Acknowledgements

- [MediaPipe by Google](https://developers.google.com/mediapipe)  
- [PyAutoGUI Documentation](https://pyautogui.readthedocs.io/)  
- [OpenCV](https://opencv.org/)

---

⭐ **If you like this project, don’t forget to star it on GitHub!**
