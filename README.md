# 🤖 Robot Simulation Project using ROS2 Humble and Gazebo!

## Overview

This project features a robot model equipped with:

- 🛰️ **Lidar**
- 📸 **Stereo Camera as a Depth Camera**

Using these sensors, the robot can map a room and navigate from one location to another while avoiding obstacles with SLAM and Nav2.
### Here is a video demonstrating the project:

[![Demonstration Video](https://github.com/PrabathBK/Ros2-Simulation-with-Gazebo/blob/main/tumbnail2.png?raw=true)](https://youtu.be/foo7gtkE8sE) </br>

link:- https://www.youtube.com/watch?v=foo7gtkE8sE </br>

## Branches

### 🌍 Main Branch: Mapping and Navigation
- Collects environmental data using sensors and navigates the robot from one location to another, avoiding obstacles along the way.

### 🎾 Object Tracking Branch
- The robot tracks a tennis ball using OpenCV object detection.

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

🎥 Watch simulation videos in the [Simulator Video Repository](https://github.com/PrabathBK/Ros2-Simulation-with-Gazebo/tree/main/simulation%20videos).

## License

This project is licensed under the MIT License.

---

Happy Coding! 🎉
