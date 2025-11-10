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
  <img src="https://github.com/damodar04/hand-gesture-control.gif" width="700px" alt="Demo GIF">
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
```bash
📁 hand-gesture-control/
  ├─ 📄 app.py                     → Main application entry point.
  ├─ 📄 Gesture_Controller.py        → Core gesture detection and system control.
  ├─ 📄 Gesture_Controller_Gloved.py → Gesture detection version for glove input.
  ├─ 📄 4bytes.py                  → Helper/utility script.
  ├─ 📄 tempCodeRunnerFile.py      → Temporary file used during development.
  ├─ 📄 LICENSE                    → License file for the project.
  └─ 📄 README.md                  → This documentation file.
🛠️ Technologies UsedTechnologyPurpose🐍 Python 3.8+Core programming language👁️ OpenCVReal-time image & video processing✋ MediaPipeHand landmark detection & tracking🖱️ PyAutoGUISystem control automation🔊 pycawAudio control💡 screen-brightness-controlBrightness management🔢 NumPyMathematical computations⚙️ Installation🧰 Step 1 — Clone the repositoryBashgit clone [https://github.com/damodar04/hand-gesture-control.git](https://github.com/damodar04/hand-gesture-control.git)
cd hand-gesture-control
📦 Step 2 — Install dependenciesIf you have a requirements.txt file (recommended):Bashpip install -r requirements.txt
If you don’t have a requirements file, install packages manually:Bashpip install opencv-python mediapipe pyautogui numpy screen-brightness-control pycaw
▶️ Step 3 — Run the projectRun the main application:Bashpython app.py
Or directly run the controller:Bashpython Gesture_Controller.py
🧠 How It WorksThe webcam continuously captures live video frames.MediaPipe identifies 21 distinct hand landmarks in real time.Detected gestures (like finger positions, counts, or distances) are mapped to specific actions.PyAutoGUI and other libraries perform system-level tasks such as moving the mouse, changing volume, and adjusting brightness.Examples of Gestures:GestureAction🖐️Move mouse cursor✌️Capture screenshot👍Increase volume👎Decrease volume🔒 LicenseThis project is licensed under the MIT License — see the LICENSE file for details.👨‍💻 Author<p align="center"><b>Damodar Bhawsar</b><i>💼 Data Science & Automation Enthusiast</i><a href="mailto:damodar.7974@gmail.com">damodar.7974@gmail.com</a></p>
