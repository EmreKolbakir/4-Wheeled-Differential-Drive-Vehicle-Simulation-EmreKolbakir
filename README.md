# 🚀 Differential Drive Robot Simulation Project 🤖

## Overview 🌐
This project is a comprehensive simulation of a differential drive robot using ROS, Gazebo, and OpenCV. It integrates various elements like robotic state publishers, image processing, and motor control to create a realistic simulation environment.

## Features ✨
- 🌌 Launches a Gazebo simulation environment with a custom differential drive robot.
- 📷 Integrates OpenCV for image processing and edge detection.
- 🤖 Includes URDF files for robot modeling.
- 🕹️ Provides rviz configuration for visualization.
- 🏎️ Control the robot's movement through velocity or torque commands.

## Launch File Arguments 🚀
- 🛑 `paused`: Start simulation in a paused state.
- ⏱️ `use_sim_time`: Use simulation time.
- 💻 `gui`: Launch with or without Gazebo GUI.
- 🕶️ `headless`: Run in a headless mode.
- 🐞 `debug`: Enable debug mode.

## Robot Control 🎮
- 🔄 Control the robot's differential drive via ROS topics.
- 🚦 Send velocity or torque commands to actuate the robot's motors.
- 🌍 Fully integrated with Gazebo for realistic physics simulation.

## Image Converter Node 📸
- 📡 Subscribes to raw image feed from the camera.
- 🔍 Performs edge detection using OpenCV.
- 📤 Publishes processed image data.

## Robot Description 🛠️
- ⚙️ The robot, `vehiclediffdrive`, is defined with various components like wheels, camera, and laser.
- 🔌 The robot is equipped with motor plugins for each wheel, allowing precise control over movement.
- 🎨 Uses different materials for visual distinction in Gazebo.
- 🤖 Configured with joints and plugins for movement and sensor data processing.

## Panels and Preferences in RViz 🖥️
- 🛠️ Customizable RViz panels for different displays and tools.
- 📊 Pre-configured settings for Grid, RobotModel, Image, and LaserScan displays.

## Installation 💾 
1. Clone the repo: `git clone https://github.com/EmreKolbakir/4-Wheeled-Differential-Drive-Vehicle-Simulation-EmreKolbakir`
2. Navigate to the project directory.
3. Run `catkin_make` to build the project.

## Running the Simulation 🏗️
1. Launch the simulation: `roslaunch project_ws final1.launch`
2. Open RViz for visualization: `rosrun rviz rviz`

## Dependencies 📚
- ROS (Robot Operating System)
- Gazebo
- OpenCV
