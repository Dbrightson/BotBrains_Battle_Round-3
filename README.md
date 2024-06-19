# BotBrains Battle - Real-World Rumble 🤖🌍

This repository documents my participation in the **BotBrains Battle - Real-World Rumble**, conducted by IIT Bhubaneshwar students. The challenge involved developing an autonomous drone fleet for efficient search operations over a grassy field. Here, I present my experience and the contents of this project.

## Project Overview 🛠️

I developed a UAV (Unmanned Aerial Vehicle) fleet capable of autonomously flying over a grassy area, searching for specific targets among clutter, and communicating the target's location to other drones in the fleet. The goal was to eliminate human intervention in the search process, making it useful for tasks such as equipment retrieval and military applications.

## Files in the Repository 📂

### 1. DRONE_SYSTEM-PART A, B, C.pdf 📄

The **DRONE_SYSTEM-PART A, B, C.pdf** file contains mini questions to test my knowledge on UAVs, divided into three sections:

- **Part A**: This section covers the fundamentals of UAV technology, including definitions, key concepts, and basic operations.
- **Part B**: This part delves into communication protocols, particularly focusing on how to use ESP8266 with a controller to facilitate drone communication.
- **Part C**: This section explores potential design changes to enhance drone performance, specifically targeting improvements in flying height and weight-carrying capacity for applications like food delivery.

Each part contains detailed explanations, justifications for design choices, and references to support the suggested improvements.

### 2. DRONE_SYSTEM-PART D.pdf 📄

The **DRONE_SYSTEM-PART D.pdf** file focuses on the implementation of the autonomous search operation using the drone fleet. It includes:

- **Introduction and Search Algorithm**: A comprehensive explanation of the initialization process, search operation, object verification, and communication protocols.
- **Calculations**: Detailed mathematical calculations for search area division, flight path planning, collision avoidance, and power consumption.
- **Diagrams**: Visual representations of the initialization and search process, flight paths, and communication flow between drones.

### 3. droneSystem.cpp 🧑‍💻

The **droneSystem.cpp** file is the C++ code implementation of the drone system. It includes:

- **Initialization Function**: Code to initialize the drones, assign search areas, and establish communication links.
- **Search Algorithm**: Implementation of the lawnmower pattern for area coverage, object detection using LiDAR, and color verification.
- **Communication Protocol**: Functions to communicate the target's location to other drones and stop their search operations.
- **Object Verification**: Methods to verify the dimensions and color of detected objects.

## My Experience 🚀

Participating in the **BotBrains Battle - Real-World Rumble** was an exhilarating experience! Here's a glimpse into my journey:

1. **Conceptualization**: I started by understanding the problem statement and brainstorming solutions for autonomous search operations using drones. The challenge of integrating multiple drones to work seamlessly together was both intriguing and demanding.

2. **Research and Design**: I delved into swarm drone technology, communication protocols, and autonomous navigation. Designing the system to ensure efficient search and accurate target detection was a critical phase.

3. **Implementation**: Writing the C++ code to implement the search algorithm, object verification, and communication was a rewarding experience. I paid special attention to optimizing the flight paths and ensuring reliable communication between the drones.

4. **Testing and Validation**: Testing the system in a simulated environment allowed me to refine the algorithms and ensure robust performance. The successful detection of targets and seamless communication between drones were the highlights of my testing phase.

5. **Learning and Growth**: Working on this project was a fantastic learning experience. The knowledge gained from this project is invaluable and will undoubtedly contribute to my future endeavors in the field of robotics and autonomous systems.

## Conclusion 🎉

This project was a testament to my ability to innovate, problem-solve, and implement complex systems. I am proud of the system I developed and the knowledge I gained throughout this journey. I hope this repository provides valuable insights into my approach and inspires others to explore the fascinating world of autonomous drones.

Thank you for visiting my repository! If you have any questions or feedback, feel free to reach out. Happy exploring! 🌟

---

*This project was conducted as part of the BotBrains Battle - Real-World Rumble, organized by IIT Bhubaneshwar students. I am grateful for the opportunity to participate and learn through this experience.* 🚁🤖🎓
