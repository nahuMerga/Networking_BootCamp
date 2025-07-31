## ** IP Addressing Basics**

**1. What is an IP address and why is it important in a network?**  
An IP address is a unique identifier for a device on a network. It allows devices to send and receive data.


**2. IPv4 vs IPv6**

|Feature|IPv4|IPv6|
|---|---|---|
|Address Length|32 bits|128 bits|
|Format|Decimal (e.g., 192.168.0.1)|Hexadecimal (e.g., 2001:0db8::1)|
|Available Addresses|~4.3 billion|~340 undecillion|

---

**3. Binary of 192.168.10.1:**  
192 = 11000000  
168 = 10101000  
10 = 00001010  
1 = 00000001  
**Answer:** `11000000.10101000.00001010.00000001`

---

**4. Convert binary to decimal:**  
11000000.10101000.00000001.00000010 =  
= 192.168.1.2

---

**5. IPv4 Class Ranges:**

|Class|Range||
|---|--- |---|
|A  |1.0.0.0 – 126.255.255.255||
|B|128.0.0.0 – 191.255.255.255||
|C|192.0.0.0 – 223.255.255.255||

---

**6. 172.16.5.4 belongs to:**  
 **Class B**

---

**7. Public vs Private IP**

- **Public IP**: Routable on the internet (e.g., 8.8.8.8)
    
- **Private IP**: For internal networks (non-routable)
    

**Private IP Ranges:**

- Class A: 10.0.0.0 – 10.255.255.255
    
- Class B: 172.16.0.0 – 172.31.255.255
    
- Class C: 192.168.0.0 – 192.168.255.255
    

---

**8. Loopback Address:**  
127.0.0.1 – Used to test the network stack of your local machine.

---

**9. Static IP vs Dynamic IP**

- **Static IP**: Manually set, doesn’t change (e.g., web servers)
    
- **Dynamic IP**: Assigned by DHCP, may change (e.g., home Wi-Fi devices)
    

---

**10. Default Subnet Masks:**

- Class A → 255.0.0.0
    
- Class B → 255.255.0.0
    
- Class C → 255.255.255.0
    

---

##  **Part B – Subnetting Concepts & Calculations**

**11. What is subnetting?**  
Dividing a large network into smaller networks (subnets) to improve management and security.

---

**12. IP: 192.168.1.0/24 → Total IPs:**  
2^(32-24) = 2^8 = **256 IP addresses**

---

**13. Usable host IPs:**  
256 total – 2 (network & broadcast) = **254 usable hosts**

---

**14. Borrow 2 bits from /24 → How many subnets?**  
2^2 = **4 subnets**

---

**15. Borrow 3 bits from /24 → New Subnet Mask:**  
24 + 3 = /27  
 **255.255.255.224**

---

**16. IP: 192.168.10.0/26**

- Host bits: 6 → 2^6 = 64 IPs  
     **Hosts/subnet:** 64 – 2 = **62**  
     **Subnets:** 2^(26–24) = **4**
    

---

**17. Subnet: 192.168.10.64/26**

- **Network Address**: 192.168.10.64
    
- **Broadcast Address**: 192.168.10.127
    
- **First usable IP**: 192.168.10.65
    
- **Last usable IP**: 192.168.10.126
    

---

**18. IP: 10.0.0.0/22**

- **Block size**: 2^(32–22) = 1024 IPs
    
- **Network Address**: 10.0.0.0
    
- **Broadcast Address**: 10.0.3.255
    

---

**19. Fill in the blanks:**

- CIDR /30 gives **2 usable IPs**
    
- CIDR /28 supports **14 hosts** per subnet
    

---

**20. Block: 172.16.0.0/20**

- Need at most **510 hosts** per subnet  
    → 2^9 = 512 addresses (9 host bits needed)  
    → Subnet mask = 32 – 9 = **/23**  
     **Subnets:** 2^(23–20) = **8 subnets**
