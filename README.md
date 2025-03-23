# Pixel Infotech Ltd. - Network Design Project

## 📌 Project Overview
You have been hired as a **Network Engineer** for **Pixel Infotech Ltd.**, a mid-sized enterprise with a **nine-floor office building**. The objective is to design a **scalable and efficient network** to facilitate seamless communication across all floors while ensuring **fault tolerance and high performance**.

---
## 📡 Network Design Requirements

### 1️⃣ Topology Selection
- **Ring Topology**: Implemented on **2 floors** to ensure **redundancy and fault tolerance**.
- **Star Topology**: Implemented on the **remaining 7 floors**, providing **high-speed data transfer** and ease of maintenance.

### 2️⃣ IP Addressing Scheme
- **Class B Private IPv4 Addressing**
- Unique **subnet allocation** for each floor to avoid conflicts.

### 3️⃣ Routing Strategy for Inter-Floor Communication & Connectivity
- **Static Routing**: Defined routes to ensure efficient data flow.
- **Network Devices Used**:
  - **Switches**: Connecting computers within each floor.
  - **Routers**: Interconnecting floors and managing network traffic.
  - **Access Points (APs)**: Providing **wireless connectivity** where required.
- **Default Gateways**:
  - Each floor is assigned a **specific gateway** to manage inter-floor routing efficiently.

---
## 🔧 Implementation Details
### 📍 Steps to Set Up the Network
1. **Configure IP Addressing**: Assign **Class B subnetted addresses** to all floors.
2. **Set Up Topology**:
   - Establish **ring topology** for 2 floors.
   - Deploy **star topology** for the remaining floors.
3. **Configure Static Routing**:
   - Define **static routes** between routers for optimized traffic flow.
   - Set up default gateways.
4. **Test Connectivity**:
   - Use **ping and traceroute commands** to verify inter-floor communication.

### 📊 Justification for Routing Approach
- **Static Routing** is chosen for inter-floor communication because:
  - It **reduces overhead** and **simplifies configuration**.
  - Suitable for **small to mid-sized networks** with **predictable traffic patterns**.
- If **dynamic routing** were to be used, **OSPF** would be recommended due to its **scalability and efficiency** in multi-floor setups.

---
## 🎯 Key Features
✅ **Hybrid Network Design**: Combination of **ring and star topologies** for performance & redundancy.
✅ **Efficient IP Addressing**: Ensures **uniqueness and manageability**.
✅ **Seamless Inter-Floor Communication**: Optimized **static routing**.
✅ **Scalable Infrastructure**: Easily expandable for **future network upgrades**.

---
## 🛠 Technologies & Tools Used
- **Cisco Packet Tracer** (for simulation & design)
- **IPv4 Addressing** (Class B Private Network)
- **Routers & Switches** (for structured network management)
- **Static Routing** (for optimized traffic flow)

---
## 🖥️ How to Open the Project
1. **Download** the project file (`.pkt`).
2. Open **Cisco Packet Tracer**.
3. Load the `.pkt` file to visualize and test the network setup.
4. Use `ping` and `show ip route` commands to verify network connectivity.

---
## 📸 Screenshots (Add Network Diagram Here)
![Network Diagram](https://i.imgur.com/3O8wYhJ.png)
---
## 🚀 Future Enhancements
🔹 **Implement VLANs** for better segmentation.  
🔹 **Introduce OSPF or EIGRP** for dynamic routing.  
🔹 **Upgrade to a Hybrid Cloud Model** for remote accessibility.  

---
## 👨‍💻 Author
**Reddy Manjunath**  
📧 Manjukannayya@gmail.com  
🔗 [GitHub Profile](https://github.com/reddy-manjunath)


