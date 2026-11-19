DHCP Server Configuration – Cisco Packet Tracer

1. Project Overview

This project demonstrates the configuration of a DHCP (Dynamic Host Configuration Protocol) Server using Cisco Packet Tracer.

A dedicated Server is configured to automatically assign IP addresses to connected PCs and laptops through a Cisco 2960 switch.

2. Network Topology

Devices Used:

- 1 Cisco 2960 Switch
- 1 Server (DHCP Server)
- 3 Desktop PCs
- 3 Laptops

3. Network Configuration

Parameter| Value
Network Address| 192.168.1.0
Subnet Mask| 255.255.255.0
Server IP| 192.168.1.2
DHCP Pool Name| LAN_POOL
Starting IP| 192.168.1.10
DNS Server| 8.8.8.8
Maximum Users| 100
Default Gateway| Not configured

4. DHCP Server Configuration

1. Open Server0.
2. Navigate to Desktop → IP Configuration.
3. Assign a static IP address to the server.
4. Open Services → DHCP.
5. Turn DHCP service ON.
6. Configure the DHCP pool:
   - Pool Name: LAN_POOL
   - Default Gateway: 0.0.0.0
   - DNS Server: 8.8.8.8
   - Start IP Address: 192.168.1.10
   - Subnet Mask: 255.255.255.0
   - Maximum Users: 100
7. Click Add or Save.

5. Client Configuration

Repeat these steps on all PCs and laptops:

1. Open the client device.
2. Select Desktop.
3. Open IP Configuration.
4. Select DHCP.
5. Verify the automatically assigned IP address.

6. Verification

Verify the following:

- All PCs receive IP addresses automatically.
- All laptops receive IP addresses automatically.
- Each device receives the correct subnet mask.
- All clients receive addresses from the configured DHCP pool.

7. Screenshots

Network Topology

"DHCP Network Topology" (screenshots/topology.png)

DHCP Server Configuration

"DHCP Configuration" (screenshots/dhcp-config.png)

Client IP Configuration

"Client IP Configuration" (screenshots/dhcp-client.png)

8. Expected Results

- DHCP service successfully configured.
- Automatic IP address allocation to all clients.
- Successful communication between devices in the same LAN.

9. Skills Learned

- DHCP Server Configuration
- Dynamic IP Address Allocation
- Cisco Switch Connectivity
- IP Address Management
- Network Troubleshooting
- Cisco Packet Tracer

10. Tools Used

- Cisco Packet Tracer

Author

Pranav Adhau

Aspiring Network Engineer
