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

```bash
📦 hand-gesture-control
├── app.py                        # Main application entry point
├── Gesture_Controller.py         # Core gesture detection and system control
├── Gesture_Controller_Gloved.py  # Gesture detection for glove input
├── 4bytes.py                     # Utility/helper script
├── tempCodeRunnerFile.py         # Temporary development file
├── LICENSE                       # Project license
└── README.md                     # Project documentation
🛠️ Technologies Used
Technology	Purpose
🐍 Python 3.8+	Core programming language
👁️ OpenCV	Real-time image & video processing
✋ MediaPipe	Hand landmark detection & tracking
🖱️ PyAutoGUI	System control automation
🔊 pycaw	Audio control
💡 screen-brightness-control	Brightness management
🔢 NumPy	Mathematical computations

⚙️ Installation
🧰 1. Clone the repository
bash
Copy code
git clone https://github.com/damodar04/hand-gesture-control.git
cd hand-gesture-control
📦 2. Install dependencies
bash
Copy code
pip install -r requirements.txt
If you don’t have a requirements file yet:

bash
Copy code
pip install opencv-python mediapipe pyautogui numpy screen-brightness-control pycaw
▶️ 3. Run the project
bash
Copy code
python app.py
or directly run the controller:

bash
Copy code
python Gesture_Controller.py
🧠 How It Works
The webcam continuously captures live video.

MediaPipe identifies 21 hand landmarks in real-time.

Gestures (based on finger distance/position) are mapped to predefined actions.

PyAutoGUI executes the system command.

Gesture	Action
🖐️	Move mouse cursor
✌️	Capture screenshot
👍	Increase volume
👎	Decrease volume

🔒 License
This project is licensed under the MIT License — see the LICENSE file for details.

👨‍💻 Author
Damodar Bhawsar
💼 Data Science & Automation Enthusiast
📧 damodar.7974@gmail.com

⭐ Acknowledgements
MediaPipe by Google

PyAutoGUI Documentation

OpenCV
