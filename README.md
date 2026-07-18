# Office Network Design and Implementation

## Overview

This project demonstrates the design and implementation of a secure, scalable enterprise office network for a single-story office building using Cisco Packet Tracer. The network was developed to provide reliable wired and wireless connectivity while ensuring high availability, security, and efficient communication between multiple departments.

The solution implements a Collapsed Core Architecture with VLAN segmentation, inter-VLAN routing, network security, redundancy, and centralized network services.

---

## Features

- Enterprise network designed using Cisco Packet Tracer
- Collapsed Core Network Architecture
- VLAN segmentation for departmental isolation
- Inter-VLAN Routing
- DHCP and DNS Server configuration
- Network Address Translation (NAT)
- Access Control Lists (ACLs)
- Cisco ASA Firewall implementation
- SSH Remote Management
- DHCP Snooping
- Port Security
- Guest Wi-Fi Network
- High Availability using HSRP
- Redundant network topology
- Internet connectivity simulation
- Network testing and validation

---

## Network Architecture

The network consists of the following departments:

- Reception
- Offices
- Open Floor Workspace
- Technicians Office
- Meeting Room
- Kitchen (IoT Devices)
- Server Room (Machine Room)
- Guest Wi-Fi Network

Each department is assigned its own VLAN to improve security and reduce broadcast traffic.

| VLAN | Department |
|-------|------------|
| VLAN 10 | Offices |
| VLAN 20 | Reception |
| VLAN 30 | Open Floor |
| VLAN 40 | Technicians |
| VLAN 50 | Meeting Room |
| VLAN 60 | Kitchen (IoT) |
| VLAN 70 | Servers |
| VLAN 80 | Guest Wi-Fi |

---

## Technologies Used

- Cisco Packet Tracer 8.2.2
- Cisco Catalyst 3560 Multilayer Switches
- Cisco Catalyst 2960 Access Switches
- Cisco 2911 Routers
- Cisco ASA 5506-X Firewalls
- DHCP
- DNS
- VLANs
- HSRP
- NAT
- ACLs
- SSH
- Port Security
- DHCP Snooping

---

## Security Features

The network incorporates multiple security mechanisms, including:

- VLAN Segmentation
- Access Control Lists (ACLs)
- Cisco ASA Firewalls
- SSH Secure Remote Access
- DHCP Snooping
- Port Security
- Password Protected Network Devices
- Guest Network Isolation
- Restricted Server Access

---

## High Availability

The network was designed with redundancy to minimize downtime.

Features include:

- Dual Core Switches
- HSRP Gateway Redundancy
- Dual Firewall Deployment
- Redundant Trunk Links
- Multiple Access Switch Connections

---

## Project Objectives

- Design a secure enterprise network
- Provide reliable wired and wireless connectivity
- Improve network scalability
- Implement enterprise-level security
- Enable centralized network management
- Simulate real-world office infrastructure
- Ensure efficient communication between departments

---

## Testing

The following tests were performed:

- Device connectivity testing
- Inter-VLAN communication
- Internet connectivity
- DHCP functionality
- DNS resolution
- Firewall verification
- ACL enforcement
- SSH remote access
- Network redundancy
- File server accessibility

---

## Project Structure

```
Office-Network-Design/
│
├── PacketTracer/
│   └── OfficeNetwork.pkt
│
├── Documentation/
│   └── Group16_Documentation.pdf
│
├── Images/
│   ├── NetworkTopology.png
│   ├── VLANDesign.png
│   └── TestingResults.png
│
└── README.md
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Enterprise Network Design
- Cisco Networking
- Network Security
- VLAN Implementation
- Routing and Switching
- Firewall Configuration
- Network Troubleshooting
- High Availability Design
- Network Documentation
- Cisco Packet Tracer Simulation

---

## Future Improvements

- VPN implementation for remote workers
- Active/Standby Firewall Failover
- Dynamic Routing Protocols (OSPF)
- Network Monitoring using SNMP
- Active Directory Integration
- Wireless Controller Deployment
- Cloud Connectivity
- IPv6 Support

---

## Author

**Mbali Dyobiso**

Bachelor of Science in Information Technology

---

## License

This project was developed for academic purposes and may be used for learning and demonstration purposes.
