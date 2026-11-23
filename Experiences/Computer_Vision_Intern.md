# Computer Vision Intern - Autonomous Train Perception - Rail Geometry Estimation & Simulation Framework

**Period:** 02/2023 - 09/2023  
**Company:** Alstom Transport SA  
**Location:** 3 rue Henri Legay, 69100 Villeurbanne, France

## Context

As part of Alstom's Innovation Center, I contributed to the development of obstacle detection systems for autonomous trains. A key challenge was determining the railway corridor ahead of the train to define where obstacles should be searched and tracked.

## Responsibilities and achievements

- Analyzed and qualified the Micro-Mapping algorithm, a rail geometry estimation model used to reconstruct the railway centerline from GNSS measurements.
- Developed a 3D railway trajectory simulator in C++ capable of generating realistic rail geometries from curvature, gradient, and speed profile data.
- Modeled railway trajectories using Frenet-Serret frames, curvature/torsion parameterization, and third-order Taylor expansions.
- Integrated real railway infrastructure data to reproduce realistic operating conditions and benchmark estimation performance.
- Designed and executed a comprehensive testing campaign to study the influence of segmentation, sampling density, initialization, and trajectory geometry on estimation accuracy.
- Investigated algorithm failure modes, particularly around curvature sign changes and inflection points, and proposed architectural improvements.

## Results

- Identified key limitations of the existing rail-position estimation approach and quantified its performance envelope.
- Demonstrated the relationship between trajectory characteristics and estimation parameters, enabling more robust configuration of the algorithm.
- Proposed optimization improvements that reduced trajectory estimation errors by more than 80% in challenging scenarios.
- Delivered findings that contributed to the launch of Alstom's autonomous obstacle detection program and led to a full-time position within the Innovation Team.

## Technical environment

- C++, Python, Linux, Git, GNSS/GPS mapping, railway geometry modeling, Frenet-Serret frames, clothoids, 3D geometry, numerical optimization, mathematical modeling, simulation.