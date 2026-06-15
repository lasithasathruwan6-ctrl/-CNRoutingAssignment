# CNRoutingAssignment
🌐 CNRoutingAssignment
![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Module](https://img.shields.io/badge/Module-Computer%20Networks-green?style=for-the-badge)
![Institution](https://img.shields.io/badge/Institution-NSBM%20Green%20University-brightgreen?style=for-the-badge)
> Practical Assignment on Router Configuration and Routing Protocols using Cisco Packet Tracer — covering Static Routing, RIP, and EIGRP.
---
📁 Repository Structure
```
CNRoutingAssignment/
│
├── 📄 Task1_BasicConfig_39132.pkt        # Basic Router Configuration
├── 📄 Task2_StaticRouting_39132.pkt      # Static Routing Configuration
├── 📄 Task3_DynamicRouting_39132.pkt     # RIP & EIGRP Dynamic Routing
└── 📄 README.md
```
---
📌 Task Overview
✅ Task 1 – Basic Router Configuration `(5 Marks)`
Configured a Cisco 2911 router with the following:
Custom hostname set to `KandyNSBM_StudentID` format
Console access secured with the password `NSBM`
Console login authentication enabled
---
✅ Task 2 – Static Routing Configuration `(10 Marks)`
Built a three-router topology and manually configured static routes to enable full inter-network communication.
Router	LAN Network	Role
BusinessRouter	192.168.2.0/24	Center Router
ComputingRouter	192.168.1.0/24	Left Router
ScienceRouter	192.168.3.0/24	Right Router
WAN Links:
BusinessRouter ↔ ComputingRouter : `12.0.0.0/30`
BusinessRouter ↔ ScienceRouter : `10.0.0.0/30`
ComputingRouter ↔ ScienceRouter : `11.0.0.0/30`
Verified Connectivity:
✔️ Network A ↔ Network B
✔️ Network A ↔ Network C
✔️ Network B ↔ Network C
---
✅ Task 3 – Dynamic Routing Configuration `(15 Marks)`
Used a three-router topology with the following setup:
Router	LAN Network
KandyNSBM	172.16.0.0/16
ColomboNSBM	Transit Router
GalleNSBM	173.16.0.0/16
WAN Links:
KandyNSBM ↔ ColomboNSBM : `14.0.0.0/30`
ColomboNSBM ↔ GalleNSBM : `15.0.0.0/30`
🔁 Part A – RIP Routing `(7 Marks)`
Configured RIP Version 2 on all three routers
Declared all directly connected networks using the `network` command
Disabled auto-summary using `no auto-summary`
Verified routing tables and confirmed successful ping between all networks
⚡ Part B – EIGRP Routing `(8 Marks)`
Removed RIP configuration using `no router rip`
Configured EIGRP (AS 100) on all three routers
Used wildcard masks with the `network` command for precise advertisement
Verified EIGRP neighbor relationships and routing tables
Confirmed full connectivity between all networks via ping tests
---
🛠️ Tools & Equipment Used
Tool	Details
Simulation Software	Cisco Packet Tracer 8.x
Router Model	Cisco 2911
Switch Model	Cisco 2960-24TT
End Devices	PC-PT
---
📋 Marking Scheme
Task	Marks
Task 1 – Basic Router Configuration	5
Task 2 – Static Routing	10
Task 3 – RIP Routing	7
Task 3 – EIGRP Routing	8
Report Quality & Documentation	5
Total	35
---
📄 Submission Details
Field	Details
Module	Computer Networks
Assignment	Router Configuration and Routing Protocols
Institution	NSBM Green University
Deadline	15th June – 11:59 PM
---
> 💡 *All .pkt files can be opened using Cisco Packet Tracer 8.0 or above.*
