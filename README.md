# drone-docs

Open-source drone documentation, resources, and guides organized by topic.

## Overview

This repository centralizes drone-related documentation, open-source projects, control systems, ROS integration, GPS navigation, telemetry, simulation, and multi-drone swarm systems.

## Drone Swarm topic overview

The GitHub topic `drone-swarm` groups repositories focused on collaborative multi-drone systems. These projects usually explore how multiple drones coordinate actions, share state, avoid collisions, and accomplish missions that a single drone cannot handle efficiently.

### Core concepts

- Drone swarm: a coordinated group of drones acting as a collective system.
- Decentralized coordination: decision-making is distributed across the swarm rather than centralized in a single controller.
- Communication: reliable real-time exchange of telemetry and commands between drones and ground stations.
- Collision avoidance: path planning and dynamic obstacle management for multiple agents.
- Distributed autonomy: each drone can react locally while the full swarm maintains a global objective.
- Multi-agent planning: route optimization, formation control, and mission scheduling.

### Typical use cases

- Light shows and artistic drone formations
- Search and rescue operations
- Mapping and aerial survey
- Infrastructure inspection
- Environmental monitoring
- Multi-target tracking and surveillance
- Scientific experiments with coordinated autonomous fleets
- Simulation and research on swarm intelligence and AI-driven coordination

## Main repositories in the drone-swarm topic

### 1. alireza787b/mavsdk_drone_show

MAVLink-based open-source framework for swarm and multi-drone mission management. Useful for drone shows, swarm orchestration, planning, and telemetry validation.

- Repository: https://github.com/alireza787b/mavsdk_drone_show

### 2. skybrush-io/skybrush-server

Server and tooling for managing synchronized multi-drone light shows. Designed around swarm choreography and coordinated flight control.

- Repository: https://github.com/skybrush-io/skybrush-server

### 3. machmind-dev/drone-swarm-challenge-2026

ROS 2 and multi-agent swarm challenge project with five-drone autonomy, architecture documentation, and hardware/software integration around open-source robotics frameworks.

- Repository: https://github.com/machmind-dev/drone-swarm-challenge-2026
- Related discussion: https://discourse.openrobotics.org/t/swarm-drone-challenge-2026-5-drone-swarm-open-sourced-uros-ros2/55467

### 4. koesan/ORCUS

Multi-drone project focused on autonomous surveillance, target engagement, ArduPilot simulation, ROS + Gazebo integration, and AI-powered vision.

- Repository: https://github.com/koesan/ORCUS

### 5. micros-uav/CoFlyers

General-purpose MATLAB/Simulink framework for collective flight and swarm behavior research.

- Repository: https://github.com/micros-uav/CoFlyers

### 6. smshagor-dev/UVA-GPS-Denied-Navigation-in-Dynamic-Environments

Drone swarm project addressing GPS-denied navigation, dynamic environments, distributed perception and navigation strategies.

- Repository: https://github.com/smshagor-dev/UVA-GPS-Denied-Navigation-in-Dynamic-Environments

### 7. Additional related resources

- Drone swarm GitHub topic: https://github.com/topics/drone-swarm
- Droneswarm topic: https://github.com/topics/droneswarm
- Autonomous Drone Swarms: Python and ROS 2 guide: https://markaicode.com/autonomous-drone-swarms-python-ros2-guide/
- Research paper: https://arxiv.org/pdf/2510.27327

## Key technology stack for drone swarms

Common components in swarm projects include:

- PX4 and ArduPilot for flight control
- MAVLink for telemetry and command exchange
- ROS 2 / micro-ROS for distributed robotics systems
- Gazebo and AirSim for simulation
- AI and multi-agent planning for autonomous behavior
- Vision sensors, lidar, and localization systems

## Recommended reading

- [Drone swarm detailed guide](docs/08-essaims-drones.md)
- [Open-source projects overview](docs/10-projets-open-source.md)
- [EU drone regulation overview](docs/09-reglementation.md)

## Main documentation

- [Introduction to drones](docs/01-introduction.md)
- [Drone components](docs/02-composants-drone.md)
- [Autopilots](docs/03-autopilotes.md)
- [GPS navigation](docs/04-pilotage-gps-navigation.md)
- [Telemetry and sensors](docs/05-telemetrie-capteurs.md)
- [ROS and programming](docs/06-ros-programmation.md)
- [Simulation](docs/07-simulation.md)
- [Drone swarms](docs/08-essaims-drones.md)
- [Regulation](docs/09-reglementation.md)
- [Open-source projects](docs/10-projets-open-source.md)

## Quick start

1. Learn the basic drone architecture.
2. Choose a control stack: PX4 or ArduPilot.
3. Study computer vision and localization.
4. Learn ROS 2 and MAVLink.
5. Prototype a small swarm in simulation.
6. Move to real-world tests with safety constraints.
7. Respect local regulatory rules.

## License

This project is published under the MIT license.

## Contributing

See CONTRIBUTING.md.
