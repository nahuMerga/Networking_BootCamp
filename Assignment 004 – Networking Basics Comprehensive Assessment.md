**Networking Assignment**

---

### 1. Define a computer network. What are its main purposes?

A computer network is a group of interconnected computers that share resources and data.  
**Purpose:** Sharing files, internet access, hardware (like printers), communication.

---

### 2. What is the difference between LAN, WAN, MAN, and PAN? Provide one example of each.

|Type|Full Form|Area Covered|Example|
|---|---|---|---|
|LAN|Local Area Network|Small area like office|Home Wi-Fi network|
|WAN|Wide Area Network|Large geographical area|Internet|
|MAN|Metropolitan Area Network|City or campus|City-wide cable network|
|PAN|Personal Area Network|Around a person|Bluetooth headset connection|

---

### 3. Explain client-server and peer-to-peer network models with examples.

- **Client-Server:** One central server serves multiple clients (e.g., Gmail server handling emails).
    
- **Peer-to-Peer:** Each device acts as both client and server (e.g., file sharing via BitTorrent).
    

---

### 4. Benefits of using a network in an organization:

- Centralized data access
    
- Shared resources
    
- Easy communication
    
- Scalability
    
- Backup and security management
    

---

### 5–7. Network Topologies

**Common Topologies:** Star, Bus, Ring, Mesh

| Topology | Diagram | Advantage                                         | Disadvantage                                  |
| -------- | ------- | ------------------------------------------------- | --------------------------------------------- |
| Star     |         | Easy to manage, one failure doesn’t affect others | If central switch fails, all connections fail |
| Bus      |         | Easy to implement                                 | Entire network fails if backbone cable fails  |

**Most common in LANs:** Star topology (reliable and easy to manage).


### 8. Define the function of the following devices:

- **Switch:** Forwards data to specific devices on a LAN.
    
- **Router:** Connects different networks; routes traffic between them.
    
- **Hub:** Broadcasts data to all devices.
    
- **Access Point:** Allows wireless devices to connect to a network.
    

---

### 9. Difference between modem and router:

- **Modem:** Connects to ISP and translates signal.
    
- **Router:** Distributes internet to multiple devices.
    

---

### 10. OSI Layers for Switch and Router:

- **Switch:** Layer 2 (Data Link)
    
- **Router:** Layer 3 (Network)
    

---

### 11. Types of Transmission Media:

- **Wired:** Twisted pair (UTP/STP), coaxial, fiber optic
    
- **Wireless:** Radio waves, microwaves, infrared
    

---

### 12. Compare STP and UTP cables:

|Feature|STP|UTP|
|---|---|---|
|Shielding|Yes|No|
|Cost|Expensive|Cheaper|
|Interference|Less|More|

---

### 13. BNC and RJ45 Connectors:

- **BNC:** Used for coaxial cables in older networks.
    
- **RJ45:** Used for Ethernet cables in modern LANs.
    

---

### 14. Single-mode vs Multi-mode Fiber:

- **Single-mode:** Long distances, laser light
    
- **Multi-mode:** Shorter distances, LED light
    

---

### 15. Typical uses of Coaxial Cable:

- Cable TV
    
- Internet connection via cable modem
    

---

### 22. 7 Layers of OSI Model:

1. **Physical** - cables, signals
    
2. **Data Link** - MAC addressing
    
3. **Network** - IP addressing
    
4. **Transport** - error checking, TCP/UDP
    
5. **Session** - manages sessions
    
6. **Presentation** - data formatting
    
7. **Application** - user-facing apps (HTTP, FTP)
    

---

### 23. Protocols matched to OSI layers:

- **HTTP** - Application
    
- **DNS** - Application
    
- **TCP** - Transport
    
- **IP** - Network
    
- **Ethernet** - Data Link
    
- **ARP** - Data Link
    

---

### 24. Function of Transport Layer:

- Reliable delivery, segmentation, error handling.
    
- Protocols: TCP, UDP
    

---

### 25. Compare OSI and TCP/IP Models:

- **Similarity:** Both have layers and define networking roles.
    
- **Difference:** OSI has 7 layers; TCP/IP has 4 layers.
    

---

### 26. TCP/IP Model Layers:

1. Application
    
2. Transport
    
3. Internet
    
4. Network Access
    

---

### 27. IP Addressing Layer:

- **OSI:** Network layer
    
- **TCP/IP:** Internet layer



**IP Addressing and Subnetting**

28. An IP address is a unique numerical identifier assigned to each device on a network to locate and communicate with it.
    

- **IPv4:** 32-bit address, written as four decimal numbers separated by dots (e.g., 192.168.1.1).
    
- **IPv6:** 128-bit address, written as eight groups of hexadecimal numbers separated by colons (e.g., 2001:0db8::1). IPv6 allows more addresses and better security.
    

29. 192.168.1.1 in binary:  
    11000000.10101000.00000001.00000001
    
30. 11000000.10101000.00000001.00000100 in decimal:  
    192.168.1.4
    
31. IP Classes:
    

- **Class A:** 1.0.0.0 to 126.255.255.255 (supports large networks)
    
- **Class B:** 128.0.0.0 to 191.255.255.255 (medium networks)
    
- **Class C:** 192.0.0.0 to 223.255.255.255 (small networks)
    

32. **Static IP:** Manually assigned, fixed IP that doesn’t change.  
    **Dynamic IP:** Assigned automatically by DHCP, can change over time.
    
33. Private IP addresses are reserved for use within private networks and are not routable on the internet.  
    Private IP ranges:
    

- 10.0.0.0 – 10.255.255.255
    
- 172.16.0.0 – 172.31.255.255
    
- 192.168.0.0 – 192.168.255.255
    

34. Loopback address is 127.0.0.1; it’s used for a device to communicate with itself for testing.
    
35. A /24 subnet supports 2^(32-24) - 2 = 254 hosts.
    
36. /26 subnet mask is 255.255.255.192. It supports 2^(32-26) - 2 = 62 hosts.
    
37. For 192.168.20.0/27:
    

- Network address: 192.168.20.0
    
- Broadcast address: 192.168.20.31
    

38. Borrowing 3 bits from /24: Number of subnets = 2^3 = 8 subnets.
    

---

**Protocols and Ports**

41. HTTP is the protocol for transferring web pages over the internet. It operates on port 80.
    
42. DNS (Domain Name System) translates domain names into IP addresses, solving the problem of remembering numeric IPs.
    
43. DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses and network settings to devices.
    
44. Five common networking protocols and functions:
    

- HTTP: Web browsing
    
- FTP: File transfer
    
- SMTP: Email sending
    
- DNS: Domain name resolution
    
- TCP: Reliable data transmission
    

---

**Switching and Routing**

45. Switching forwards data within the same network (LAN), routing directs data between different networks.
    
46. VLAN (Virtual LAN) logically segments a network into separate broadcast domains to improve management and security.
    

---

**Crimping and Cables**

16. T568A color code: White/Green, Green, White/Orange, Blue, White/Blue, Orange, White/Brown, Brown  
    T568B color code: White/Orange, Orange, White/Green, Blue, White/Blue, Green, White/Brown, Brown
    
17. Straight-through cables connect different devices (e.g., PC to switch); crossover cables connect similar devices (e.g., switch to switch).
    
18. Three tools: Crimping tool, cable tester, wire stripper.
    

---

**Communication Models**

- Simplex: One-way communication only.
    
- Half-Duplex: Two-way communication, but one direction at a time.
    
- Full-Duplex: Two-way communication simultaneously.
    

---

**MAC Address and ARP**

39. MAC address is a hardware address unique to each network interface; IP address is a logical address assigned to devices.
    
40. ARP (Address Resolution Protocol) maps IP addresses to MAC addresses on a local network.
    

---

**Basic Communication System**

20. Key components: Sender, Receiver, Medium, Message, Protocol.
    
21. Protocols ensure devices follow the same rules for communication to avoid errors.
    

---

**Networking Essentials**

47. Default gateway is the router that connects a local network to other networks, used to send data outside the local subnet.
    

---

**Security Basics**

48. Three common network threats: Malware, Phishing, Denial of Service (DoS) attacks.
    
49. Firewall monitors and controls incoming/outgoing network traffic to protect against unauthorized access.
    
50. Antivirus software detects and removes malicious software to protect devices and networks.
    

---

**BONUS**

51. NAT (Network Address Translation) translates private IP addresses to a public IP for internet access, commonly used in routers for home and office networks.
