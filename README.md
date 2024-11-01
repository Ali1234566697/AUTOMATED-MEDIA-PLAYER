# AUTOMATED-MEDIA-PLAYER
Overview:

--> Automated Media Player is a Python-based project that utilizes computer vision and gesture recognition to control media playback on a computer.

--> The system is designed to recognize hand gestures captured through the computer's webcam and translate them into specific commands to control media playback.

** Features:

--> Gesture Recognition:

The project uses the MediaPipe library for hand tracking and gesture recognition.

By analyzing the positions of landmarks on the hand, it determines specific gestures such as counting fingers.

--> Media Control: Based on the recognized gestures, the system performs actions such as play, pause, skip forward, and skip backward on a media player.

--> Cross-Platform Compatibility:

The project is implemented in Python, making it platform-independent.

It can be run on various operating systems such as Windows, macOS, and Linux.

** Requirements:

--> Python 3.x

--> OpenCV (cv2)

--> MediaPipe

--> PyAutoGUI

** Installation:

Install Python if not already installed. You can download it from the official Python website: " python.org"

** Install required Python packages using pip:

--> Copy code

--> pip install opencv-python mediapipe pyautogui

** Usage:

--> Clone the repository or download the project files to your local machine.

--> Connect a webcam to your computer if it's not built-in.

--> Run the automated_media_player.py script.

--> Ensure that your hand is visible to the webcam.

--> The project will track your hand movements and recognize gestures.

** Perform gestures according to the defined controls:

1 finger raised: Skip forward

2 fingers raised: Skip backward

3 fingers raised: Play/pause

To exit the program, press the Esc key.

** Contributing:

Contributions to the project are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request on the project's GitHub repository.

By following these instructions, users can understand how to set up and utilize the Automated Media Player project effectively for controlling media playback through hand gestures.
