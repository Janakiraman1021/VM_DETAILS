<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gesture Controller</title>
</head>

<body>

    <h1>Gesture Controller</h1>

    <h2>Introduction</h2>
    <p>Gesture Controller is a Python script that leverages the MediaPipe library for hand tracking and recognition.
        This script allows users to control their computer using hand gestures captured through a webcam.
        It interprets various hand gestures, such as fist, pinch, V-gesture, and more, and performs corresponding
        actions like mouse control, clicking, double-clicking, and system controls (e.g., volume and brightness
        adjustments).</p>

    <h2>Author</h2>
    <p><strong>Author:</strong> Janakiraman</p>

    <h2>Dependencies</h2>
    <p>Ensure that you have the following Python libraries installed before running the script:</p>
    <ul>
        <li><code>cv2</code></li>
        <li><code>mediapipe</code></li>
        <li><code>pyautogui</code></li>
        <li><code>pycaw</code></li>
        <li><code>screen-brightness-control</code></li>
    </ul>

    <p>You can install these dependencies using the following command:</p>
    <pre><code>pip install opencv-python mediapipe pyautogui pycaw screen-brightness-control</code></pre>

    <h2>How to Run</h2>
    <ol>
        <li>Clone this repository to your local machine.</li>
        <li>Install the required dependencies.</li>
        <li>Execute the script using Python:
            <pre><code>python gesture_controller.py</code></pre>
        </li>
    </ol>

    <h2>Usage</h2>
    <ul>
        <li>The script captures video feed from the webcam, detects hand landmarks, and recognizes gestures based on
            hand positions.</li>
        <li>Different gestures trigger various actions, such as moving the mouse, left/right clicking, double-clicking,
            and system controls.</li>
        <li>Press <code>Enter</code> to exit the application.</li>
    </ul>

    <h2>Customization</h2>
    <p>You can customize the script by adjusting the gesture encodings, modifying the actions in the <code>Controller</code>
        class, or extending the functionality based on your specific needs.</p>

    <h2>Contributions</h2>
    <p>Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please
        open an issue or submit a pull request.</p>

    <h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

</body>

</html>
