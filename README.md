🖐️ Hand Gesture Control System

A Computer Vision + Python project that allows users to control their entire computer using hand gestures captured through a webcam.
This includes actions like controlling volume, brightness, screenshots, app launching, file opening, and more — all hands-free!

🚀 Project Overview

The Hand Gesture Control System uses real-time hand tracking to interpret specific gestures and perform predefined system actions.
It leverages OpenCV, MediaPipe, and PyAutoGUI to create a fully interactive experience where your hand becomes your controller.

✨ Key Features

🎚️ Volume Control — Increase or decrease system volume using hand distance.

🌞 Brightness Control — Adjust screen brightness with gestures.

📸 Screenshot Capture — Instantly take screenshots with a simple gesture.

🗂️ App & File Launching — Open applications or files with specific hand signals.

🔄 Gesture Recognition (with or without gloves) — Works with bare hands or with a glove setup for accuracy.

🧠 AI-Powered Gesture Detection — Uses MediaPipe Hand Landmark model for precise recognition.

🧩 Project Files
File Name	Description
app.py	Main application file (entry point). Runs the Streamlit or main interface if implemented.
Gesture_Controller.py	Core script for detecting hand gestures and controlling system functions.
Gesture_Controller_Gloved.py	Alternate version for gesture detection using a glove setup.
4bytes.py	Utility or helper script for supporting functionalities.
tempCodeRunnerFile.py	Temporary file used during development (can be ignored).
LICENSE	Project license file.
README.md	Project documentation (this file).
🛠️ Technologies Used

Python 3.8+

OpenCV – for real-time image processing

MediaPipe – for hand landmark tracking

PyAutoGUI – to control mouse, keyboard, and system events

NumPy – for data processing

Screen-Brightness-Control / pycaw – for brightness and audio control

⚙️ Installation
1️⃣ Clone this repository
git clone https://github.com/damodar04/hand-gesture-control.git
cd hand-gesture-control

2️⃣ Install the required dependencies
pip install -r requirements.txt


(If there’s no requirements file, install manually:)

pip install opencv-python mediapipe pyautogui numpy screen-brightness-control pycaw

3️⃣ Run the project
python app.py


or run the controller directly:

python Gesture_Controller.py

🧠 How It Works

The webcam captures live video frames.

MediaPipe detects 21 hand landmarks in each frame.

Gestures (like finger positions or distances) are mapped to actions.

PyAutoGUI executes the respective computer command.

Example:
🖐️ → Move mouse
✌️ → Take screenshot
👍 → Increase volume
👎 → Decrease volume

🔒 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

👨‍💻 Author

Damodar Bhawsar
💼 Data Science & Automation Enthusiast
📧 damodar.7974@gmail.com
🔗 https://github.com/damodar04

⭐ Acknowledgements

MediaPipe by Google

PyAutoGUI Documentation

OpenCV
