# IGVC-Robot-Barbie-Jeep
This project focuses on developing an autonomous vehicle for the Intelligent Ground Vehicle Competition (IGVC). The vehicle integrates lane-keeping and object-avoidance algorithms, coupled with precise motor control, to navigate complex environments.

![Barbie_Jeep](https://github.com/user-attachments/assets/15254247-9e39-4a58-9c51-314bbc024136)

![LaneDetected](https://github.com/user-attachments/assets/7750169f-7922-4f8d-8964-09a401086e49)

- **Lane Detection**: Real-time lane detection algorithms for staying within designated paths, even when only one lane is visible using a 120 degree wide-angle camera.
- **Object Avoidance**: LiDAR-based object detection and avoidance, combined with custom algorithms for navigating around obstacles.
- **Motor Control**: Efficient communication between a NVIDIA Jetson Nano and Arduino ESP32 to control motors via a Sabretooth motor driver.
- **Hybrid Approach**: Combines Python-based software for computer vision processing on the Jetson Nano with motor control logic executed on the TM4C MCU.

### Demo:
![WorkingRobot](https://github.com/user-attachments/assets/2e4f7a10-6a70-4297-867b-070e7cf05ad1)
