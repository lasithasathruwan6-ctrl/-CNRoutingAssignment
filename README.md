# CNRoutingAssignment
This repository contains the Cisco Packet Tracer simulation files (.pkt) completed as part of the Computer Networks module practical assignment. The assignment covers router basic configuration, static routing, and dynamic routing protocols including RIP and EIGRP.

📁 Repository Structure
CNRoutingAssignment/
│
├── Task1_BasicRouterConfig.pkt
├── Task2_StaticRouting.pkt
├── Task3_DynamicRouting.pkt
└── README.md

📌 Task Overview
Task 1 – Basic Router Configuration
This task involves configuring a router with a custom hostname following the format KandyNSBM_StudentID, setting up console access with a password, and enabling console login authentication using Cisco Packet Tracer.
Task 2 – Static Routing Configuration
This task sets up a network topology with three routers named BusinessRouter, ComputingRouter, and ScienceRouter, each connected to a separate LAN network (192.168.1.0/24, 192.168.2.0/24, 192.168.3.0/24). Static routes are manually configured on all routers to enable full communication between all three networks.
Task 3 – Dynamic Routing Configuration
This task uses a three-router topology with KandyNSBM, ColomboNSBM, and GalleNSBM routers connected across two WAN links (14.0.0.0/30 and 15.0.0.0/30) with two LAN networks (172.16.0.0/16 and 173.16.0.0/16).

Part A – RIP Routing: RIP version 2 is configured on all routers to enable dynamic route advertisement and automatic routing between all networks.
Part B – EIGRP Routing: RIP is removed and replaced with EIGRP (AS 100) to demonstrate a more advanced dynamic routing protocol with faster convergence and better path selection.


🛠️ Tools Used

Cisco Packet Tracer 8.x
Cisco 2911 Routers
Cisco 2960-24TT Switches


📄 Submission Details

Module: Computer Networks
Assignment: Router Configuration and Routing Protocols
Institution: NSBM Green University
