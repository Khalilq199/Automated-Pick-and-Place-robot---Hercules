# Hercules I: Autonomous Pick-and-Place Robot

**Hercules I** is a prototype pick-and-place robot designed for autonomous object collection, storage, and navigation in a predefined rectangular area. Using advanced algorithms and object-oriented programming, Hercules I showcases high precision and efficiency in real-world scenarios.

## 🚀 Project Overview

Hercules I uses sensors, encoders, and a custom path-tracing algorithm to detect, collect, and store cylindrical objects within a defined area. The robot operates in two stages:
1. **Perimeter Tracing**: Hercules I starts in the bottom-left corner and traces the outer perimeter, using ultrasonic and touch sensors to detect objects and measure the environment.
2. **Central Area Detection**: After completing the perimeter, the robot scans the central area using an iterative program to ensure no objects are missed.

## 🔧 Features & Highlights

- **95% Object Storage Accuracy**: Optimized algorithms ensure high precision in collecting and storing objects during operation.
- **97% Obstacle Avoidance**: Successfully avoids walls, corners, and other obstacles using an ultrasonic sensor and a unique "parallel parking" algorithm.
- **100% Return-to-Base Success**: After completing the task, the robot reliably returns to its initial starting point.
- **Scalable Path-Tracing Algorithm**: The robot adapts to any enclosed rectangular environment, offering flexibility for various test conditions.
- **Optimized Sensor Placement**: Custom design minimizes ultrasonic sensor errors and interference between touch and ultrasonic sensors, improving detection accuracy.

## 📐 Technical Specs

- **Programming**: Object-oriented programming with loops, conditionals, and iterative protocols
- **Hardware**: EV3 motors, ultrasonic sensor, touch sensor, encoders
- **Algorithms**:
  - Custom object detection for cylindrical shapes
  - Scalable perimeter and center-detection algorithm
  - Corner navigation ("parallel parking") algorithm to maximize area coverage
- **Performance**:
  - 95% accuracy in object detection and storage
  - 97% accuracy in avoiding walls and obstacles
  - 100% success rate in returning to the starting base during trials

## 🛠️ Development Notes

- **Challenge**: Given the compact size (10"), turning in corners was a challenge, which was overcome by implementing a "parallel parking" maneuver to maximize coverage.
- **Optimization**: Addressed ultrasonic sensor error (3mm per 5") by designing a custom placement to reduce false positives and avoid sensor overlap.

## 🚧 Future Plans: Hercules II

Hercules II is already in development and will introduce:
- SLAM (Simultaneous Localization and Mapping)
- Mapping, graph traversal, and tree structures for more complex environments
- Enhanced navigation with real-time mapping

## 📬 Contact

Feel free to reach out if you'd like to collaborate or learn more about this project:

- **Khalil Ahmad Qamar**  
- [LinkedIn](https://linkedin.com/in/khalil-ahmad-qamar/)  
- [Email](mailto:your.email@example.com)

