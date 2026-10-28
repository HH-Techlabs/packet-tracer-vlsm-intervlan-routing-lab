# Inter-VLAN Routing and VLSM Lab

## Overview

This project demonstrates the implementation of a segmented enterprise network using Cisco Packet Tracer.

Technologies used:

- VLANs
- VLSM (Variable Length Subnet Masking)
- 802.1Q Trunking
- Multilayer Switching
- Inter-VLAN Routing

## Topology

The network contains:

- 1 Cisco 3560 Multilayer Switch
- 6 Cisco 2960 Access Switches
- 6 Department PCs

Departments:

| VLAN | Department |
|------|------------|
| 10 | Finance |
| 20 | Sales |
| 30 | Human Resources |
| 40 | Operations |
| 50 | Executive Management |
| 60 | IT Department |

## VLSM Design

| VLAN | Network |
|------|---------|
| 40 | 10.10.0.0/24 |
| 20 | 10.10.1.0/25 |
| 60 | 10.10.1.128/25 |
| 30 | 10.10.2.0/27 |
| 10 | 10.10.2.32/27 |
| 50 | 10.10.2.64/29 |

## Verification

- VLAN creation verified
- Trunk links verified
- SVI interfaces verified
- Routing table verified
- Cross-VLAN connectivity verified

## Skills Demonstrated

- Cisco IOS CLI
- VLAN Configuration
- Layer 2 Switching
- Layer 3 Switching
- VLSM Subnetting
- Inter-VLAN Routing
- Network Troubleshooting

## Author

HH-Tech

CompTIA A+ | Network+ | Security+

Calgary, Alberta
