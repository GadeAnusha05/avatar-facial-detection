# avatar-facial-detection
# 😊 Real-Time Facial Emotion Recognition with Voice Feedback

This project uses **MediaPipe**, **OpenCV**, and **pyttsx3** to detect facial expressions from a webcam feed and respond with real-time **emotion-based speech** and an animated avatar overlay.

---

## 🚀 Features

- 🔎 Detects facial emotions: **Happy**, **Sad**, **Angry**, **Surprised**, **Fear**, **Disgust**, **Neutral**
- 🎙️ Speaks out your emotion in real-time using text-to-speech (TTS)
- 🧠 Emotion classification based on facial landmarks (eyes, lips, mouth, iris, etc.)
- 🎨 Avatar visualization beside your webcam using MediaPipe's face mesh
- 🧵 Smooth, non-blocking voice output using threaded speech queue
- 🔁 Fast reaction — emotion updates every few frames

---

## 🖥️ Demo

| Webcam Feed | Avatar Canvas |
|-------------|----------------|
| ![webcam-feed](demo/webcam.gif) | ![avatar-canvas](demo/avatar.gif) |

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/facial-emotion-voice-feedback.git
   cd facial-emotion-voice-feedback

2.Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
3.Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
4.📦 Dependencies
text
Copy
Edit
opencv-python
mediapipe
numpy
pyttsx3
5.Install manually if needed:

bash
Copy
Edit
pip install opencv-python mediapipe numpy pyttsx3
6.▶️ Run the App
bash
Copy
Edit
python emotion_voice_app.py
Press ESC to exit the window.

7.📁 Project Structure
bash
Copy
Edit
.
├── emotion_voice_app.py       # Main Python script
├── README.md
├── requirements.txt
└── demo/
    ├── webcam.gif             # (Optional) Sample output GIFs
    └── avatar.gif
