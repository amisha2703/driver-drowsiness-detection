# driver-drowsiness-detection
Drowsiness Detection System
Overview
This Python script is designed for real-time drowsiness detection using facial landmarks. It utilizes the dlib library for face detection and facial landmark prediction, OpenCV for image processing, and Pygame for sound alerts. The system monitors eye blink patterns to determine the driver's state, providing alerts when drowsiness or sleep is detected.

Features
Facial landmark detection using dlib's pre-trained model.
Real-time monitoring of eye blink patterns.
Status display on the frame indicating whether the driver is active, drowsy, or sleeping.
Sound alerts triggered based on the driver's state.
Requirements
Ensure you have the following libraries installed:

OpenCV (cv2)
NumPy (numpy)
dlib (dlib)
imutils (imutils)
Pygame (pygame)
Additionally, download the dlib shape predictor file and specify the correct path in the script:

shape_predictor_68_face_landmarks.dat
Place your desired sound alert file (e.g., "music.wav") at the specified path in the script.

Usage
Run the script in a Python environment.
bash
Copy code
python drowsiness_detection.py
The camera will be initialized, and the script will start monitoring facial expressions.

View the real-time status on the frame indicating whether the driver is active, drowsy, or sleeping.

Sound alerts will be triggered based on the detected state.

Press Esc to exit the script.

Important Notes
Ensure that your camera is connected and accessible.
Pay attention to the terminal for any errors or additional information.
Adjust the blink ratio thresholds in the script based on your testing and requirements
