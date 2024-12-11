# CIS 281 Network Administration I Notes

## **1. Introduction to Network Administration**
- **Definition**: The process of managing and maintaining computer networks.
- **Key Responsibilities**:
  - Network setup and configuration
  - Monitoring and troubleshooting
  - Implementing security measures
  - Backup and recovery planning
  - Performance optimization

---

## **2. Types of Networks**
- **LAN (Local Area Network)**:
  - Covers a small geographical area (e.g., office, home)
  - High-speed connections
- **WAN (Wide Area Network)**:
  - Spans large geographical areas (e.g., Internet)
  - Lower speeds compared to LAN
- **MAN (Metropolitan Area Network)**:
  - Covers a city or large campus
- **PAN (Personal Area Network)**:
  - Small network for personal devices (e.g., Bluetooth)

---

## **3. Network Topologies**
- **Star Topology**:
  - Devices connect to a central hub or switch
  - Easy to troubleshoot
- **Bus Topology**:
  - All devices share a single communication line
  - Low cost but prone to failures
- **Ring Topology**:
  - Devices connect in a circular fashion
  - Data travels in one direction
- **Mesh Topology**:
  - Every device connects to every other device
  - Highly fault-tolerant but expensive

---

## **4. Network Devices**
- **Router**:
  - Connects different networks
  - Directs traffic using IP addresses
- **Switch**:
  - Connects devices within the same network
  - Uses MAC addresses to forward data
- **Hub**:
  - Broadcasts data to all devices in a network
  - Less efficient than switches
- **Firewall**:
  - Protects the network by filtering traffic
- **Access Point**:
  - Provides wireless connectivity

---

## **5. OSI Model**
- **Layers**:
  1. Physical
  2. Data Link
  3. Network
  4. Transport
  5. Session
  6. Presentation
  7. Application
- **Mnemonic**: "Please Do Not Throw Sausage Pizza Away"

---

## **6. TCP/IP Protocol Suite**
- **Layers**:
  - Application
  - Transport
  - Internet
  - Network Access
- **Key Protocols**:
  - **HTTP/HTTPS**: Web browsing
  - **SMTP/IMAP**: Email
  - **FTP/SFTP**: File transfer
  - **DNS**: Resolves domain names to IP addresses

---

## **7. IP Addressing**
- **IPv4**:
  - Format: `x.x.x.x` (e.g., `192.168.1.1`)
  - Classes: A, B, C, D, E
- **IPv6**:
  - Format: `x:x:x:x:x:x:x:x` (e.g., `2001:0db8:85a3:0000:0000:8a2e:0370:7334`)
  - Larger address space
- **Private vs Public IPs**:
  - Private: Reserved for internal use (e.g., `192.168.0.0/16`)
  - Public: Accessible over the Internet

---

## **8. Subnetting**
- **Purpose**: Divides a network into smaller segments.
- **Subnet Mask**:
  - Used to determine the network and host portions of an IP address.
  - Example: `255.255.255.0` (CIDR notation: `/24`)
- **Key Calculations**:
  - Number of subnets
  - Hosts per subnet

---

## **9. Network Security Basics**
- **Threats**:
  - Malware
  - Phishing
  - Denial-of-Service (DoS) attacks
- **Security Measures**:
  - Firewalls
  - Antivirus software
  - Intrusion Detection Systems (IDS)
  - Regular updates and patches
- **Encryption**:
  - Protects data in transit
  - Common protocols: SSL/TLS, IPsec

---

## **10. Network Troubleshooting Tools**
- **Ping**:
  - Tests connectivity to a host
  - Command: `ping <IP>`
- **Traceroute**:
  - Tracks the path data takes to a destination
  - Command: `traceroute <IP>` (Linux) / `tracert <IP>` (Windows)
- **Netstat**:
  - Displays network connections and statistics
- **Nslookup**:
  - Resolves DNS names to IP addresses
- **Wireshark**:
  - Captures and analyzes network traffic

---

## **11. Study Tips**
- **Practice Commands**:
  - Familiarize yourself with network administration tools in a lab environment.
- **Learn by Doing**:
  - Set up a small network using virtual machines or physical devices.
- **Review Key Concepts**:
  - Focus on subnetting, OSI model, and troubleshooting techniques.
- **Group Discussions**:
  - Exchange knowledge and solve problems collaboratively.

---

**End of Notes**
