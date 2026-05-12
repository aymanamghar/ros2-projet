This project simulates a drone in Gazebo and controls it
using real-time hand gesture recognition with YOLO.

The system integrates:
- Gazebo simulation
- PX4/MAVLink communication
- QGroundControl
- YOLO hand tracking
- Real-time drone command generation

architecteur : 

Camera → YOLO → Gesture Recognition
                    ↓
             MAVLink Commands
                    ↓
           PX4 / Drone Control
                    ↓
               Gazebo Drone

🚀 How the System Works :
1-A webcam captures live video.
2-YOLO detects and classifies hand gestures.
3-The gesture is mapped to a drone movement command.
4-MAVLink sends commands to the PX4 controller.
5-The drone reacts instantly inside Gazebo.
6-QGroundControl displays telemetry and drone state.

![image alt](https://github.com/aymanamghar/ros2-projet/blob/b1d784887e66ecf2e20c3412756972f1856851d5/Screenshot%20from%202026-05-12%2010-41-00.png)
![image alt](https://github.com/aymanamghar/ros2-projet/blob/b1d784887e66ecf2e20c3412756972f1856851d5/Screenshot%20from%202026-05-12%2010-41-17.png)
![image alt](https://github.com/aymanamghar/ros2-projet/blob/292bf089672bbbaf21d45d8464dfd7d822c9e11e/Screenshot%20from%202026-05-12%2010-42-43.png)
