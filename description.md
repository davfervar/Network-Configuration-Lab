# Network Engineering & Administration Lab Portfolio

This repository contains a collection of network labs completed as part of my networking studies. These labs demonstrate my hands-on experience with fundamental and advanced networking concepts using Cisco Packet Tracer. Each lab includes documentation, configuration files, and screenshots showcasing the successful implementation of various network topologies and protocols.

## Table of Contents

1.  [About This Portfolio](#about-this-portfolio)
2.  [Skills Demonstrated](#skills-demonstrated)
3.  [Lab Summaries](#lab-summaries)
    * [Lab 2: OSI Model & Cabling](#lab-2-osi-model--cabling)
    * [Lab 3: Local Area Network (LAN) Configuration](#lab-3-local-area-network-lan-configuration)
    * [Lab 4: VLANs and Trunking](#lab-4-vlans-and-trunking)
    * [Lab 5: Inter-VLAN Routing with Sub-Interfaces](#lab-5-inter-vlan-routing-with-sub-interfaces)
    * [Lab 6: Static Routing Across Multiple Networks](#lab-6-static-routing-across-multiple-networks)
    * [Lab 8: IPv6 Implementation](#lab-8-ipv6-implementation)
4.  [How to Use This Repository](#how-to-use-this-repository)

## About This Portfolio

The purpose of this portfolio is to provide tangible evidence of my skills in network design, configuration, and troubleshooting. The labs herein cover a foundational curriculum in network administration, from physical layer connectivity to complex routing and switching configurations. [cite_start]All labs were built, configured, and verified remotely using Cisco Packet Tracer. [cite: 1, 280, 515, 900, 967]

---

## Skills Demonstrated

Across these labs, I have gained and demonstrated proficiency in the following areas:

* [cite_start]**Network Fundamentals:** OSI Model [cite: 924, 925, 926, 927, 928, 929, 930][cite_start], TCP/IP Suite (TCP & UDP) [cite: 744, 747][cite_start], IP Addressing (IPv4 & IPv6) [cite: 493, 498][cite_start], and Subnetting[cite: 899, 1250].
* **Switching Technologies:**
    * [cite_start]VLAN creation and management for network segmentation. [cite: 276, 1094, 1099, 1101]
    * [cite_start]Configuration of trunk ports (IEEE 802.1Q) to carry traffic for multiple VLANs. [cite: 265, 271, 1245]
    * [cite_start]Assigning switch ports to specific VLANs. [cite: 897]
* **Routing Protocols & Configuration:**
    * [cite_start]Configuration of router sub-interfaces for Inter-VLAN routing ("Router on a Stick"). [cite: 1239]
    * [cite_start]Implementation of static and default routes (`0.0.0.0/0`) to connect disparate networks. [cite: 605, 780, 783]
    * [cite_start]Basic router interface configuration (IP addresses, subnet masks). [cite: 892, 893]
* [cite_start]**IP Services:** Understanding the role of DHCP for automatic IP assignment versus static addressing. [cite: 887]
* **Network Tools & Troubleshooting:**
    * [cite_start]Using `ping` and `traceroute` to verify connectivity and test network paths. [cite: 953]
    * [cite_start]Using Cisco IOS `show` commands (`show ip interface brief`, `show vlan`, `show ip route`) to verify configurations and troubleshoot issues. [cite: 150, 162, 594, 725, 878, 1241, 1243]

---

## Lab Summaries

### Lab 2: OSI Model & Cabling

* [cite_start]**Description:** This foundational lab covered the 7 layers of the OSI model and physical network connectivity. [cite: 924, 925, 926, 927, 928, 929, 930] [cite_start]It involved creating network cables (patch and crossover) and establishing a direct PC-to-PC connection to test with the `ping` command. [cite: 936, 947, 953]
* [cite_start]**Key Concepts:** OSI Model, physical media (wired, wireless) [cite: 932, 933][cite_start], T-568B wiring standard [cite: 936][cite_start], use of crossover cables [cite: 947][cite_start], and basic connectivity testing. [cite: 953]

### Lab 3: Local Area Network (LAN) Configuration

* [cite_start]**Description:** This lab involved setting up a basic small office/home office (SOHO) network. [cite: 792] [cite_start]A Cisco router was configured as the gateway, and a multilayer switch was used to connect multiple PCs. [cite: 792]
* [cite_start]**Key Concepts:** IP addressing on a router interface [cite: 893][cite_start], basic switch port configuration [cite: 896][cite_start], static vs. DHCP addressing [cite: 887][cite_start], and entering privileged EXEC mode (`enable`). [cite: 889]

### Lab 4: VLANs and Trunking

* [cite_start]**Description:** This lab demonstrated how to logically segment a network into two separate broadcast domains (VLAN 10 and VLAN 20) using a single switch. [cite: 276] A trunk port was configured to connect two switches, allowing hosts on the same VLAN to communicate across different physical devices.
* [cite_start]**Key Concepts:** VLAN creation [cite: 276][cite_start], port assignment [cite: 142, 143][cite_start], trunk ports [cite: 265][cite_start], and the IEEE 802.1Q standard. [cite: 271] [cite_start]The default VLAN is VLAN 1. [cite: 263]

### Lab 5: Inter-VLAN Routing with Sub-Interfaces

* **Description:** Building on the previous lab, this exercise introduced the "Router on a Stick" model. [cite_start]A single physical router interface was configured with multiple sub-interfaces, each acting as the default gateway for a different VLAN. [cite: 1239]
* [cite_start]**Key Concepts:** Sub-interface configuration [cite: 1239][cite_start], VLAN tagging at Layer 2[cite: 273], and enabling communication between different VLANs through a router.

### Lab 6: Static Routing Across Multiple Networks

* **Description:** This lab demonstrated how to connect two separate networks using static routing. [cite_start]Two routers were connected via their serial interfaces, and default static routes were configured to forward any traffic with an unknown destination to the other network. [cite: 783]
* [cite_start]**Key Concepts:** Static vs. dynamic routing, configuring a default route (`0.0.0.0 0.0.0.0`) [cite: 782][cite_start], understanding the "Gateway of last resort" [cite: 786][cite_start], and comparing TCP (reliable) with UDP (fast, connectionless). [cite: 750, 751]

### Lab 8: IPv6 Implementation

* **Description:** This lab focused on the fundamentals of IPv6, the successor to IPv4. It covered the key differences, address structure, and abbreviation methods.
* [cite_start]**Key Concepts:** IPv6 address space (128-bit) [cite: 498][cite_start], key advantages over IPv4 (no NAT, built-in IPsec) [cite: 499][cite_start], and methods for shortening IPv6 addresses (omitting leading zeros, using `::`). [cite: 505, 506]

## How to Use This Repository

Each lab folder contains the original PDF with instructions and screenshots of the completed work. The goal is to clearly document the process and outcome of each exercise. For any questions, feel free to reach out.
