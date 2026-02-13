# Week 3: S.A. Operating Systems and Maintenance

Week 3 focuses on essential server management tasks in Windows Server 2008 R2, emphasizing system maintenance, User Account Control (UAC), system settings, remote access, and network connectivity. 

System maintenance is critical for organizational efficiency and security, involving updates, hardware management, and user account configurations. UAC enhances security by requiring administrator permission for potentially harmful actions, with adjustable security levels. 

System settings centralize management of health, updates, and protection, including hardware and user account configurations. 

Remote settings enable administrative access and collaborative troubleshooting, with Remote Desktop supporting multiple connections and Network Level Authentication enhancing security. 

Network connectivity relies on proper IP address configuration and date/time synchronization for reliable service delivery. 

Best practices include regular updates, secure remote access configurations, and synchronized system settings to ensure optimal server performance and security.

---

## Major Topics Outline  

- **System Maintenance Importance**  
- **User Account Control (UAC)**  
  - Features  
  - Standard User Capabilities  
  - UAC Security Impact  
- **System Settings**  
  - Control Panel Interface  
  - Key System Configurations  
  - Computer Name and Domain Settings  
  - Workgroups vs Domains  
- **Remote Settings**  
  - Remote Assistance  
  - Remote Desktop  
  - Network Level Authentication  
- **Network Connectivity**  
  - IP Address Configuration  
  - Date and Time Synchronization  

---

## Glossary  

- **User Account Control (UAC)** — A security feature in Windows that prevents unauthorized changes by requiring administrator permission for certain actions.  
- **Workgroup** — A peer-to-peer network where user accounts are decentralized and stored on each individual computer.  
- **Domain** — A centralized logical unit for scalable security and management through Active Directory, defining a security boundary controlled by domain controllers.  
- **Network Level Authentication (NLA)** — A security method that completes user authentication before establishing a full remote desktop connection, enhancing security against unauthorized access.  

---

## Section Summaries  

### **System Maintenance Importance**  

- Essential for organizational efficiency and security.  
- Involves regular updates, hardware management, and user account configurations.  
- Critical for maintaining system health and reliability.  

### **User Account Control (UAC)**  

- Enhances security by requiring permission for potentially harmful actions.  
- Standard users can perform basic tasks without administrative rights.  
- Adjustable security levels via a slider in the Control Panel.  

### **System Settings**  

- Centralized management of system health, updates, and protection.  
- Includes hardware and user account management.  
- Key configurations involve computer naming, domain membership, and remote access settings.  

### **Remote Settings**  

- Remote Assistance allows collaborative troubleshooting.  
- Remote Desktop provides full administrative access.  
- Network Level Authentication enhances remote connection security.  

### **Network Connectivity**  

- IP address configuration is essential for network communication.  
- Date and time synchronization is critical for logging and security.  
- Proper configuration ensures reliable service delivery.  

---

## Technical Specifications  

- **Remote Desktop Connections**: Supports two remote desktop connections plus one console mode by default.  
- **Network Level Authentication**: Completes user authentication before establishing a full connection.  

---

## Comparisons  

### **Workgroups vs Domains**  

- **Workgroup**  
  - Decentralized  
  - Peer-to-peer  
  - User accounts stored locally  
- **Domain**  
  - Centralized  
  - Scalable security  
  - Managed by Active Directory  

### **Remote Assistance vs Remote Desktop**

- **Remote Assistance**  
  - Collaborative troubleshooting  
  - Shared control  
  - Encrypted connection  
- **Remote Desktop**  
  - Full administrative access  
  - Supports multiple connections  
  - Network Level Authentication  

---

## Procedures  

### **Enable or Disable UAC**  

1. Access User Accounts in the Control Panel.  
2. Select the target account.  
3. Click Change User Account Control settings.  
4. Adjust the slider to the appropriate security option.  
5. Restart the system for changes to take effect.  

### **Setting Up Remote Assistance**  

1. Install Remote Assistance as a Windows feature.  
2. Enable the option in the Remote tab of System properties.  
3. Send an invitation via email or instant message.  
4. Establish a two-way encrypted connection after acceptance.  

### **Verifying NLA Support**  

1. Start a Remote Desktop Connection.  
2. Click the icon in the upper-left corner of the dialog box.  
3. Select the About option from the menu.  
4. Verify the text: 'Network Level Authentication supported.'  

---

## Best Practices and Recommendations  

- Regularly update Windows and install necessary roles and features.  
- Configure Network Level Authentication for enhanced remote desktop security.  
- Synchronize date and time settings for reliable logging and authentication.  
- Use Remote Assistance for collaborative troubleshooting to minimize downtime.
