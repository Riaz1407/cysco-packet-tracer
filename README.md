# 🌐 Network Topologies using Cisco Packet Tracer

This repository contains different **computer network topologies** created and configured using **Cisco Packet Tracer** as part of a networking assignment.

## 📌 Objective

The objective of this assignment is to understand and implement different types of network topologies using Cisco Packet Tracer and verify connectivity between the connected devices using the **Ping command**.

## 🛠️ Software Used

- **Cisco Packet Tracer**
- **Command Prompt / CLI**
- **Git & GitHub**

## 📚 Topologies Implemented

The following network topologies are included in this repository:

1. ⭐ **Star Topology**
2. 🔗 **Bus Topology**
3. 🔄 **Ring Topology**
4. 🕸️ **Mesh Topology**
5. 🌳 **Tree Topology**

## ⭐ 1. Star Topology

In a Star Topology, all computers/devices are connected to a **central switch**.

### Devices Used

- 1 × Switch
- Multiple × PCs
- Ethernet cables

### Configuration

Each PC is assigned a unique IP address in the same network.

Example:

| Device | IP Address  | Subnet Mask   |
| ------ | ----------- | ------------- |
| PC1    | 192.168.1.1 | 255.255.255.0 |
| PC2    | 192.168.1.2 | 255.255.255.0 |
| PC3    | 192.168.1.3 | 255.255.255.0 |
| PC4    | 192.168.1.4 | 255.255.255.0 |

### Connectivity Test

Connectivity can be verified using the `ping` command.

```bash
ping 192.168.1.2
```

A successful reply confirms that the devices can communicate with each other.

## 🔗 2. Bus Topology

Bus topology connects multiple devices through a common communication path.

The topology is implemented in Cisco Packet Tracer using appropriate networking devices and connections.

## 🔄 3. Ring Topology

In Ring Topology, each device is connected to two other devices, forming a closed loop.

The topology is created and tested in Cisco Packet Tracer.

## 🕸️ 4. Mesh Topology

In Mesh Topology, devices have multiple connections with other devices, providing multiple communication paths.

The topology is configured and connectivity is tested using the `ping` command.

## 🌳 5. Tree Topology

Tree Topology combines characteristics of star and hierarchical topologies.

Devices are arranged in multiple levels with switches connecting different sections of the network.

## 🔀 6. Hybrid Topology

Hybrid Topology is a combination of two or more different network topologies.

The topology is designed and tested using Cisco Packet Tracer.

## 🎯 Learning Outcomes

Through this assignment, I learned:

- Different types of network topologies
- How to create network topologies in Cisco Packet Tracer
- Connecting PCs, switches, and other networking devices
- Assigning IP addresses to devices
- Testing network connectivity using the `ping` command
- Understanding how different topologies affect network communication
- Basic network troubleshooting

## 📸 Screenshots

Screenshots of each implemented topology and successful connectivity tests are included in their respective folders.



⭐ *This repository was created for academic and learning purposes.*
