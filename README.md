# AN-AIoT-BASED-AUTONOMOUS-VEHICLE-PROTOTYPE-WITH-SMART-MOBILITY-AND-LANE-DETECTION
AIoT-based autonomous vehicle prototype integrating Raspberry Pi, Arduino, OpenCV, and YOLO-based computer vision for real-time lane detection, object recognition, and smart mobility.
# Objectives
To develop an AI-based vision system capable of detecting lanes, zebra crossings,pedestrians and road conditions in real time.
To implement intelligent decision-making that analyzes the vehicle's surroundings and determines appropriate actions.
To integrate Raspberry Pi, Arduino, sensors, and AI models into a unified autonomous mobility prototype for real-time perception and control.
# Hardware Components
Raspberry Pi 5 (8GB RAM)
Arduino Uno R4 Minima
USB camera
BTS7960 motor drivers
DC motors
Ultrasonic sensor
Battery and power supply components
Connecting wires and vehicle chassis
# Software and Technologies
Python
OpenCV
YOLO-based computer vision model
Arduino IDE
Raspberry Pi OS
Serial communication
VNC Viewer for remote access
Visual Studio Code
# Working Principle
The USB camera captures images of the vehicle's surroundings.
The Raspberry Pi processes the camera input using OpenCV and the YOLO-based vision model.
The implemented vision system identifies the supported road features and object classes.
The Raspberry Pi sends movement or control commands to the Arduino through serial communication.
The Arduino interprets the received commands and controls the motor drivers.
The motors respond to the implemented control logic to perform the required vehicle movements.
The system combines camera-based perception with embedded control to demonstrate key concepts used in autonomous mobility.
# Future Improvements
Improve lane and zebra-crossing detection under different lighting conditions.
Refine decision-making and vehicle-control logic.
Improve obstacle detection and response.
Explore vehicle-to-vehicle (V2V) communication and coordinated braking as future research directions.
# Limitations and Safety
This project is an educational prototype developed for learning and experimentation. It is not designed or validated for use on public roads. Its detection and control performance may vary depending on environmental conditions, hardware limitations, and model accuracy.
