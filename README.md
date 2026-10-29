# Enterprise-Network-Infrastructure

🌐 **Enterprise Network Infrastructure Design & Implementation Using Cisco Packet Tracer**

## Overview

Designed and simulated an enterprise network infrastructure using Cisco Packet Tracer, connecting multiple departments through a centralized Core Switch and two Access Switches. The project focuses on VLAN segmentation, inter-VLAN routing, DHCP services, gateway redundancy, and network resilience to provide reliable and organized network connectivity.

## Objectives

To design and implement a scalable and reliable enterprise network that supports multiple VLANs, automates IP address allocation, enables inter-department communication, and improves network availability through redundancy mechanisms.

## 🛠️ Key Stages & Techniques

✅ **VLAN Configuration**

Created separate VLANs for different departments (VLANs 10, 20, and 30), along with a dedicated server VLAN (VLAN 40), to organize network traffic and isolate broadcast domains.

✅ **IPv4 Addressing**

Designed a structured IPv4 addressing scheme using separate `/24` subnets for each VLAN, simplifying device addressing and network management.

✅ **VTP Configuration**

Configured the Core Switch as the VTP server and the Access Switches as VTP clients to simplify VLAN management across the switching infrastructure.

✅ **802.1Q Trunking**

Configured trunk links between switches and routers to carry traffic from multiple VLANs across the network infrastructure.

✅ **Inter-VLAN Routing**

Implemented Router-on-a-Stick (ROAS) on both routers using subinterfaces to enable communication between different VLANs.

✅ **HSRP Gateway Redundancy**

Configured Hot Standby Router Protocol (HSRP) to provide a virtual default gateway and support gateway redundancy between the two routers.

✅ **DHCP Configuration**

Configured DHCP services on the routers for selected VLANs and used a dedicated DHCP server for another VLAN to automate IP address assignment.

✅ **Spanning Tree Protocol (STP)**

Configured Per-VLAN Spanning Tree (PVST) and assigned the Core Switch as the intended root bridge, with the Access Switches configured as secondary root bridges to help prevent Layer 2 loops.

✅ **Switch Port Security**

Configured Port Security on end-device access ports using sticky MAC address learning, maximum MAC address limits, and violation shutdown to restrict unauthorized device connections.

✅ **Unused Port Protection**

Assigned unused switch ports to a dedicated VLAN and administratively disabled them to reduce unauthorized access risks.

✅ **Network Verification & Troubleshooting**

Verified VLAN membership, trunk operation, routing, DHCP address assignment, HSRP status, STP behavior, and end-to-end connectivity using Cisco IOS commands and ping tests.

## 🎯 Project Outcomes

✅ Implemented a multi-VLAN enterprise network architecture

✅ Enabled inter-VLAN communication through Router-on-a-Stick

✅ Automated IP address assignment using router-based and server-based DHCP

✅ Implemented default gateway redundancy using HSRP

✅ Improved Layer 2 loop prevention using PVST

✅ Strengthened access-layer security using Port Security

✅ Practiced network verification and troubleshooting using Cisco IOS commands

## 🎓 Project Context

A hands-on networking project developed using Cisco Packet Tracer to apply CCNA concepts in enterprise network design, switching, routing, DHCP, redundancy, and basic network security. The project demonstrates practical experience in configuring, verifying, and troubleshooting a multi-VLAN network infrastructure.
