<h1 align="center">🖐️ Hand Gesture Control System</h1>

<p align="center">
  <b>Control your entire computer using just your hand gestures 🖐️ — no touch, no mouse, just movement!</b><br>
  A Computer Vision + Python project for hands-free control of volume, brightness, screenshots, apps, and more.
</p>

---

## 🚀 Project Overview
The **Hand Gesture Control System** uses real-time **hand tracking** to interpret gestures and perform computer actions.  
With the power of **OpenCV**, **MediaPipe**, and **PyAutoGUI**, your **webcam** becomes a smart controller — allowing you to interact with your PC naturally and efficiently.

<p align="center">
  <img src="https://github.com/damodar04/hand-gesture-control/assets/placeholder-demo.gif" width="700px" alt="Demo GIF">
</p>

---

## ✨ Features

| 💡 Feature | 🎯 Description |
|------------|----------------|
| 🎚️ **Volume Control** | Control system volume using finger distance. |
| 🌞 **Brightness Control** | Adjust screen brightness with simple gestures. |
| 📸 **Screenshot Capture** | Take instant screenshots with a specific hand pose. |
| 🗂️ **App & File Launching** | Open apps or files using gestures. |
| 🔄 **Glove Mode** | Use with or without a glove for flexibility. |
| 🧠 **AI-Powered Detection** | Uses MediaPipe’s landmark model for accurate tracking. |

---

## 🧩 Project Structure

**Folder Tree:**
- 📁 **hand-gesture-control/**
  - 📄 **app.py** → Main application entry point.
  - 📄 **Gesture_Controller.py** → Core gesture detection and system control.
  - 📄 **Gesture_Controller_Gloved.py** → Gesture detection version for glove input.
  - 📄 **4bytes.py** → Helper/utility script.
  - 📄 **tempCodeRunnerFile.py** → Temporary file used during development.
  - 📄 **LICENSE** → License file for the project.
  - 📄 **README.md** → This documentation file.

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

## ⚙️ Installation

### 🧰 Step 1 — Clone the repository
bash
git clone https://github.com/damodar04/hand-gesture-control.git
cd hand-gesture-control  

---

### 📦 Step 2 — Install dependencies
pip install -r requirements.txt


If you don’t have a requirements file:

pip install opencv-python mediapipe pyautogui numpy screen-brightness-control pycaw

▶️ Step 3 — Run the project
python app.py


Or directly run the controller:

python Gesture_Controller.py

🧠 How It Works

The webcam continuously captures live video frames.

MediaPipe identifies 21 hand landmarks in real time.

Detected gestures (like finger positions or distances) are mapped to specific actions.

PyAutoGUI performs system-level tasks such as mouse, volume, and brightness control.

Examples of Gestures:

Gesture	Action
🖐️	Move mouse cursor
✌️	Capture screenshot
👍	Increase volume
👎	Decrease volume
📸 Demo (Optional)

You can embed a demo GIF or YouTube video link here.

🎥 Example Demo:
👉 Coming Soon: "Hand Gesture Control in Action"

🔒 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

👨‍💻 Author

Damodar Bhawsar
💼 Data Science & Automation Enthusiast
<p align="center">
  <img src="damodar.7974@gmail.com" width="700px" alt="Demo GIF">
</p>

⭐ Acknowledgements

MediaPipe by Google

PyAutoGUI Documentation

OpenCV
