# Gesture Controller

## Introduction
Gesture Controller is a Python script that leverages the MediaPipe library for hand tracking and recognition. This script allows users to control their computer using hand gestures captured through a webcam. It interprets various hand gestures, such as fist, pinch, V-gesture, and more, and performs corresponding actions like mouse control, clicking, double-clicking, and system controls (e.g., volume and brightness adjustments).

## Author
- **Author:** Janakiraman

## Dependencies
Ensure that you have the following Python libraries installed before running the script:
- `cv2`
- `mediapipe`
- `pyautogui`
- `pycaw`
- `screen-brightness-control`

You can install these dependencies using the following command:
```bash
pip install opencv-python mediapipe pyautogui pycaw screen-brightness-control



How to Run
Clone this repository to your local machine.
Install the required dependencies.
Execute the script using Python:


python gesture_controller.py


Usage
The script captures video feed from the webcam, detects hand landmarks, and recognizes gestures based on hand positions.
Different gestures trigger various actions, such as moving the mouse, left/right clicking, double-clicking, and system controls.
Press Enter to exit the application.


Customization
You can customize the script by adjusting the gesture encodings, modifying the actions in the Controller class, or extending the functionality based on your specific needs.

License
This project is licensed under the MIT License.

