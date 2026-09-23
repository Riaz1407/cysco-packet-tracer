# 1. Introduction to Networking Tools and Hardware
Aim
To identify and demonstrate the use of common networking devices and cables in Cisco Packet Tracer.
Requirements
- Cisco Packet Tracer
- PC
- Hub
- Switch
- Router
- Copper Straight-Through Cable
- Copper Cross-Over Cable
Procedure
1. Opened Cisco Packet Tracer.
2. Added PCs, a Hub, Switch and Router to the workspace.
3. Connected the devices using appropriate cables.
4. Observed the function of each networking device.
Devices Used
Device	Function
Hub	Connects multiple devices and broadcasts data to all connected devices.
Switch	Connects devices in a LAN and forwards data to the required device.
Router	Connects different networks and forwards packets between them.
PC	Acts as an end device for sending and receiving data.


Result
The different networking devices were successfully identified and their basic working was demonstrated in Cisco Packet Tracer.
# 2. Straight-Through and Cross-Over Cables
Aim
To understand and implement the appropriate use of straight-through and crossover cables in Cisco Packet Tracer.
Procedure
I created different connections between networking devices and selected the appropriate cable.
Straight-Through Cable
Straight-through cable was used for connecting dissimilar devices, such as:
- PC → Switch
- PC → Hub
- Router → Switch
Example:
PC ───── Straight-Through ───── Switch

Cross-Over Cable
Crossover cable was used for connecting similar devices, such as:
- PC → PC
- Switch → Switch
- Router → Router
Example:
PC ───── Cross-Over ───── PC

Result
The appropriate cables were successfully used to establish connections between the required devices.
# 3. Network Topologies
A. Star Topology ⭐
Aim
To create and test a Star topology using Cisco Packet Tracer.
Devices Used
- 1 Hub
- 5 PCs
- Copper Straight-Through cables
Procedure
I placed one Hub in the center and connected all five PCs directly to the Hub.
             PC0
              |
PC1 ─────── HUB ─────── PC2
              |
             PC3
              |
             PC4

I assigned the following IP addresses:
Device	IP Address	Subnet Mask
PC0	192.168.1.1	255.255.255.0
PC1	192.168.1.2	255.255.255.0
PC2	192.168.1.3	255.255.255.0
PC3	192.168.1.4	255.255.255.0
PC4	192.168.1.5	255.255.255.0


Testing
From PC0, I opened Desktop → Command Prompt and tested the connections using:
ping 192.168.1.2
ping 192.168.1.3
ping 192.168.1.4
ping 192.168.1.5

The ping requests were successfully received.
Result
The Star topology was successfully created and connectivity between the PCs was verified.
B. Bus Topology
Aim
To create and simulate a Bus topology in Cisco Packet Tracer.
Procedure
I created a common communication path and connected the required devices to it. Each computer was connected to the common backbone.
PC0 ── PC1 ── PC2 ── PC3 ── PC4
          Common Backbone

I assigned IP addresses in the same network and tested connectivity using the ping command.
Result
The Bus topology was successfully simulated and connectivity was tested.
C. Ring Topology
Aim
To create and simulate a Ring topology using Cisco Packet Tracer.
Procedure
I connected the devices in a closed loop, where each device was connected to two neighboring devices.
        PC0 ───── PC1
       /            \
     PC4            PC2
       \            /
        ─── PC3 ───

IP addresses were assigned to the devices and connectivity was tested using ping.
Result
The Ring topology was successfully created and tested.
D. Mesh Topology
Aim
To create and simulate a Mesh topology using Cisco Packet Tracer.
Procedure
I connected the devices with multiple links so that there were multiple possible paths between the devices.
PC0 ───────── PC1
 | \          / |
 |  \        /  |
 |   \      /   |
 |    \    /    |
PC2 ───────── PC3

I assigned IP addresses and tested the connectivity between the devices.
Result
The Mesh topology was successfully simulated and connectivity was verified.
# 4. Two LANs Interconnected Through a Router
Aim
To configure two different LANs and connect them using a router in Cisco Packet Tracer.
Devices Used
- 1 Router
- 2 Switches
- 4 PCs
- Copper Straight-Through cables
Topology
LAN 1                         LAN 2

PC0 ─┐                       ┌─ PC2
     ├─ Switch0 ─ Router ─ Switch1 ─┤
PC1 ─┘                       └─ PC3

IP Addressing
LAN 1
Device	IP Address
PC0	192.168.1.2
PC1	192.168.1.3
Router Interface	192.168.1.1


LAN 2
Device	IP Address
PC2	192.168.2.2
PC3	192.168.2.3
Router Interface	192.168.2.1


Subnet mask:
255.255.255.0

Default gateway for LAN 1:
192.168.1.1

Default gateway for LAN 2:
192.168.2.1

Router Configuration
I configured the router interfaces with the respective IP addresses for both LANs.
Testing
From PC0, I tested communication with a PC in the second LAN:
ping 192.168.2.2

If the router and IP configuration are correct, the PC receives replies.
Result
Two separate LANs were successfully configured and interconnected using a router. Connectivity between the two networks was verified using the ping command.
Conclusion
In this practical, I learned how to identify and use basic networking devices, select appropriate cables, create different network topologies, configure IP addresses, and connect two separate LANs using a router in Cisco Packet Tracer.
