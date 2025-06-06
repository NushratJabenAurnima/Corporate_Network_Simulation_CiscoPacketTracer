# 🌐 Corporate Campus Network Simulation using Cisco Packet Tracer

This project simulates a modular, scalable network infrastructure for a large corporate campus using **Cisco Packet Tracer**. It connects five departments via OSPF routing, assigns IP addresses dynamically using DHCP, and centralizes DNS and web services. Browser-based mock systems simulate real corporate processes like onboarding, invoicing, and asset management.



## 📌 Problem Overview

As part of a corporate campus expansion, the objective was to design a robust and expandable network infrastructure across five distinct buildings:

-  Headquarters  
-  Sales Office  
-  Tech Center  
-  Human Resources  
-  Finance Division  

Each building maintains:
- Independent LAN with DHCP server  
- Router with OSPF for dynamic routing  
- Access to centralized services hosted at the Headquarters (DNS and Web Server)



## 🔹 Network Design Overview

- **IP Scheme**: Class A addressing (e.g., 10.0.0.0 – 14.0.0.0)
- **DHCP**: Configured in each LAN to automate IP assignment
- **Routing**: OSPF implemented across all routers for inter-building communication
- **DNS & Web Server**: Located in Headquarters, accessible via `www.campusnet.com`
- **Simulated Business Processes**: Web pages hosted internally for onboarding, asset tracking, and invoice handling



## 🔹 Technologies & Tools

| Category       | Tool / Protocol               |
|----------------|-------------------------------|
| Simulation     | Cisco Packet Tracer (.pkt)    |
| Routing        | OSPF                          |
| IP Allocation  | DHCP                          |
| Services       | DNS, HTTP (Web)               |
| Devices Used   | Routers, Switches, PCs        |



## 🔹 Configuration Summary

### ✅ Router Setup
- Configured with OSPF and proper interfaces for each building
- Interconnected using static and dynamic OSPF routing

### 📶 DHCP Setup
- Five servers auto-assign IPs to clients in each LAN

### 🌍 DNS & Web Server
- Resolves `www.campusnet.com` internally
- Hosts static HTML mock systems for testing



## 🔹 Simulation Outcomes

| Task                                   | Result       |
|----------------------------------------|--------------|
| Ping: Headquarters → Finance           | ✅ Success    |
| Ping: Sales → HR                       | ✅ Success    |
| Ping: Tech → HR                        | ✅ Success    |
| DNS resolution (all PCs)               | ✅ Success    |
| Web page access from all LANs         | ✅ Success    |
| Business process page load             | ✅ Verified   |



## 🔹 Simulated Corporate Systems

-  **Invoice Submission Portal**
-  **Employee Onboarding Form**
-  **Asset Management Dashboard**

These were tested from LAN client PCs via browser interfaces.
