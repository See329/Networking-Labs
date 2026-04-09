# Networking-Labs
Hands-on networking labs and simulations using Cisco Packet Tracer. Focused on IPv4 subnetting, routing, and network service configuration for CompTIA Network+ preparation.
# IT Networking Portfolio: Packet Tracer Labs

## Lab 1: 3-Node LAN with Mail Service Configuration
**Goal:** Establish a functional Local Area Network (LAN) for three workstations to communicate and exchange data via a central router.

### 💡 The Setup
* **Devices:** 3 Generic PCs, 1 Cisco Router, 1 Network Switch.
* **Topology:** Star Topology using Copper Straight-Through cabling.
* **Network ID:** `192.168.0.0/24`

### 🛠 Configuration Details
* **PC 1:** `192.168.0.1`
* **PC 2:** `192.168.0.2`
* **PC 3:** `192.168.0.3`
* **Default Gateway:** `192.168.0.254` (Router Interface)

### ✅ Key Achievements
1. **Physical Connectivity:** Verified all link lights were green using appropriate cabling.
2. **IP Addressing:** Manually assigned static IPv4 addresses and verified subnet mask patterns.
3. **Service Testing:** Successfully configured and verified end-to-end mail delivery between all three hosts.
4. **Connectivity Check:** Confirmed successful 4/4 ICMP (Ping) replies across the entire network.

### 🚀 What I Learned
By adding the third computer, I practiced scaling the network and ensuring that the Default Gateway was correctly configured on all nodes to allow for traffic flow. This lab reinforced my understanding of **Layer 2 (Switching)** and **Layer 3 (Routing)** logic.
