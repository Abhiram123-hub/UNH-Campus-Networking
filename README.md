# Lab 5: Network Project

## 1. Project Overview
This project is a Cisco Packet Tracer simulation designed to demonstrate networking concepts including device configuration, routing, and connectivity testing. The topology consists of multiple routers, switches, and end devices configured to simulate a real-world network scenario.

## 2. Network Topology
![Network Topology](topology.png)
*(Insert a screenshot of your Packet Tracer network topology here.)*

## 3. Devices & Configurations
| Device  | Hostname | IP Address    | Subnet Mask     | Additional Notes       |
|---------|---------|--------------|----------------|------------------------|
| Router1 | R1      | 192.168.1.1  | 255.255.255.0  | Configured with RIP    |
| Switch1 | SW1     | N/A          | N/A            | VLAN Configured        |
| PC1     | PC1     | 192.168.1.10 | 255.255.255.0  | Default Gateway: R1    |

## 4. Setup Instructions
To open and test this project:
1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/lab5-network-project.git
   ```  
3. Open **LAB5_PROJECT.pkt** in Cisco Packet Tracer.
4. Verify network connectivity using:
   ```sh
   ping <destination IP>
   ```

## 5. Configuration Files
All router, switch, and PC configurations are saved in the `configs/` directory.

Example **Router1 Configuration (`configs/router1_config.txt`)**:
```sh
enable  
configure terminal  
hostname R1  
interface GigabitEthernet0/0  
ip address 192.168.1.1 255.255.255.0  
no shutdown  
exit  

## 6. Troubleshooting
- **No connectivity?** 
- **Devices not responding?** 
## 7. Contributors
- **Abhiram** 

