EasyCoach Bus Station - Enterprise Network Topology (OSPF)

 📌 Project Overview
This project simulates the **EasyCoach Bus Booking System enterprise network**, connecting multiple regional offices across Kenya (Mombasa, Nakuru, Kisumu, and Nairobi HQ).  

The aim of this project is to model a **scalable, secure, and efficient enterprise network**, applying best practices that would be used in real-world corporate environments.

It was designed in **Cisco Packet Tracer/GNS3** to demonstrate **enterprise-level routing, WAN design, and security**.  

The solution incorporates:
- **Dynamic Routing with OSPFv2**
- **Secure OSPF adjacencies with MD5 authentication**
- **Passive interfaces** for security on user-facing connections
- **Loopback interfaces** to simulate servers/services
- **ISP integration** for external connectivity
- **High availability** using redundant WAN links


🎯 Key Features
- **Dynamic Routing (OSPFv2):**  
  Configured across all routers with MD5 authentication for secure neighbor adjacencies.
  
- **Scalability:**  
  Loopback interfaces simulate future expansions such as additional booking systems or servers.
  
- **Security:**  
  Passive interfaces enabled to prevent routing updates on end-device-facing interfaces.  
  MD5 password authentication ensures OSPF neighbor integrity.

- **High Availability:**  
  Redundant paths between branch routers (ring topology) ensuring failover capability.

- **Branch Integration:**  
  Nairobi HQ connects directly to LAN users via switch (HQ-SW1) and supports booking system access at **192.168.4.0/24**.

- **ISP Connectivity:**  
  SEACOM (ISP) provides external connectivity for future cloud services or intercity bookings.


   Technologies & Tools
- **Cisco Routers:** ISR 4321, 2911

- **Cisco Switches:** Catalyst 2960

- **PCs & End Devices:** Simulated with Packet Tracer

- **Protocols & Configurations:**  

  - OSPFv2 with MD5 Authentication  

  - Static Default Routes (towards ISP)  

  - Loopback Interfaces (Simulated Servers)  
  - Passive Interfaces  
  - Subnetting for WAN & LAN links  

 Skills Demonstrated

 This project demonstrates my ability to **design, configure, and secure enterprise-grade networks** — skills directly applicable to **Network Engineering, Systems Administration, and IT Infrastructure roles**.

✅ Enterprise WAN & LAN Design  
✅ Advanced OSPF Configuration & Authentication  
✅ ISP Peering & Default Routes  
✅ Subnetting & Address Planning  
✅ Security (Passive Interfaces, Authentication)  
✅ Documentation & Network Presentation  

Author

BRADLEY GIOVANNI
Aspiring Network Engineer | CCNA Student | Passionate about Enterprise Networking & Cloud Integration
📧 [giovanniibradley@gmail.com
] | 🌐 [[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/bradley-giovanniii293)
  