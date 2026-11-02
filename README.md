# Computer Networks Coursework & Labs (Semester 4)

Comprehensive collection of network protocol analysis, simulation models, packet captures, and diagnostic implementations from the Computer Networks curriculum (UE24CS252B) at PES University.

---

## 📌 Course Progression Overview

```
Computer Networks Coursework
├── Level 1: Core Labs (Wireshark Captures, Cisco Packet Tracer & Protocol Studies)
├── Level 2: Orange Project (SDN Mininet & OpenFlow Packet Logger)
└── Level 3: Jackfruit Final Project (ICMP Diagnostic Suite & IoT Socket Controller)
```

---

## 📂 Repository Contents

### 🔹 [Level 1: Core Labs](./Level-1-Labs/)

* **[Lab-01: Basic Networking Commands](./Level-1-Labs/Lab-01-Basic-Networking-Commands/)**:
  * Diagnostic and network configuration command exploration: `ping`, `traceroute`, `netstat`, `arp`, `nslookup`, `ipconfig`/`ifconfig`.
  * Verified submission document: `lab0_I_PES1UG24CS493.pdf`.
  * Includes 19 terminal output execution screenshots.

* **[Lab-02: Cisco Packet Tracer Network Topologies](./Level-1-Labs/Lab-02-Cisco-Packet-Tracer-Topologies/)**:
  * Topology simulation and packet transmission analysis in Cisco Packet Tracer.
  * Models created: Star, Mesh, Bus, and Hybrid topologies across multi-subnet routers and switches.
  * Topology files: `week1.pkt`, `week1-1b.pkt`.
  * Submission report: `lab1_I_PES1UG24CS493.pdf` with sub-experiment verification captures (`1a`, `1b`, `2a`, `2b`).

* **[Lab-04: HTTP Persistent vs Non-Persistent Connections](./Level-1-Labs/Lab-04-HTTP-Persistent-Connections/)**:
  * Quantitative latency comparison of HTTP/1.0 (non-persistent, multiple 3-way handshakes) vs HTTP/1.1 (persistent connection pipelining).
  * Analysis notebook: `CN_LAB4.ipynb`.
  * Mock web server test assets: `web_assets/` (`a.html` and image batch `1.jpg` through `10.jpg`).
  * Submission report: `PES1UG24CS493_I_LAB2.pdf` and packet capture verification screenshots.

* **[Lab-05: UDP & DNS Protocol Exploration](./Level-1-Labs/Lab-05-UDP-and-DNS-Analysis/)**:
  * Deep packet inspection of User Datagram Protocol (UDP) and Domain Name System (DNS) via Wireshark.
  * Dissection of DNS query/response structures, recursion, transaction IDs, and root hints.
  * Submission report: `PES1UG24CS493_I_LAB3.pdf` and 13 packet inspection screenshots.

* **[Lab-06: TCP Congestion Control & Flow Dynamics](./Level-1-Labs/Lab-06-TCP-Congestion-Control/)**:
  * Empirical study of TCP congestion window (cwnd) mechanisms: Slow Start, Congestion Avoidance, Fast Retransmit, and Fast Recovery.
  * Packet capture traces: `WEEK 4 CN LAB.pcapng` and `TCP Congestion Control.pcapng`.
  * Submission report: `PES1UG24CS493_I_LAB4.pdf` and throughput progression screenshots.

* **[Lab-07: Ethernet Framing & Address Resolution Protocol (ARP)](./Level-1-Labs/Lab-07-Ethernet-and-ARP/)**:
  * Layer 2 data link layer analysis: IEEE 802.3 Ethernet frame structure and preamble.
  * ARP request broadcast (`ff:ff:ff:ff:ff:ff`) and unicast reply mechanism, cache timeout, and address resolution tables.
  * Packet capture traces: `lab 5.pcapng` (41.6 MB) and `lab 5 -2.pcapng`.
  * Submission report: `PES1UG24CS493_I_LAB5.pdf` and packet dissection screenshots.

---

## 🔗 Related Coursework Repositories

### 🍊 Level 2: Orange Project (SDN Packet Logger)
* 🔗 **Dedicated Branch**: [**`Tanmayi-n14/CN-Jackfruit-Orange-Problems` (Branch: `SDN-orange-problem-Tanmayi-CS493`)**](https://github.com/Tanmayi-n14/CN-Jackfruit-Orange-Problems/tree/SDN-orange-problem-Tanmayi-CS493)
* Custom OpenFlow 1.0 controller application (`logger.py`) built on the POX framework for real-time MAC/IP header monitoring and reactive flow establishment across Mininet virtual switches.

### 🍈 Level 3: Jackfruit Final Projects
* 🔗 **Dedicated Repository**: [**`Tanmayi-n14/CN-Jackfruit-Orange-Problems`**](https://github.com/Tanmayi-n14/CN-Jackfruit-Orange-Problems)
  1. **ICMP-Based Network Diagnostic Suite**: Combined Ping & Traceroute tool utilizing raw sockets (`socket.IPPROTO_ICMP`), TTL manipulation, and custom ping engine (`ping_engine.py`).
  2. **Smart IoT Thermostat Controller**: Full-duplex raw TCP/IP socket infrastructure (`controller.py`, `device_mock.py`, `index.html`) implementing moving-average noise filtering, short-cycle compressor protection, and watchdog fault detection.

---

## 👤 Author
* **Tanmayi Nagabhairava** ([@Tanmayi-n14](https://github.com/Tanmayi-n14))
* PES University — Department of Computer Science and Engineering
