

**1. STP vs UTP Cables:**

- **STP (Shielded Twisted Pair):** Has shielding to reduce interference.
    
- **UTP (Unshielded Twisted Pair):** No shielding, cheaper, and more flexible.
    

**2. STP Advantages & Disadvantages:**  

 **Advantages:** Less interference, more secure  
 **Disadvantages:** More expensive, harder to install

**3. Coaxial Cable:**  
A cable with a single copper wire core, shielded by insulation.  
**Used for:**

- Cable TV
    
- Internet connections
    

**4. BNC Connector:**  
Used to connect coaxial cables; often in **CCTV** and **radio equipment**.

**5. RJ45 vs RJ11:**

|Connector|Pins|Used For|
|---|---|---|
|RJ45|8 pins|Networking (Ethernet)|
|RJ11|4–6 pins|Telephony (phones)|

**6. UTP Cat 5e and Cat 6 Specs:**

- **Cat 5e:** 1 Gbps up to 100 meters
    
- **Cat 6:** 10 Gbps up to 55 meters (1 Gbps for 100m)
    

**7. Two Types of Fiber Optic Cables:**

- **Single-mode:** Long distance, uses laser light
    
- **Multi-mode:** Short distance, uses LED light
    

**8. Single-mode vs Multi-mode:**

- **Single-mode:** Thin core, long-range
    
- **Multi-mode:** Thick core, cheaper, short-range
    

**9. Two Advantages of Fiber Optic:**

- Faster speeds (high bandwidth)
    
- Immune to electrical interference
    

**10. T568A & T568B Color Codes:**  

**T568A** and **T568B**
![[Pasted image 20250731074937.png]]


**11. Straight-through cable used for:**  
 PC to Switch  
 Switch to Router

**12. Crossover cable used for:**  
Direct PC-to-PC or Switch-to-Switch connection

**13. Two Tools for Ethernet cables:**

- Crimping tool
    
- Cable tester
    

**14. Fill in the blanks:**

- **Straight-through**: PC to **Switch**
    
- **Crossover**: PC to **PC**
    

**15. Compare Cable Types:**

|Cable|Cost|Speed|Interference|
|---|---|---|---|
|**Coaxial**|Medium|Medium|Medium|
|**Twisted Pair**|Low|Good|Medium|
|**Fiber Optic**|High|Very High|Very Low|

---

###  **Section 2: Communication Models**

**16. What is a communication model?**  
It’s a framework showing how data is transmitted between devices.

**17. Three Data Flow Types + Examples:**

- **Simplex**: One-way (TV broadcast)
    
- **Half-Duplex**: One way at a time (Walkie-talkie)
    
- **Full-Duplex**: Both ways at once (Phone call)
    

**18. Simplex, Half-Duplex, Full-Duplex:**

- **Simplex**: Sender only → Receiver (Radio)
    
- **Half-Duplex**: Sender ↔ Receiver (one at a time) (Walkie-talkie)
    
- **Full-Duplex**: Both send & receive at once (Phone)
    

**19. Importance of a Protocol:**  
Protocols ensure devices speak the same “language” so data is sent and understood correctly.

**20. Basic Elements of Communication System:**

- Sender
    
- Receiver
    
- Transmission Medium
    
- Message
    
- Protocol
    

---

###  **Section 3: OSI Model (Detailed)**

**21. 7 OSI Layers (Top to Bottom):**

1. Application
    
2. Presentation
    
3. Session
    
4. Transport
    
5. Network
    
6. Data Link
    
7. Physical
    


**22. Match OSI Layers to Protocols:**

- **Application** – HTTP
    
- **Transport** – TCP
    
- **Network** – IP
    
- **Data Link** – Ethernet
    
- **Physical** – Fiber Optic Cable
    

**23. Transport Layer Function (Layer 4):**  
Breaks data into segments, ensures delivery.  
Protocols: TCP, UDP

**24. IP Addressing Layer:**  
**Network Layer (Layer 3)** – Handles logical addressing and routing of packets.

**25. Data Unit Names by Layer:**

- Layer 4 (Transport) → Segment
    
- Layer 3 (Network) → Packet
    
- Layer 2 (Data Link) → Frame
    
- Layer 1 (Physical) → Bits
    

**26. Router vs Switch vs Hub:**

|Device|Function|OSI Layer|
|---|---|---|
|**Router**|Routes data between networks|Layer 3|
|**Switch**|Connects devices in a LAN|Layer 2|
|**Hub**|Broadcasts to all devices|Layer 1|

**27. What happens at each OSI layer when sending a file:**

1. **App Layer**: User selects file to send
    
2. **Presentation**: Data is formatted/encrypted
    
3. **Session**: Connection is established
    
4. **Transport**: Data split into segments
    
5. **Network**: Adds IP address
    
6. **Data Link**: Adds MAC address
    
7. **Physical**: Sends bits over cable/wireless
    

**28. Why OSI Model is Important:**  
It breaks down complex networking into simple layers to troubleshoot, design, and understand how data moves.

**29. Real-Life Analogy:**  
 **Post Office**:

- You write a letter (App layer)
    
- Envelope it (Presentation/Session)
    
- Add address (Network)
    
- Sort it (Data Link)
    
- Deliver it (Physical)
    

**30. BONUS – OSI vs TCP/IP:**  
 **Similarity**: Both models define how data travels over a network  
**Difference**: OSI has 7 layers; TCP/IP has 4 (Application, Transport, Internet, Network Access)
