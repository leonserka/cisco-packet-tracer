# 🌐 Cisco Packet Tracer Labs – Leon Serka

This repository contains a collection of **network simulation exercises** designed using **Cisco Packet Tracer**.  
These labs were created as part of the **Computer Networks** course curriculum to practice network topology design, device configuration, and troubleshooting.

---

## 📘 Overview

The repository documents the progression from basic networking concepts to more complex routing and switching configurations. Each folder corresponds to a specific practice session or chapter, containing `.pkt` simulation files that demonstrate specific networking tasks.

---

## 🧩 Topics Covered

- 🖥️ **Network Design** – Creating topologies with routers, switches, and end devices  
- 🔌 **Basic Configuration** – Hostnames, passwords, console/VTY access  
- 🔢 **IP Addressing** – IPv4 Subnetting and interface configuration  
- 🛣️ **Routing** – Static routing and Dynamic protocols (RIP, OSPF, EIGRP)  
- 🔀 **Switching** – VLANs, Trunking (802.1Q), and Inter-VLAN routing  
- 🛡️ **Security** – ACLs (Access Control Lists) and port security  
- 🌐 **Services** – DHCP, DNS, and NAT configuration  
- 🏆 **Final Project** – Comprehensive group project (Enterprise Network Design)

---

## 🗂️ Project Structure

```
cisco-packet-tracer/
├── practice 1/                        # Network fundamentals
│   ├── Serka_Leon_01_04.pkt           # Basic topology setup
│   ├── Serka_Leon_01_05.pkt           # Cabling and connections
│   └── Serka_Leon_01_06.pkt           # First device configurations
│
├── practice 2/                        # Switch configuration
│   ├── serka_leon_02_12.pkt           # Basic switch settings
│   └── serka_leon_02_13.pkt           # Port security implementation
│
├── practice 3/                        # LAN Design
│   └── Serka_Leon_03.pkt              # Network expansion scenario
│
├── practice 4/                        # Routing basics
│   ├── Serka_Leon_04_25.pkt           # Router interface config
│   └── Serka_Leon_04_27.pkt           # Static routing
│
├── practice 5/                        # Dynamic Routing
│   ├── Serka_Leon_05_30.pkt           # RIPv2 Configuration
│   └── Serka_Leon_05_31.pkt           # OSPF Single Area
│
├── practice 6/                        # VLANs & Trunking
│   ├── Serka_Leon_06_32.pkt           # VLAN creation
│   ├── Serka_Leon_06_33.pkt           # Trunk links assignment
│   └── Serka_Leon_06_34.pkt           # Router-on-a-Stick
│
├── practice 7/                        # Access Control
│   ├── Serka_Leon_07_35.pkt           # Standard ACLs
│   ├── Serka_Leon_07_36.pkt           # Extended ACLs
│   └── Serka_Leon_07_37.pkt           # Named ACLs
│
├── practice 8/                        # Advanced Services (NAT/DHCP)
│   ├── Serka_Leon_08_38.pkt           # DHCP Server setup
│   ├── Serka_Leon_08_39.pkt           # NAT Static/Dynamic
│   ├── Serka_Leon_08_40.pkt           # PAT (Overloading)
│   └── Serka_Leon_08_41.pkt           # Final troubleshooting scenario
│
├── Šerka_Kliškinić/                   # Final Group Project (Defense)
│   ├── Šerka_Kliškinić.pkt            # Full topology simulation
│   ├── Šerka_Kliškinić.pdf            # Project Documentation & Requirements
│   ├── Centralni prospojnik_config.txt# Core Switch Configuration
│   ├── Usmjernik ISP-a_config.txt     # ISP Router Configuration
│   └── (floor_configs)                # Access Switch Configurations
│ 
├── tasks on croatian.pdf              # PDF containing instructions for the tasks
└── Šerka_Leon_obrana.pkt              # Final project / Defense task
```

(Note: File numbers typically reference specific tasks from the course material.)

---

##🚀 How to Run the Simulations
1️⃣ **Install Cisco Packet Tracer** Ensure you have Cisco Packet Tracer installed (Version 8.x recommended).

Download from [Cisco Networking Academy (login required).](https://www.netacad.com/courses/packet-tracer.)

2️⃣ **Open a Lab File** Navigate to the desired folder and double-click the `.pkt` file.

3️⃣ **Interact with the Network** - Click on devices to view CLI configurations.

Use **Simulation Mode** (Shift+S) to visualize packet flow (ICMP, ARP, etc.).

Check the "**Completion**" tab (if applicable) to see the scoring for the activity.

---

##🔧 Final Project – Defense Task
**Project: Enterprise Network Design for "Dijamant" Company** Authors: Leon Serka & Kliškinić

This group project simulates a 3-story office building network with advanced requirements. It integrates multiple technologies into a single, scalable topology.

##🏢 Network Scenario
- **Location**: Varaždin, 3-floor building.
- **Hardware**: 1 Core Layer 3 Switch, 3 Access Layer Switches (one per floor), 1 ISP Router.
- **Departments**: Finance, Service, Marketing, Projects.

##⚙️ Key Configurations implemented:

| Feature | Description |
|------------|-------------|
| **VLAN Segmentation** | 5 distinct VLANs (10, 20, 30, 40, 50) + Management VLAN (1) |
| **Layer 3 Switching** | Core switch handles Inter-VLAN routing (SVI interfaces) |
| **DHCP Services** | Core switch acts as DHCP server for all departments |
| **ISP Connectivity** | Point-to-Point connection to ISP with Static Routing |
| **Security** | Port Security on access switches & SSH configuration |
| **Servers** | Static IP assignment for VLAN 50 (Server Farm) |
---

##🎯 Learning Objectives
- Understand the OSI and TCP/IP models practically
- Master IOS command-line interface (CLI) navigation
- Design scalable and secure network architectures
- Troubleshoot connectivity issues using ping and traceroute
- Prepare for CCNA-level networking tasks

---

##🧠 Technologies Used
- 🖥️ Cisco Packet Tracer 8.x - ⚙️ Cisco IOS (Internetwork Operating System)
- 🔌 Networking Protocols (IPv4, OSPF, RIP, DHCP, DNS, HTTP) 

---

📄 License
This repository is open-source and intended for educational purposes.

---

✍️ Author
Leon Serka
