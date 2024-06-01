# 🤖 Robot Simulation Project using ROS2 Humble and Gazebo! 

## Overview

This project features a robot model equipped with:

- 🛰️ **Lidar**
- 📸 **Stereo Camera as a Depth Camera**

Using these sensors, the robot can perform SLAM (Simultaneous Localization and Mapping) to map a room and navigate from one location to another while avoiding obstacles with Nav2.

## Branches

### 🌍 Main Branch: SLAM and Navigation

- **Lidar and Camera**: Collects environmental data.
- **SLAM**: Creates a map of the environment.
- **Nav2**: Navigates the robot from one location to another, avoiding obstacles along the way.

### 🎾 ObjectTracking Branch

In this branch, the robot tracks a tennis ball using object detection.

- **Object Detection**: Implemented with OpenCV.
- **Repository**: Utilizes code from [joshnewans/ball_tracker](https://github.com/joshnewans/ball_tracker).

## Usage

- **Mapping a Room**:
    1. Move the robot around to create a map. 
    2. Save the generated map.

- **Navigation**:
    1. Load the saved map.
    2. Set a goal location.
    3. The robot will navigate to the goal while avoiding obstacles.

- **Object Tracking**:
    1. Switch to the `ObjectTracking` branch.
    2. Launch the object tracking node.
    3. The robot will track a tennis ball in the environment.

## Simulation Videos

🎥 Watch simulation videos in the [Simulator Video Repository](https://github.com/yourusername/simulator-video-repo).

## License

This project is licensed under the MIT License.

---

Happy Coding! 🎉
