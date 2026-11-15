# Multi-Router Enterprise Network with Multiple WAN Links Using Static Routing

A multi-router enterprise network designed and simulated using **Cisco Packet Tracer**. The topology consists of four routers connected through multiple WAN links, providing different paths between network segments.

The project focuses on configuring static routes to establish communication between multiple LAN networks.

---

## Topology

| **Item** | **Details** |
|---|---|
| Tool | Cisco Packet Tracer |
| Routers | 4 |
| Switches | 4 |
| End Devices | 8 PCs |
| LAN Networks | 4 |
| WAN Links | 4 |
| Routing Method | Static Routing |
| Topology File | `lab.pkt` |
| Configuration | `configuration.txt` |
| Screenshot | `topology.png` |

### Network Topology Diagram

![Network Topology](topology.png)

---

## Topology Summary

- **Router Network:** Four routers interconnected through multiple point-to-point WAN links.
- **LAN 1:** Router1 connected to two PCs through Switch0.
- **LAN 2:** Router2 connected to two PCs through Switch1.
- **LAN 3:** Router3 connected to two PCs through Switch2.
- **LAN 4:** Router4 connected to two PCs through Switch3.
- **WAN Connectivity:** Multiple router-to-router links connect the four routers.

---

## IP Addressing Plan

### LAN Networks

| **Network** | **Router IP** | **PC Addresses** |
|---|---|---|
| LAN 1 | 10.0.0.3 | 10.0.0.1, 10.0.0.2 |
| LAN 2 | 20.0.0.3 | 20.0.0.1, 20.0.0.2 |
| LAN 3 | 30.0.0.3 | 30.0.0.1, 30.0.0.2 |
| LAN 4 | 40.0.0.3 | 40.0.0.1, 40.0.0.2 |

### WAN Links

| **Connection** | **Router 1 IP** | **Router 2 IP** |
|---|---|---|
| Router1 – Router2 | 50.0.0.1 | 50.0.0.2 |
| Router2 – Router3 | 60.0.0.1 | 60.0.0.2 |
| Router3 – Router4 | 70.0.0.1 | 70.0.0.2 |
| Router1 – Router4 | 80.0.0.1 | 80.0.0.2 |

*Note: IP addresses are taken from the topology diagram. Refer to the actual device configurations for subnet masks and interface assignments.*

---

## Network Devices

| **Device** | **Role** |
|---|---|
| Router1–Router4 | Inter-network routing |
| Switch0–Switch3 | LAN connectivity |
| PC0–PC7 | End devices |

---

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- Static Routing
- IPv4 Addressing
- WAN Connectivity
- LAN Networking
- Network Troubleshooting

---

## Configuration and Verification

- Configuring IP addresses on router interfaces.
- Implementing static routes between routers.
- Establishing communication between multiple LANs.
- Verifying routing tables using `show ip route`.
- Checking interface status using `show ip interface brief`.
- Testing end-to-end connectivity using `ping`.

---

## Project Structure

```text
Multi-Router-Enterprise-Network-with-Multiple-WAN-Links-Using-Static-Routing/
│
├── README.md
├── topology.png
├── configuration.txt
└── lab.pkt
```

---

## How to Use

1. Download the `lab.pkt` file.
2. Open it using Cisco Packet Tracer.
3. Review the network topology and IP addressing.
4. Check router configurations in `configuration.txt`.
5. Test connectivity between PCs across different LAN networks.

---

## Learning Outcomes

- Understanding multi-router network design.
- Configuring static routes across multiple routers.
- Understanding multiple WAN connections.
- Analysing routing tables and next-hop addresses.
- Testing communication between different LAN networks.
- Developing network troubleshooting skills.

---

**Project Status:** Completed

**Tool:** Cisco Packet Tracer
