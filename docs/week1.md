# Week 2: System Administration Overview

---

## Introduction

This review summarizes the key concepts, terminology, and core principles of System Administration (S.A) Operating Systems. It focuses on server functions, hardware subsystems, server roles, software selection, installation strategies, performance optimization, and long-term maintenance planning. The objective is to build a comprehensive understanding of effective server management.

---

## Key Terms and Fundamentals

Bottleneck — A subsystem failure or over-utilization that limits the overall performance of the entire system.

NIC (Network Interface Card) — Hardware component that enables communication between a server and client devices across a network.

Volatile Memory — Temporary memory (RAM) that loses stored data when power is removed.

---

## Understanding What a Server Does

A server is a high-performance computer designed to:

- Host applications and services
- Store and manage organizational data
- Process requests from client devices
- Provide authentication and enforce security

### Form Factors

- Physical servers (rack-mounted or tower systems)
- Virtual machines
- Containers (lightweight isolated environments)

### Common Server Types

- Web servers — Deliver websites and web-based applications
- Database servers — Manage structured data
- File servers — Centralize file storage and sharing
- Mail servers — Handle email services

---

## Primary Subsystems of a Server

### Processor (CPU)

- Acts as the “brain” of the system
- Performs mathematical and logical calculations
- Major manufacturers include Intel and AMD

### Memory (RAM)

- Provides short-term storage for instructions and active processes
- Volatile in nature
- A primary factor influencing performance

### Storage

Used for long-term data retention:

- HDD (Hard Disk Drive) — Mechanical rotating platters, slower access speeds
- SSD (Solid State Drive) — Electronic, no moving parts, faster access speeds

### Network

- Enables communication between server and clients
- Utilizes NIC hardware for connectivity

---

## Primary Server Roles

Servers can be configured to perform multiple roles, including:

- File Services — Centralized file storage and secure sharing
- Print Services — Managing print jobs across network printers
- Web Services (IIS 7.5) — Hosting internet and intranet websites and applications
- Application Services — Supporting business software environments
- Email Services — Managing communication systems
- Remote Access — Providing secure external connectivity to internal resources

---

## Identifying System Bottlenecks

### Resource Strain

Bottlenecks occur when a subsystem (Processor, Memory, Storage, or Network) becomes over-utilized or fails.

### Systemic Impact

A single weak subsystem can degrade overall performance and system stability. Continuous monitoring and balanced hardware planning are essential.

---

## Software Selection: Windows Server 2008 R2

### Architecture

- Strictly 64-bit operating system
- No 32-bit version available
- In-place upgrades from 32-bit systems are unsupported

### Editions and Target Audience

- Foundation
  - Designed for small businesses (fewer than 15 users)
  - Cost-effective with limited scalability

- Standard
  - General enterprise use
  - Supports virtualization and power-saving features

- Enterprise
  - Designed for mission-critical workloads
  - Increased RAM support and failover clustering

- Datacenter
  - Large-scale virtualization
  - Suitable for business-critical applications

- Web Server
  - Optimized for IIS 7.5
  - Intended for internet-facing environments

---

## Installation Methods

### Clean Installation

Pros:
- Fresh start with no legacy conflicts

Cons:
- Time-consuming
- Requires full configuration and patching

### Disk Cloning and System Preparation

1. Master Configuration — Prepare a reference system
2. Sysprep Execution — Remove machine-specific identifiers
3. Sector-by-Sector Copy — Create a system image
4. Image Deployment — Deploy to multiple servers

### Unattended Installation

- Uses autounattend.xml
- Allows hands-off automated setup

### Windows Deployment Services (WDS)

- Network-based installation
- Enables automated large-scale deployment

---

## Maintenance: Windows Updates

- Apply Service Packs regularly
- Install critical patches using Windows Update
- Monitor system health to maintain stability and security

---

## Strategic Planning and Lifecycle

Service Lifecycle:
- Typically 3 to 5 years of active service

Future Planning:
- Anticipate growth to prevent early hardware replacement

ROI Maximization:
- Proper planning ensures scalability, efficiency, and long-term return on investment

---

## Conclusion

This overview highlights the essential aspects of System Administration, including server functionality, hardware subsystems, software selection, deployment strategies, and maintenance practices. Mastery of these components is critical for effective server management and system optimization.

Ready for System Administration? This foundation prepares you for practical implementation and advanced study in real-world IT environments.

---

