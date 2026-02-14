# Week 3 – Operating Systems and Maintenance (Windows Server 2008 R2 Administration)

---

## Overview

This week focuses on essential administration, configuration, and maintenance tasks within a Windows Server 2008 R2 environment. Emphasis is placed on system security, remote management, domain integration, and proper network configuration to ensure stable and secure server operations in organizational settings.

---

## Learning Objectives

By the end of this lesson, students should be able to:

- Perform essential server management and maintenance tasks
- Configure system settings such as remote access, domain membership, and date/time synchronization
- Understand and apply LAN/WAN technologies according to network design requirements
- Maintain secure and properly configured Windows Server environments

---

## Key Terms

Important terminology for Windows Server administration includes:

- User Account Control (UAC)
- Domain
- Active Directory Services
- Device Driver
- Plug and Play
- Workgroup
- Network Level Authentication (NLA)

---

## Performing Initial Configuration Tasks

After installation, Windows Server 2008 R2 automatically opens the Initial Configuration Tasks window. This interface helps administrators complete essential setup steps.

Key configuration actions include:

- Enabling Remote Desktop and configuring Windows Firewall
- Updating Windows and installing roles and features
- Configuring network settings
- Assigning a computer name and joining a domain
- Activating Windows
- Setting the correct date, time, and time zone

Completing these tasks ensures the server is secure, network-ready, and properly integrated into the organization’s infrastructure.

---

## Using the Control Panel

The Control Panel provides centralized access to system configuration tools.

Primary areas include:

System and Security  
- Monitor system health  
- Configure Windows Update  
- Manage firewall and security settings  

Hardware  
- Manage devices and drivers  
- Configure hardware settings  

User Accounts  
- Manage user permissions  
- Configure account settings and profiles  

Effective navigation of the Control Panel is essential for system-wide administration.

---

## Understanding User Account Control (UAC)

User Account Control (UAC) improves security by preventing unauthorized system changes through permission prompts.

Key features:

- Mandatory prompts for configuration changes
- Administrator approval required for sensitive tasks
- Standard users must provide administrator credentials for restricted actions

Standard User Capabilities:

- Install approved updates and drivers from Windows Update
- View system settings without modifying them
- Pair Bluetooth devices
- Reset network adapters and run diagnostics

Adjusting UAC Settings:

1. Open User Accounts in Control Panel
2. Select the desired account
3. Click “Change User Account Control settings”
4. Adjust the security level using the slider
5. Restart the system if required

---

## System Settings and Configuration

Important configuration options include:

- Viewing general system information
- Adding the computer to a domain or workgroup
- Accessing Device Manager for hardware configuration
- Configuring Remote Settings
- Managing Startup and Recovery options

These settings allow administrators to define system identity, hardware configuration, and operational behavior.

---

## Changing Computer Name and Domain Membership

Establishing system identity and network membership is critical.

Workgroups:
- Decentralized, peer-to-peer networks
- User accounts stored locally on each machine

Domains:
- Centralized network management
- Controlled through Active Directory
- Scalable security and centralized authentication

Joining a domain enables centralized policy enforcement and resource management.

---

## Configuring Remote Access

Remote management tools allow administrators and support staff to access systems securely.

### Remote Assistance

- Install as a Windows feature
- Enable in the Remote tab of System Properties
- Send an invitation via email or messaging
- Establish an encrypted two-way connection

Used primarily for user support and troubleshooting.

### Remote Desktop

- Allows two simultaneous remote sessions (plus one console session)
- Used for full administrative control

Network Level Authentication (NLA):
- Verifies user credentials before establishing a full remote session
- Enhances security by reducing exposure to unauthorized access

Remote Desktop can be configured to:

- Allow connections from any version (less secure)
- Require Network Level Authentication (more secure)

---

## Changing Date and Time

Accurate date and time settings are critical for:

- Event logging
- Authentication
- Security protocols
- Domain communication

Incorrect time synchronization can result in authentication failures and denial of secure communications.

---

## Network Connectivity Configuration

Proper TCP/IP configuration is essential for communication.

Key components include:

IP Address and Subnet Mask  
- Uniquely identify the device on the network  

Default Gateway  
- Router that enables communication outside the local network  

DNS Servers  
- Translate domain names into IP addresses  

Correct configuration ensures reliable LAN and WAN connectivity.

---

## Session Review

This session covered:

- Initial Configuration Tasks
- User Account Control (UAC)
- System Settings and Domain Membership
- Remote Assistance and Remote Desktop
- Network Connectivity and TCP/IP Configuration

Mastering these administrative tasks ensures secure, stable, and properly configured Windows Server 2008 R2 environments.
