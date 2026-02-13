# Week 2: System Administration (S.A) Operating Systems 

System Administration involves managing servers that provide resources, services, and data to clients. 

Key components include processors, RAM, storage, and network interfaces. Servers perform roles like file and print services, web hosting, and remote access. 

Bottlenecks arise from subsystem failures or over-utilization, impacting overall performance. 

Windows Server 2008 R2, a 64-bit OS, offers editions tailored to different needs, from small businesses to large-scale enterprises. 

Installation methods include clean installs, upgrades, disk cloning, and network-based deployments. 

Strategic planning emphasizes lifecycle management and future scalability to maximize ROI. 

Regular updates and monitoring are essential for maintaining system stability and performance.  

---

## Major Topics Outline  

- **Key Terms and Fundamentals**  
  - Bottleneck  
  - NIC (Network Interface Card)  
  - Volatile Memory  
- **Understanding What a Server Does**  
  - Primary Functions  
  - Form Factors  
  - Common Types  
- **Primary Subsystems of a Server**  
  - Processor  
  - Memory (RAM)  
  - Storage  
  - Network  
- **Primary Server Roles**  
  - File and Print Services  
  - Web Services (IIS 7.5)  
  - Application and Email  
  - Remote Access  
- **Identifying System Bottlenecks**  
  - Resource Strain  
  - Systemic Impact  
- **Selecting the Software Architecture**  
  - Windows Server 2008 R2 Editions  
  - Installation Methods  
  - Windows Updates  
- **Strategic Planning and Lifecycle**  
  - Service Lifecycle  
  - Future Horizon  
  - ROI Maximization  

---

## Glossary  

- **Bottleneck** — A subsystem failure or over-utilization that limits the entire system performance.  
- **NIC (Network Interface Card)** — Hardware enabling communication between server and clients.  
- **Volatile Memory** — Data that is lost when power is removed, specifically referring to RAM.  

---

## Section Summaries  

### **Understanding What a Server Does**  

- A server is a high-performance computer providing resources, services, or data to other devices.  
- Primary functions include hosting applications, managing data, processing client requests, and providing authentication.  
- Common server types include web, database, file, and mail servers.  

### **Primary Subsystems of a Server**  

- Processor acts as the system's brain, performing calculations.  
- RAM provides short-term, volatile memory for instructions and data.  
- Storage includes HDDs and SSDs for long-term data retention.  
- Network connectivity is enabled via NIC for client-server interaction.  

### **Primary Server Roles**  

- File services manage shared documents and network printing.  
- Web services host websites and applications using IIS 7.5.  
- Application and email servers support business apps and communication.  
- Remote access enables secure connections outside the physical network.  

### **Identifying System Bottlenecks**  

- Bottlenecks occur due to subsystem failure or over-utilization.  
- A single weak component can degrade entire system performance.  
- Focus on monitoring processor, memory, storage, and network health.  

### **Selecting the Software Architecture**  

- Windows Server 2008 R2 is strictly 64-bit with no 32-bit version.  
- Editions include Foundation, Standard, Enterprise, and Datacenter.  
- Installation methods include clean install, upgrade, disk cloning, and WDS.  

### **Strategic Planning and Lifecycle**  

- Servers typically have a 3-5 year service lifecycle.  
- Plan for future growth to maximize ROI.  
- Regular updates and patches are crucial for system stability.  

---

## Technical Specifications  

- **Network Connection**: Minimum Card Speed: 100 Mbps, Standard Server Speed: 1 Gbps, Lifecycle Estimate: 3-5 years  
- **Windows Server 2008 R2**: Strictly 64-bit architecture, no 32-bit version available  

---

## Comparisons  

### **HDD vs SSD**  

#### **HDD**  

- Mechanical rotating platters  
- Slower access times  

#### **SSD**  

- Purely electronic with no moving parts  
- Faster access times  

### **Clean Install vs Upgrade**  

#### **Clean Install**  

- Fresh start, no legacy configuration  
- Time-consuming, requires extensive patching  

#### **Upgrade**  

- Retains settings from older version  
- Not supported for 32-bit to 64-bit in WS2008 R2  

---

## Procedures  

### **Disk Cloning and System Prep**  

1. **Master Configuration**: Configure a reference computer with necessary software and settings.  
2. **Sysprep Execution**: Use the System Preparation Tool to remove machine-specific identifiers.  
3. **Sector-by-Sector Copy**: Create an image file of the master disk.  
4. **Image Deployment**: Apply the captured image to multiple destination servers.  

---

## Windows Server 2008 R2 Editions 

### **Foundation**  

**Target Audience**: Small businesses  
**Scalability Level**: Low  
**Key Features**:  
- Cost-effective  
- Supports fewer than 15 users  

### **Standard**  

**Target Audience**: General Enterprise  
**Scalability Level**: Medium  
**Key Features**:  
- Virtualization support  
- Power savings  

### **Enterprise**  

**Target Audience**: Mission-Critical  
**Scalability Level**: High  
**Key Features**:  
- Increased RAM support  
- Failover clustering  

### **Datacenter**  

**Target Audience**: Large-scale  
**Scalability Level**: Very High  
**Key Features**:  
- Business-critical applications  
- Large-scale virtualization  

---

## Best Practices and Recommendations 

- Regularly apply Windows Updates and Service Packs for system stability.  
- Plan for future growth to avoid early hardware refreshes.  
- Monitor subsystem health to prevent bottlenecks.
