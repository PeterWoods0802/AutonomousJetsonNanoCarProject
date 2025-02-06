# Autonomous Jetson Nano Car Project

This project leverages the powerful Jetson Nano in conjunction with an Arduino, DC Motors, Motor Controllers, various sensors, a camera, and external power sources to create an autonomous electric car capable of navigating and interacting with its environment. This is a work in progress, with ongoing development in both hardware integration and software functionalities including a user interface being designed in Figma.

## Program List

- **Roam Mode:** The car roams autonomously within a user-defined radius, using a 2D LiDAR scanner to map its environment. It incorporates Darknet's YOLOv4 for real-time object detection and labeling.
- **Follow Mode:** The car follows a specific object or person within its environment.
- **Track Mode:** Track specific paths or waypoints predefined in the environment.
- **Create Mode:** Users can define custom behaviors and paths for the car.

## Essential Parts List

- **Jetson Nano B01** - Primary computing unit for image processing. [Buy here](https://www.amazon.com/Yahboom-Jetson-Nano-4GB-Board/dp/B09T37PPRF)
- **Servo Motors** - Used for the pan and tilt mechanisms of the camera. [Buy here](https://www.amazon.com/Dorhea-Arduino-Helicopter-Airplane-Walking/dp/B07Q6JGWNV)
- **Arduino Uno R3** - Manages motor drivers. [Buy here](https://www.amazon.com/ELEGOO-Board-ATmega328P-ATMEGA16U2-Compliant/dp/B01EWOE0UU)
- **Arduino Nano** - Controls pan/tilt mechanisms. [Buy here](https://www.amazon.com/ELEGOO-Pre-soldered-ATmega-Compatible-Arduino/dp/B0D5LYFRQP)
- **Wi-Fi Adapter** - For network connectivity. [Buy here](https://www.amazon.com/TP-Link-Nano-Archer-T3U-Wireless/dp/B09KTDXPY3)
- **LiDAR Sensor** - For scanning and mapping the environment. [Buy here](https://www.amazon.com/Slamtec-RPLIDAR-Scanning-Avoidance-Navigation/dp/B07TJW5SXF)
- **Camera** - For visual data processing. [Buy here](https://www.amazon.com/innomaker-Computer-Raspberry-Support-Windows/dp/B0CLRJZG8D)
- **Microphone** - Captures audio cues. [Buy here](https://www.amazon.com/WWZMDiB-Performance-Microphone-Amplifier-CMA-4544PF-W/dp/B0BVHBCX66)
- **Motor Driver Modules** - Control motor actions. [Buy here](https://www.amazon.com/QCCAN-DRV8833-Module-Bridge-Controller/dp/B0BGLH27GG)
- **Various other components** listed in the original parts list provided.

## Machine Learning and Computer Vision

The project utilizes machine learning for object detection and computer vision for the pan-tilt camera module, employing models such as ResNet along with OpenCV to enhance the car's interactive and autonomous capabilities.

## Current Status and Future Work

The project is still under active development. Current efforts are focused on enhancing the machine learning models for better object recognition and refining the user interface for easier control and interaction.

## Contributions

We welcome contributions from other developers and enthusiasts. Whether you have suggestions for improvements, bug fixes, or new features, your input is valuable. Please see our contribution guidelines for more information.
