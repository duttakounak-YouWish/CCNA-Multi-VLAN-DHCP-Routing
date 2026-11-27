Project Overview

This project demonstrates the design and configuration of a small enterprise network using Cisco Packet Tracer.

The network consists of three departments: HR, Finance, and IT. Each department is assigned a separate VLAN to provide logical network segmentation.

The project implements DHCP for automatic IP address assignment, trunk links between switches, and inter-VLAN routing through a Cisco router.

Network Topology

- 1 Cisco 2911 Router
- 2 Cisco 2960 Switches
- 9 End Devices (PCs)
- 3 Departmental VLANs

VLAN and IP Addressing

| Department | VLAN ID | Network | Default Gateway |
|---|---:|---|---|
| HR | 10 | 192.168.10.0/24 | 192.168.10.1 |
| FIN | 20 | 192.168.20.0/24 | 192.168.20.1 |
| IT | 30 | 192.168.30.0/24 | 192.168.30.1 |

Technologies and Configuration

- Cisco Packet Tracer
- VLAN creation and segmentation
- Access port configuration
- IEEE 802.1Q trunking
- DHCP configuration on the router
- Inter-VLAN routing
- IPv4 addressing and subnetting
- Network connectivity testing

Implementation

1. Designed the network topology using Cisco Packet Tracer.
2. Configured departmental VLANs on both switches.
3. Assigned switch access ports to the appropriate VLANs.
4. Configured trunk links between network devices.
5. Configured router interfaces for inter-VLAN communication.
6. Created DHCP pools for automatic IP address assignment.
7. Verified network connectivity between departments.

Testing and Verification

The following tests were performed:

| Test | Result |
|---|---|
| DHCP address assignment | Successful |
| Finance PC to Finance gateway | PASS |
| Finance PC to HR gateway | PASS |
| Finance PC to IT gateway | PASS |
| Finance PC to HR PC | PASS |
| HR PC to Finance PC | PASS |
| IT PC to Finance PC | PASS |
| Router interfaces | UP/UP |
| Switch trunk links | Verified |

External connectivity to 8.8.8.8 was not established in this project.

Screenshots

All of the screenshots are in the screenshots folder in the repo itself.

Project Files

- `Multi-VLAN-DHCP-InterVLAN-Routing.pkt` – Cisco Packet Tracer project file.
- `Screenshots/` – Network configuration and testing evidence.

Conclusion

Successfully designed and configured a multi-VLAN network with DHCP and inter-VLAN routing using Cisco Packet Tracer. Verified communication between devices across different departmental VLANs.
