# ROS 2

## Installation

Two options:
- **Dockerized Installation**: follow either [Ayg](https://github.com/Cyber-Fusion/Ayg) for the full Ayg's software stack, or [Docker + ROS + NVIDIA](https://github.com/ddebenedittis/docker_ros_nvidia) for a minimal docker setup with GUIs and NVIDIA support.
- **Classical Installation**: follow [this](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debs.html).

It is recommended to follow the Dockerized Installation to not be constrained by the host OS and have a reproducible environment.

## Tutorials

[Official ROS 2 tutorials](https://docs.ros.org/en/humble/Tutorials.html).

Fundamentals:
- From Concepts:
  - Basic Concepts
- From Tutorials:
  - Beginner: CLI tools
  - Beginner: Client libraries
  - From Intermediate:
    - Launch
    - tf2
    - Testing
    - URDF
    - RViz
  - From Advanced:
    - Simulators -> Gazebo
- From Concepts:
  - Intermediate Concepts

It is recommended to read and understand these tutorials without however fully memorizing the syntax. Just knowing what is possible within ROS 2 and where to find the information when needed is sufficient. \\
On the other hand, memorizing the CLI commands is useful as they are used often.

Know the difference between Gazebo Classic and Gazebo (ex. Ignition Gazebo).
- [Gazebo Classic](https://classic.gazebosim.org/) is the "old" Gazebo, now EOL.
- [Gazebo](https://gazebosim.org/home) is the new generation simulator. In CF, we use this one.