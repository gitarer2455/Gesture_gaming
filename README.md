# Gesture-Controlled Gaming with Python

This project allows you to play a game using hand gestures and body movements captured by a webcam. The gestures are interpreted using the MediaPipe library, and pyautogui is used to simulate key presses based on these gestures. The game can be controlled by the following actions:

- **Hands joined**: Start the game.
- **Left/Right movement**: Move the character left or right.
- **Jump/Crouch**: Jump or crouch by moving the body vertically.

## Requirements

This project uses the following libraries:

- `pyautogui` for controlling the keyboard
- `mediapipe` for detecting body landmarks and gestures
- `opencv-python` for video capture and image processing
- `numpy` for numerical operations

## Installation

To run the project, install the required dependencies:
after runnning the project use sample game to test it https://poki.com/en/g/subway-surfers
try subway surfures by jumping to the train (love to try cool stuffs)
```bash
pip install -r requirements.txt
