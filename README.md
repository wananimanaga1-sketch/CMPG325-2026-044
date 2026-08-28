# CMPG325-2026-044

## CMPG 325 – Computer Networks Semester Project

**Client:** Kgalagadi Transport Solutions (Klerksdorp)  
**Industry:** Logistics  
**Project ID:** CMPG325-2026-044  
**Client ID:** CLI-044  
**Assigned IPv4 Block:** 10.24.0.0/16

## Project Overview

This project involves the design and simulation of a computer network for Kgalagadi Transport Solutions in Klerksdorp. The network is designed to provide reliable connectivity, network segmentation, secure communication, and support for the organisation's office, logistics, CCTV, server, and management infrastructure.

The network design uses VLAN segmentation and a Layer 3 core switch to provide inter-VLAN routing. The addressing plan supports both IPv4 and IPv6.

## Network Segmentation

| VLAN | Department | IPv4 Network | IPv4 Gateway | IPv6 Network |
|------|------------|--------------|--------------|--------------|
| 10 | Office | 10.24.10.0/24 | 10.24.10.1 | 2001:db8:24:10::/64 |
| 20 | Logistics | 10.24.20.0/24 | 10.24.20.1 | 2001:db8:24:20::/64 |
| 30 | CCTV | 10.24.30.0/24 | 10.24.30.1 | 2001:db8:24:30::/64 |
| 40 | Servers | 10.24.40.0/24 | 10.24.40.1 | 2001:db8:24:40::/64 |
| 50 | Management | 10.24.50.0/24 | 10.24.50.1 | 2001:db8:24:50::/64 |

## Milestone 1 – Client Design Review

This repository contains the initial network design documentation:

1. **01_Client_Requirements** – Client requirements and network needs.
2. **02_Physical_Topology** – Physical network topology design.
3. **03_Logical_Topology** – Logical topology showing VLAN segmentation and addressing.
4. **04_IP_Addressing** – IPv4 and IPv6 addressing plan.

## Proposed Network Design

The proposed network includes:

- Dual Internet/ISP connectivity
- Two edge routers
- Layer 3 core switch
- Inter-VLAN routing
- Office access network
- Logistics access network
- CCTV network
- Server network
- Management VLAN
- IPv4 and IPv6 dual-stack addressing

## Tools

- Cisco Packet Tracer
- diagrams.net (draw.io)
- Microsoft Excel
- GitHub

## Project Status

**Milestone 1 – Client Design Review: Completed**
