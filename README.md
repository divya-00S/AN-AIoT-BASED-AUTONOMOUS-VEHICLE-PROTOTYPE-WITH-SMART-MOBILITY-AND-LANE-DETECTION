# AN-AIoT-BASED-AUTONOMOUS-VEHICLE-PROTOTYPE-WITH-SMART-MOBILITY-AND-LANE-DETECTION
AIoT-based autonomous vehicle prototype integrating Raspberry Pi, Arduino, OpenCV, and YOLO-based computer vision for real-time lane detection, object recognition, and smart mobility.
# Objectives
- To develop an AI-based vision system capable of detecting lanes, zebra crossings,pedestrians and road conditions in real time.
- To implement intelligent decision-making that analyzes the vehicle's surroundings and determines appropriate actions.
- To integrate Raspberry Pi, Arduino, sensors, and AI models into a unified autonomous mobility prototype for real-time perception and control.
# Hardware Components
- Raspberry Pi 5 (8GB RAM)
- Arduino Uno R4 Minima
- USB camera
- BTS7960 motor drivers
- DC motors
- Ultrasonic sensor
- Battery and power supply components
- Connecting wires and vehicle chassis
# Software and Technologies
- Python
- OpenCV
- YOLO-based computer vision model
- Arduino IDE
- Raspberry Pi OS
- Serial communication
- VNC Viewer for remote access
- Visual Studio Code
# Working Principle
- The USB camera captures images of the vehicle's surroundings.
- The Raspberry Pi processes the camera input using OpenCV and the YOLO-based vision model.
- The implemented vision system identifies the supported road features and object classes.
- The Raspberry Pi sends movement or control commands to the Arduino through serial communication.
- The Arduino interprets the received commands and controls the motor drivers.
- The motors respond to the implemented control logic to perform the required vehicle movements.
- The system combines camera-based perception with embedded control to demonstrate key concepts used in autonomous mobility.
# Output Logic and Decision-Making

The autonomous vehicle uses camera-based detection and predefined decision-making logic to determine its movement based on the surrounding environment.

1. Lane Detection and Safety Assessment: When two lanes are detected and the path is considered safe, the vehicle moves forward. When three lanes are detected and the condition is classified as unsafe, the vehicle follows the implemented logic to return to the intended path.

2. Object Detection: When supported objects, such as animals, other vehicles, or stop signs, are detected, the vehicle stops according to the programmed control logic.

3. Zebra Crossing and Pedestrian Detection: When a zebra crossing is detected, the system checks for a pedestrian crossing. If a pedestrian is detected crossing, the vehicle stops. If no pedestrian is detected crossing, the vehicle continues moving according to the programmed logic.

4. Command Transmission: The Raspberry Pi sends the appropriate movement command to the Arduino through serial communication.

5. Vehicle Control: The Arduino processes the received command and controls the motors through the motor drivers to execute the required action.

Decision Summary

Detected Condition| Vehicle Action
Two lanes and safe path| Move forward
Three lanes and unsafe condition| Return to the intended path
Animal or other supported obstacle| Stop
Stop sign detected| Stop
Zebra crossing with a crossing pedestrian| Stop
Zebra crossing without a crossing pedestrian| Continue if the path is safe
# Future Improvements
- Improve lane and zebra-crossing detection under different lighting conditions.
- Refine decision-making and vehicle-control logic.
- Improve obstacle detection and response.
Explore vehicle-to-vehicle (V2V) communication and coordinated braking as future research directions.
# Limitations and Safety
This project is an educational prototype developed for learning and experimentation. It is not designed or validated for use on public roads. Its detection and control performance may vary depending on environmental conditions, hardware limitations, and model accuracy.
