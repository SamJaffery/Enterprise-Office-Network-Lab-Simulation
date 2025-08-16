# Enterprise-Office-Network-Lab-Simulation
This project is a simulation of an enterprise office network featuring IP Telephony, IoT device integration, and remote access management. It demonstrates how modern enterprises can implement unified communications and smart office automation within a secure and scalable network design.
🔹 Project Overview

IP Telephony Service (VoIP) configured across multiple office floors using Cisco IP Phones.

IoT Devices (Smart Lights, Fans, Air Conditioners, Doors) fully integrated into the network and accessible remotely from any office computer.

Centralized Server Room with:

Main Router & Switch

CUCM (Call Manager) / IP Telephony Server

DHCP, DNS services

Multi-Floor Setup – Floor 1, Floor 2, and Floor 3 with individual switches, laptops, and IP Phones connected.

Remote Access configured for IoT management and monitoring.

🔹 Technologies & Protocols Used

Routing & Switching – VLANs, Inter-VLAN Routing

IP Telephony (VoIP) – SIP / SCCP Protocols

DHCP – Automatic IP addressing for phones & IoT devices

DNS – Name resolution within the network

IoT Device Management – Remote control via PCs

Security – Basic access control for safe device management

🔹 Network Topology

📌 The network is designed with a centralized star topology, connecting all floors and the server room.

Server Room: Router, Main Switch, IP Telephony Server

Floor 1: Switch, IP Phones, Laptops, IoT Devices (Lights, Fan, AC)

Floor 2: Switch, IP Phones, Laptops, IoT Devices (Lights, Fan, AC, Door)

Floor 3: Switch, IP Phones, Laptops, IoT Devices (Lights, Fan, AC, Door)

(See diagram in repository for details)

🔹 Key Features

✅ Seamless voice communication across the enterprise network

✅ IoT device control from any connected PC

✅ Remote accessibility for monitoring and management

✅ Scalable design suitable for enterprise-level deployments


🚀 How to Use

Open the project in Cisco Packet Tracer.

Load PacketTracerFile.pkt.

Explore different floors, IP Phones, and IoT devices.

Test IP Telephony calls between phones.

Control IoT devices from any office computer.

📌 Future Enhancements

🔧 Implement advanced VoIP features (Voicemail, Call Forwarding).

🔧 Add firewall & VPN configurations for secure remote access.

🔧 Automate IoT control using Python & REST APIs.

💡 Author

👨‍💻 Designed & implemented by Syed Ahmed Ali Murtaza
📌 Network Engineer | IP Telephony | IoT | Cisco Enthusiast
Linkdin: www.linkedin.com/in/syed-ahmed-ali-murtaza-69358728b

⭐ If you find this project useful, feel free to star this repo and connect with me!
