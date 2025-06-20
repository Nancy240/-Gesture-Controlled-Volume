# Gesture Controlled Volume 🎛️🖐️

Control your computer's volume using hand gestures through your webcam!  
Built using **MediaPipe** for hand tracking and **Pycaw** for audio control.


## 🧠 How It Works

- Uses webcam to detect hand landmarks (especially your thumb and index finger).
- Calculates the distance between them.
- Adjusts system volume based on this distance — move fingers apart to increase volume, bring them close to decrease.

## 🛠️ Tech Stack

- [MediaPipe](https://google.github.io/mediapipe/) for hand landmark detection
- [OpenCV](https://opencv.org/) for video processing
- [Pycaw](https://github.com/AndreMiras/pycaw) for volume control on Windows
