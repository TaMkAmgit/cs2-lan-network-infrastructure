# CS2 LAN Infrastructure — Huawei eNSP

## Project Overview

This project demonstrates the design and configuration of a network infrastructure for a Counter-Strike 2 LAN tournament, inspired by PGL Astana.

The infrastructure was simulated using Huawei eNSP.

## Implemented Technologies

- VLAN Segmentation
- Ether-Trunk
- RSTP
- Router-on-a-Stick
- DHCP
- OSPF
- ACL
- FTP
- PPPoE
- NAT
- IPv4 / IPv6
- OSPFv3

## Network Architecture

The network uses a hierarchical topology with a central Core Switch. Separate VLANs provide logical segmentation for players, administrators, casters, spectators, and game servers.

## Testing

Connectivity and routing were tested using ICMP Ping between network segments and devices.

## Requirements

- Huawei eNSP
- Compatible Oracle VirtualBox version
- Windows environment

**Note:** The project was developed and tested in a compatible Huawei eNSP and VirtualBox environment. The exact software versions should be verified before running the topology.


## Project Structure

```text
cs2-lan-network-infrastructure/
├── screenshots/
├── CS2-eNSP-Project.zip
├── SET' FINALEXAM.pdf
├── SET' FINALEXAM.pptx
└── README.md
```
<img width="1520" height="850" alt="scr1" src="https://github.com/user-attachments/assets/01f8beb0-085b-4615-9242-63dfc34d8093" />


## Author

Tamerlan Kamaliyev
