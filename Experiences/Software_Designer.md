# Software Designer - Autonomous Train Perception & Localization

**Period:** 10/2023 - Present  
**Company:** Alstom Transport SA  
**Location:** 3 rue Henri Legay, 69100 Villeurbanne, France

## Context

As part of the Innovation Team at Alstom, I contribute to the development of perception, localization, and decision-making systems for autonomous trains and railway Advanced Driver Assistance Systems (ADAS). My work focuses on the design and implementation of real-time, safety-critical software for obstacle detection, railway environment perception, digital mapping integration, and train guidance. The solutions leverage LiDAR, GNSS, digital maps, and railway geometric models to enable reliable obstacle detection and operational decision support in complex railway environments.

## Responsibilities and achievements

- Designed the software architecture of the Obstacle Detection System (ODS) perception pipeline for railway ADAS and autonomous train applications.
- Designed and implemented a real-time 3D Volume of Interest (VoI) computation framework, dynamically adapting the perception area according to train localization, track position, digital map information, and deterministic railway geometry models based on clothoids and track topology.
- Defined and modeled Areas of Interest (AoI) using digital maps, GNSS data, train localization information, and mathematical railway trajectory models.
- Designed and developed advanced rail detection and localization algorithms from 3D LiDAR point clouds to improve perception robustness and reduce obstacle-detection false positives.
- Developed a rail extraction approach based on LiDAR scan-line processing and 1D signal analysis, enabling accurate rail identification directly from raw point cloud acquisitions.
- Designed and implemented optimization pipelines using Ceres Solver, including custom cost functions, parameter estimation strategies, and numerical optimization techniques to improve localization accuracy and perception performance.
- Developed and maintained high-performance real-time software components in modern C++, covering perception, localization, geometry processing, optimization, and decision-making functionalities.
- Designed the architecture of the Decision Module, responsible for:
  - Providing digital mapping information to the Obstacle Detection System.
  - Interpreting obstacle detection outputs.
  - Generating driver warnings and operational recommendations.
  - Managing acknowledgement workflows and interactions with train operators.
- Implemented the Decision Module from architecture definition through deployment-ready software development.
- Developed automated experimentation and validation tools in Python to perform large-scale hyperparameter exploration, orchestrating iterative execution of C++ algorithms and evaluating performance metrics across multiple datasets.
- Contributed to the signaling detection system within the ARTE project.

## Results

- Deployed and tested a complete perception and decision-support system on a tram operating in commercial urban service in Zurich.
- Validated more than 100 functional and operational scenarios on dedicated test benches and field deployments.
- Achieved a significant reduction in obstacle-detection false positives through rail-aware filtering and contextualized Volume-of-Interest computation (actual performance figures confidential).
- Delivered real-time perception and decision-making software compatible with railway operational and safety constraints.

## Technical environment

- **Programming and software development:** C++ (STL, Eigen, Ceres Solver, OpenCV, ROS2), Python, Git, Linux, CMake, CUDA.
- **Perception and localization:** LiDAR, GNSS & IMU, point cloud processing, digital mapping, railway localization, sensor fusion, SLAM, obstacle detection, rail detection.
- **Mathematics and algorithms:** 3D geometry, numerical optimization, non-linear least squares, cost function design, signal processing, real-time algorithms, deterministic modeling, railway geometry, clothoids.
- **Software architecture and systems engineering:** Real-time systems, distributed software architecture, decision systems, safety-critical software, algorithm design, performance optimization, system integration.
- **Domains:** Autonomous systems, robotics, railway ADAS, autonomous trains, autonomous vehicles (AVs), railway engineering, embedded systems, safety-critical software development.