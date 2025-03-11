# SWARM-X

## System for Wireless Autonomous Resource Management and eXecution

### Overview

SWARM-X is a comprehensive, cross-platform system designed to manage, simulate, and execute tasks for autonomous groups. Initially developed for UAV swarms, SWARM-X is built to be a **universal task management platform**, adaptable to various autonomous systems, including robotic fleets, industrial automation, and smart infrastructure. Its modular architecture and extensible design make it **easy to enhance and integrate with other autonomous solutions**, ensuring flexibility across diverse use cases.

## Key Features

- 🚀 **Multi-User & Multi-Server**: Supports independent client applications and multiple microservices.
- 🔄 **Versatile Task Management & Simulation**: Organizes, simulates, and executes tasks for various autonomous agents, from UAVs to ground robots and IoT networks.
- 🔒 **Secure & Efficient Networking**: Provides a standardized API library for communication between client and server, utilizing modern security techniques.
- 🖥 **Cross-Platform Support**: Runs on Windows, Linux, and macOS, enabling real-time collaboration from anywhere in the world.
- ⚡ **Decentralized Execution**: Autonomous agents can function independently without relying on a central cloud, making them adaptable to real-world dynamic conditions.
- 📊 **Graph-Based Path Optimization**: Implements Eulerian graphs and rotor-router algorithms to optimize movement paths, ensuring full coverage while minimizing resource consumption.
- 📡 **Resilient Communication**: Uses gossip and broadcast algorithms for secure data exchange between autonomous agents, ensuring operational continuity.
- 🌍 **3D Mapping & Processing**: Integrates OpenDroneMap to generate high-resolution 3D panoramic maps from image data, supporting applications in disaster response, environmental monitoring, industrial inspections, and security.

## Why SWARM-X?

Unlike conventional task management solutions, **SWARM-X is designed as a universal and adaptable platform** for autonomous resource coordination. Whether managing UAV missions, robotic fleets, or industrial automation systems, SWARM-X provides a **scalable, secure, and modular** architecture that supports real-time decision-making and efficient execution.

## Use Cases

- 🤖 **Autonomous Robotics**: Manage and coordinate robotic fleets in warehouses, manufacturing, and logistics.
- 🔍 **Aerial & Ground Surveillance**: Deploy autonomous systems for security, reconnaissance, and large-area monitoring.
- 🚨 **Disaster Response & Environmental Analysis**: Capture real-time 3D maps for situational awareness and resource allocation.
- 🏔 **Scientific Exploration & Research**: Coordinate autonomous exploration in extreme or hazardous environments.

## 🚀 Technology Stack

- **Programming Language**: Modern C++ (C++17/20) with Qt framework.
- **Networking**: Standardized API library for communication between client and server.
- **Graph Processing**: Eulerian graphs, rotor-router algorithms for path optimization.
- **Mapping & Visualization**: OpenDroneMap for 3D mapping and image processing.

## 📌 Get Started

```bash
# Clone the Repository
git clone https://github.com/LazyanArtyom/swarm-x.git
cd swarm-x

# Debug build
mkdir -p build/debug
cmake -S . -B build/debug -DCMAKE_BUILD_TYPE=Debug
cmake --build build/debug

# Release build
mkdir -p build/release
cmake -S . -B build/release -DCMAKE_BUILD_TYPE=Release
cmake --build build/release
```
