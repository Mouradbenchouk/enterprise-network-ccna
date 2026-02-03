# Enterprise Network Design and Simulation (Cisco CCNA)

##  Project Overview
This project demonstrates the design and simulation of a small enterprise network based on Cisco CCNA concepts.  
The goal is to create a secure and well-structured internal network with VLAN segmentation and inter-VLAN routing.

##  Network Topology
- 1 Cisco Router (2911)
- 2 Cisco Switches (2960)
- 4 End Devices (PCs)

##  Technologies & Concepts
- Cisco Packet Tracer
- VLAN Configuration
- Inter-VLAN Routing (Router-on-a-Stick)
- Static IP Addressing
- Basic Network Security
- Connectivity Testing (Ping)

##  VLAN Design
| VLAN ID | Name  | Purpose |
|--------:|-------|---------|
| 10      | ADMIN | Administration |
| 20      | USERS | Employees |

##  IP Addressing
| VLAN | Network | Gateway |
|------|---------|---------|
| 10 | 192.168.10.0/26 | 192.168.10.1 |
| 20 | 192.168.10.64/26 | 192.168.10.65 |

##  Testing & Validation
- Successful connectivity tests between devices in the same VLAN
- Successful inter-VLAN communication verified using ICMP (ping)

##  Files
- Packet Tracer file: `/packet-tracer/enterprise_network_ccna.pkt`
- Network screenshots: `/screenshots/`
- Documentation: `/documentation/project_overview.pdf`

---

 *This project was created as part of my CCNA preparation to strengthen my practical networking skills.*
