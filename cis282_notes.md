# CIS 282 Advanced Network Administration I Notes

## **1. Introduction to Advanced Network Administration**
- **Overview**: Focuses on advanced concepts in managing and optimizing enterprise-level networks.
- **Key Responsibilities**:
  - Advanced troubleshooting
  - Scalability planning
  - Network security hardening
  - Virtualization and cloud integration
  - High-availability configurations

---

## **2. VLANs (Virtual Local Area Networks)**
- **Definition**: Logical segmentation of networks to improve efficiency and security.
- **Benefits**:
  - Reduces broadcast domains
  - Enhances security
  - Simplifies network management
- **Trunking**:
  - Allows VLANs to span multiple switches
  - Common protocol: **802.1Q**
- **Commands** (Cisco example):
  ```bash
  vlan 10
  name HR
  exit
  interface fa0/1
  switchport mode access
  switchport access vlan 10
