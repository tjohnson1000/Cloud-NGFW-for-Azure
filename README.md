# Palo Alto Cloud NGFW for Azure Security Lab
<img src="https://i.imgur.com/LIK6y5b.png" height="80%" alt="Topology" />
## Overview
This lab explores **Palo Alto Networks Cloud NGFW for Azure**, using the **Ultimate Test Drive (UTD) Pilot Program**. It provides hands-on experience with **firewall deployment, security policy management, threat prevention, and Azure Virtual WAN (VWAN) security**.

## Lab Setup
The lab consists of:
- **Cloud NGFW for Azure**
- **Azure Virtual WAN (VWAN) & VNet Peering**
- **Web & DB Servers in Spoke VNets**
- **Azure Log Analytics for monitoring**

## Objectives
- **Deploy and configure Cloud NGFW on Azure**
- **Secure inbound, outbound, and VNet traffic**
- **Implement security policies using Local Rule Stack**
- **Configure NAT and firewall policies**
- **Simulate and block brute force attacks on DB server**
- **Monitor security logs with Azure Log Analytics**

## Configuration Steps

### **1. Deploy Cloud NGFW on Azure**
- Use **Azure Resource Manager (ARM) templates**
- Configure **Virtual WAN and VNet peering**

### **2. Configure Security Policies**
- Apply **Zero Trust rules** to restrict traffic
- Implement **destination NAT** for secure access
- Allow **MySQL traffic from Web to DB**
- Block **social networking sites**

### **3. Simulate and Block Cyber Attacks**
- Launch a **brute force attack** on the DB server
- Monitor logs to verify Palo Alto **threat detection**

### **4. Validate Security Enforcement**
- Verify traffic logs in **Azure Log Analytics**
- Check **session flows and rule enforcement**

## **Verification & Testing**
```shell
show security policies
show session all
show threat log
```

## **Repository Structure**
```
├── configs/
│   ├── CloudNGFW_Azure_Config.txt  # Configuration for Cloud NGFW on Azure
├── README.md                       # Documentation
├── screenshots/                    # Screenshots of verification outputs
└── topology.png                     # Network diagram
```

## **Conclusion**
This lab provides **real-world experience in deploying and securing workloads in Azure** using **Palo Alto Cloud NGFW**. It covers **Zero Trust policies, threat detection, and traffic enforcement**, making it an essential resource for **cloud security professionals**.

---
**Author:** Travis Johnson  
**Company:** 10Digit Solutions LLC  
**GitHub Repository:** [Add link when available]
