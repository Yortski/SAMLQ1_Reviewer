# WEEK 4 S.A DEVICES, DEVICE DRIVERS, MANAGEMENT CONSOLE AND ADMINISTRATIVE TOOLS

This lecture covers essential aspects of device and server management in system administration. 

Key topics include managing devices and device drivers, understanding Plug and Play technology, and the importance of signed drivers. 

The Microsoft Management Console (MMC) and various administrative tools are discussed, highlighting their roles in system management. 

Remote Server Administration Tools (RSAT) are introduced for managing server roles remotely. 

The lecture also explains server roles, services, and the Windows Registry structure, emphasizing their significance in system configuration and security. 

Best practices include regular driver updates, using signed drivers, and leveraging RSAT for efficient remote management.

---

## Major Topics Outline 

- **Managing Devices and Device Drivers**  
  - Understanding Plug and Play Devices  
  - Understanding Signed Drivers  
  - Using Devices and Printers  
  - Using Device Manager  
- **Microsoft Management Console and Administrative Tools**  
  - Overview of MMC  
  - Common Administrative Tools  
- **Computer and Server Management Consoles**  
  - Using Computer Management Console  
  - Using Server Management Console  
- **Remote Server Administration Tools**  
  - Overview of RSAT  
  - RSAT Roles  
- **Managing Roles and Features**  
  - Server Roles  
  - Managing Services  
- **Windows Registry**  
  - Registry Structure  
  - Registry Hives  

---

## Glossary 

- **Device Driver** — A program that controls a device, acting as a translator between the device and the operating system.  
- **Plug and Play (PnP)** — A technology allowing devices to be automatically recognized and configured upon installation.  
- **Signed Driver** — A device driver with a digital signature indicating its publisher and verifying its integrity.  
- **Microsoft Management Console (MMC)** — A framework for hosting administrative tools, providing a standard interface for managing Windows and network services.  
- **Server Role** — A set of software programs enabling a computer to perform specific functions for multiple users.  
- **Service** — A program or process performing specific system functions to support other programs or provide network services.  
- **Registry** — A central database storing hardware, software, and security configuration information for Windows.  


---

## Section Summaries 

### **Managing Devices and Device Drivers**  

- Device drivers act as translators between devices and the OS.  
- Plug and Play automates device recognition and configuration.  
- Signed drivers ensure driver integrity and publisher verification.  

### **Microsoft Management Console and Administrative Tools** 

- MMC provides a standard interface for administrative tools.  
- Administrative Tools folder contains utilities for system management.  

### **Remote Server Administration Tools**  

- RSAT enables remote management of Windows Server roles.  
- Includes tools for AD DS, DHCP, DNS, and more.  

---

## Technical Specifications

- **System Resources Managed by Device Manager**:  
  - Interrupt request (IRQ) line numbers  
  - Direct memory access (DMA) channels  
  - Input/output (I/O) port addresses  
  - Memory address ranges  
- **Driver Management Options**:  
  - Driver Details  
  - Update Driver  
  - Roll Back Driver  
  - Disable/Enable  
  - Uninstall  
- **Administrative Tools**:  
  - **Component Services**: Configure and administer Component Object Model (COM) components.  
  - **Computer Management**: Manage local or remote computers using a consolidated tool.  
  - **Event Viewer**: View significant events recorded in event logs.  
  - **Performance Monitor**: View advanced system information about processor, memory, hard disk, and network performance.  
  - **Task Scheduler**: Schedule programs or tasks to run automatically.  
- **RSAT Roles**:  
  - Active Directory Certificate Services Tools  
  - Active Directory Domain Services (AD DS) and Active Directory Lightweight Directory Services (AD LDS) Tools  
  - DHCP Server Tools  
  - DNS Server Tools  
  - Hyper-V Tools  
  - Network Policy and Access Services Tools  
  - Failover Clustering Tools  
- **Roles and Features**:  
  - **Server Role**: A set of software programs that enable a computer to perform a specific function for multiple users.  
  - **Service**: A program, routine, or process that performs a specific system function to support other programs or provide a network service.  
- **Service Startup Types**:  
  - Automatic  
  - Automatic (Delayed Start)  
  - Manual  
  - Disable  
- **Example Services**:  
  - Server  
  - Workstation  
- **Registry Structure**:  
  - A central, secure database storing hardware and software configuration information and system security policies.  
- **Registry Hives**:  
  - **HKEY_CLASSES_ROOT**: Stores information about registered applications and file associations.  
  - **HKEY_CURRENT_USER**: Stores settings specific to the currently logged-in user.  
  - **HKEY_LOCAL_MACHINE**: Stores settings specific to the local computer.  

---

## Section Summaries 

### **Managing Devices and Device Drivers**  

- Device drivers act as translators between devices and the OS.  
- Plug and Play automates device recognition and configuration.  
- Signed drivers ensure driver integrity and publisher verification.  
- Device Manager provides a graphical interface for managing hardware.  

### **Microsoft Management Console and Administrative Tools**  

- MMC is a primary tool for managing Windows and network services.  
- Administrative Tools include utilities for system and network management.  
- Computer and Server Management consoles consolidate common MMC snap-ins.  
- Remote Server Administration Tools enable remote management of servers.  

### **Managing Roles, Services, and the Registry**  

- Server roles define specific functions for a computer.  
- Services run in the background to support system and network functions.  
- The registry stores critical configuration and security information.  

---

## Best Practices and Recommendations 
 
- Regularly update device drivers to ensure compatibility and security.  
- Use signed drivers to prevent unauthorized or corrupted drivers from being installed.  
- Leverage RSAT for efficient remote server management.
