# Cisco Packet Tracer Home Lab
This project uses Cisco Packet Tracer project to demonstrate VLANs, ACLs, and basic network security setups in network environments.

**Objective:** Simulate a real network environment and implement basic protocols to secure the network.

**Environment:**
Cisco Packet Tracer

**Steps Taken:**
1. Built physical topology: connected PCs to switch, switch to router using Copper Straight-Through cables

2. Enabled router interfaces and configured trunk port on switch

3. Created VLANs: Admin (10), HR (20), Guest (30)

4. Assigned switch ports to respective VLANs

5. Configured router-on-a-stick sub-interfaces for each VLAN

6. Configured IP addresses for PCs and verified connectivity

7. Implemented ACLs to block Guest access to Admin/HR while allowing Admin full access

8. Troubleshot ACLs for two-way communication (ICMP echo/reply)

9. Verified network segmentation and security using ping tests 
