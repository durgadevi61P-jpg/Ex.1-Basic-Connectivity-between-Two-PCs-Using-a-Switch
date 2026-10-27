Ex. No 1. Basic Connectivity between Two PCs Using a Switch
Date : 15.10.2026
Objective
      “To configure and test basic LAN connectivity between two PCs using a switch.”
Apparatus/Tools Required
• Cisco Packet Tracer Software • Devices: PCs, Switch, Router, Cables • Optional: Wireless Router, Server, Cloud

Network Topology Diagram
<img width="1920" height="1200" alt="Screenshot (344)" src="https://github.com/user-attachments/assets/46741c0d-ebfb-405c-8c2e-f929b99135c8" />

IP Addressing Table (if applicable)
Device Name Interface IP Address Subnet Mask PC0 NIC 192.168.1.2 255.255.255.0 PC1 NIC 192.168.1.3 255.255.255.0 Router0 Fa0/0 192.168.1.1 255.255.255.0

Procedure
Step-by-step commands/configurations. Example:

Open Cisco Packet Tracer and add two PCs and one Switch.
Connect the PCs to the switch using straight-through cables.
Assign IP addresses to the PCs.
Use the ping command to verify connectivity.
Commands Used (if any)
For PC IP assignment:
nginx
CopyEdit
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0
For Router Configuration (CLI):

Output (Screenshots / Ping Results)

<img width="1535" height="766" alt="Screenshot 2026-10-27 173424" src="https://github.com/user-attachments/assets/02b7c78d-8fef-42d9-8ac0-fccb01fde481" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/ff223be1-2b7f-4408-a234-3bcdbcacfd01" />

<img width="1535" height="683" alt="image" src="https://github.com/user-attachments/assets/817b0580-f573-493f-a717-444feb78accc" />
<img width="1535" height="937" alt="image" src="https://github.com/user-attachments/assets/cf5e9d3e-14a7-4084-b3c6-9e97a1f437a2" />



Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
