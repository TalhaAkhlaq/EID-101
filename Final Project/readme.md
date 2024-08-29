# Line Following Robot with Ball Launcher

## Contributors

- [Talha Akhlaq](https://github.com/TalhaAkhlaq)
- [Abhijeet Khirdekar](https://github.com/akhirdekar)
- Brayan Ramos

## Technical Overview

### Develop a robot with the capability to:
1. Follow a line course.
2. Detect and respond to junctions.
3. Launch ping pong balls into a goal.
4. Navigate around obstacles.

## Design Process

### Releasing Mechanism

Develop a mechanism for reliably releasing ping pong balls with precise timing and accuracy by designing a system that ensures consistent propulsion, and integrating sensors to monitor and adjust release timing and positioning.

### Retrieval Mechanism

Design a system capable of collecting balls by integrating sensors to detect and locate them, and use an automated system to guide the balls to the collection area.

## Firmware

### Junction Detection and Line Following Algorithms

The software component encompasses algorithms for junction detection and line following. The junction detection algorithm identifies track intersections, while the line following algorithm maintains the robot's adherence to the path, adapting to curves and obstacles. Additionally, the firmware manages the release of balls and retrieval mechanisms, using sensor feedback to determine the optimal release timing and retrieval operations. It also ensures the robot can re-align and resume its course if it deviates.

## Course Breakdown

- **Course A**: The robot starts at a specified point, finds the junction, stops, follows the curve, and then stops at the end box.
- **Course B**: The robot locates the “end box” from three different starting points, demonstrating adaptability to different starting conditions.
- **Course C**: The robot detects the ping pong ball goal and launches the ball into the goal.
- **Course D**: The robot completes the course while avoiding placed obstacles, showcasing its ability to navigate and react to dynamic challenges.



