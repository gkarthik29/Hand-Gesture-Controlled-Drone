# Hand Gesture Controlled Drone with Wireless Charging
# 1. Introduction
This project demonstrates the development of a hand gesture-controlled drone equipped with wireless charging capabilities. The system utilizes computer vision and machine learning to interpret hand gestures, enabling intuitive control of the drone's movement. This innovative integration of hand gesture control and wireless charging aims to simplify drone operation and enhance user experience.

# 2. Abstract
The project combines gesture recognition and wireless charging technologies to control a drone effectively. Using MediaPipe for hand gesture recognition and OpenCV for real-time video feed processing, it detects hand landmarks and interprets specific gestures. The drone responds accordingly, offering a hands-free, seamless control experience. Additionally, a wireless charging mechanism ensures that the drone can recharge without manual intervention, boosting efficiency and operational convenience.

# 3. Steps to Proceed
# Prerequisites 
Hardware Components:

A drone (compatible with gesture control firmware).
Wireless charging module.
Camera module for gesture detection.
Arduino or microcontroller for interfacing.
Software/Dependencies:

- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- Arduino IDE (for embedded systems programming).

# Steps:
# A. Gesture Detection System
Clone the repository and navigate to the folder:

# Copy code
```
git clone https://github.com/yourusername/gesture-drone-wireless-charging.git
```
cd gesture-drone-wireless-charging
Install the required Python libraries:

Copy code
```
pip install opencv-python mediapipe numpy
```
Run the Test.py file to test the gesture recognition system:
bash
Copy code
```
python Test.py
```

This script uses MediaPipe to identify hand gestures and count fingers.
Ensure your camera is functional.
# B. Drone Control Integration
Write a communication protocol (e.g., using serial communication) between the Python script and the drone.
Use the 01_camera.py file to customize camera input and integrate gesture commands for the drone's movement.
# C. Wireless Charging Setup
Connect the wireless charging module to the drone as per the hardware specifications.
Ensure the module is properly configured for the drone's power requirements.
# D. Firmware for Drone
Use the Arduino IDE to upload the appropriate drone control script, such as the one in splash.ino.
Adjust settings in the script for gesture mappings and safety mechanisms.
# E. Testing
Start the gesture recognition script and connect the drone.
Perform hand gestures to control the drone:
E.g., one finger up for forward motion, two fingers for backward motion, etc.
Monitor wireless charging functionality during rest phases.
