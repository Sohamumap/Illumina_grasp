# IlluminaGrasp

IlluminaGrasp is an innovative project that leverages computer vision and hand tracking to control screen brightness dynamically. This interactive system utilizes the Mediapipe library for hand tracking and the screen_brightness_control library for adjusting screen brightness. The project is developed in Python, making use of the OpenCV library for webcam input and visualization.

## Features
- **Hand Tracking:** The system tracks specific landmarks on the hand, focusing on key points like fingers.
- **Dynamic Brightness Control:** By measuring the distance between selected hand landmarks, the system dynamically adjusts the screen brightness, offering a unique and interactive user experience.
- **Real-time Feedback:** The webcam feed displays the hand tracking and brightness control in real-time, providing immediate visual feedback to the user.

## How it Works
1. The project captures webcam input and processes it using the Mediapipe library to detect and track hand landmarks.
2. The system identifies specific hand gestures, such as grasping or pinching, to control the screen brightness.
3. The distance between selected hand landmarks determines the brightness level, providing a seamless and intuitive user interface.
4. The adjusted brightness levels are reflected in real-time, enhancing the overall user experience.

## Dependencies
- OpenCV: `pip install opencv-python`
- Mediapipe: `pip install mediapipe`
- Screen Brightness Control: `pip install screen-brightness-control`

## Usage

1. Install dependencies: `pip install -r requirements.txt`
2. Run the main script: `python illuminagrasp.py`
3. Interact with the webcam to control screen brightness dynamically.
