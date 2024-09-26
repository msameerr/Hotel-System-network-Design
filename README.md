# 🏨 Hotel System Network Design

This project is a comprehensive network design for a three-floor hotel, each floor housing distinct departments. The network design ensures secure and efficient communication between departments while maintaining segmented network environments through VLANs.

## 🖥️ Project Overview

The network integrates three routers connected through serial DCE cables to facilitate inter-floor routing using specific IP ranges. Each floor consists of:
- A **switch** for wired connections.
- **WiFi networks** for wireless access.
- **VLANs** to securely segment departmental traffic.

Key network features:
- **Dynamic IP assignment** using DHCP configured on routers.
- **OSPF (Open Shortest Path First)** as the primary routing protocol for inter-router communication.
- **SSH (Secure Shell)** implemented across routers for secure remote access and network management.

## 📜 Features

- **Interdepartmental Communication**: Efficient routing between departments using specific IP ranges.
- **VLAN Segmentation**: Isolates departmental traffic for security.
- **DHCP Configuration**: Automates dynamic IP assignment.
- **OSPF Protocol**: Optimizes routing between floors.
- **SSH Security**: Ensures secure remote management of routers.

## 💼 Implementation in Packet Tracer

The network was designed and tested using **Cisco Packet Tracer**, a powerful simulation tool. This project includes:
- **Routing Configuration**: Facilitates communication between different floors.
- **VLANs**: Ensure secure departmental communication.
- **DHCP**: Enables dynamic IP assignment.
- **OSPF**: Configured for optimal route advertisement.
- **SSH**: Implemented for secure remote management.

Cisco Packet Tracer was used to test, troubleshoot, and verify network performance, IP assignments, and security protocols.

## 🛠️ How to Install Cisco Packet Tracer 2019

Follow these steps to install **Cisco Packet Tracer 2019** on your machine:

1. **Download Cisco Packet Tracer**:
   - Go to the official Cisco Networking Academy website: [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
   - Sign up for a free account or log in if you already have one.
   - Download **Packet Tracer 2019** from the "Resources" section.

2. **Install Packet Tracer**:
   - Open the downloaded `.exe` or `.dmg` file for Windows or macOS.
   - Follow the installation prompts.
   - After installation, log in with your Cisco Networking Academy credentials.

3. **Verify Installation**:
   - Open Packet Tracer, create a simple network (e.g., connect a PC to a switch) to verify that it works correctly.

4. **Load the Project**:
   - Open the provided `.pkt` file in Cisco Packet Tracer to explore the hotel’s network design and configuration.

## 📂 Project File

The hotel network design project is saved in a **`.pkt`** file. Open this file in Cisco Packet Tracer to simulate and explore the network settings, including routing, VLANs, DHCP, and SSH configurations.
