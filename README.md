# Hand Gesture Automation with Arduino and OpenCV

## Overview
This project demonstrates how to use computer vision and Arduino to automate devices based on hand gestures. By raising fingers in front of a camera, you can control various devices, such as LEDs, TVs, fans, or other appliances, making your daily life more convenient and interactive.

The project uses OpenCV for hand gesture detection and Arduino with Firmata for device control. The number of fingers raised corresponds to the number of LEDs that are activated. For instance, one raised finger activates one LED, two fingers activate two LEDs, and so on, up to a maximum of five LEDs.

![Demo GIF](link_to_demo.gif)  <!-- Add a GIF or screenshot here -->

## Features
- Hand gesture recognition using OpenCV.
- Real-time control of devices based on the number of raised fingers.
- Easily customizable to automate various appliances.

## Requirements
- Python 3.x
- OpenCV library
- Arduino board with Firmata firmware
- Components Needed: LEDs, Jumper Wires and Breadboard
- Webcam or laptop camera
- Devices to control (e.g., LEDs, TVs, fans, etc.)

## Getting Started

1. Clone this repository to your local machine:
   
   ```bash
   https://github.com/Gururagavendra/home-automation-using-opencv
   ```

2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Upload the Firmata firmware to your Arduino board using the Arduino IDE.

4. Connect the LEDs to the Arduino board, ensuring you use appropriate resistors to limit current.

5. Run the Python script:

   ```bash
   python hand_gesture_control.py
   ```
6. Raise fingers in front of the camera to control the connected LEDs or other devices.

## Usage
Adjust the camera settings and detection thresholds in the hand_gesture_control.py script to optimize hand gesture recognition for your environment.
Customize the Arduino code and hardware connections to control other appliances.

## Contributing
Contributions are welcome! If you have ideas for improvements or new features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
OpenCV for computer vision capabilities.
Arduino for the microcontroller platform.
PyFirmata for the Python-Arduino communication library.

## Author
GitHub: Gururagavendra
