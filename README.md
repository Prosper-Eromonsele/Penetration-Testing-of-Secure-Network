 # Penetration-Testing-of-Secure-Network

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)
 
<h2>Description</h2>
<br>
This project demonstrates how penetration testing can be used to assess and strengthen the security of a virtualized network environment. The network is segmented into Trusted, Un-trusted, and DMZ zones, with traffic managed by a pfSense firewall.

A Production Server was introduced into the Trusted zone, and various attack simulations were performed using Kali Linux tools to test the effectiveness of firewall rules, access controls, and network isolation.

The goal was to identify vulnerabilities, validate security configurations, and ensure that untrusted actors could not breach the trusted environment. This practical test highlights the importance of proactive security measures in modern network design.
<br/>

<h2>The Virtual Environment Includes:</h2>
<br>
🌐 Web Server

🔥 Router-Firewall (pfSense)

🖥️ CEO Workstation and Trusted User PC

🖥️ Production Server

📡 DNS Server

🛡️ Demilitarized Zone (DMZ)

This repository serves as a practical showcase of secure network design, virtualization strategy, and access control implementation—ideal for IT professionals, students, and cybersecurity enthusiasts.
<br />



<h2>Project walk-through:</h2>

<p align="center">
  <h2>Network Diagram:</h2>
</p>

<p align="center">
<img src="https://imgur.com/JZo1QHT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<h2>IP Structure for the Network:</h2>
<p align="center">
<img src="https://imgur.com/uIL8r5z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br/>
<br>

<br/>
<h2>Deploying the VMs:</h2>
<p align="center">
<img src="https://imgur.com/vnPLPZp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>
Installation of the supplied Production server VM INTO Trusted network!
<br />
<h2>A diagnostic scan using Nmap on the Production Server:</h2>
<p align="center">
<img src="https://imgur.com/64VVZwb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>
Conducting a comprehensive Nmap scan to enumerate open ports, service versions, and operating system details on the production server.
<br />
<br>

<br/>
<h2>Performed initial vulnerability exploitation:</h2>
<p align="center">
<img src="https://imgur.com/HYIvhjp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>
Performed initial vulnerability exploitation on a live server using Metasploit’s msfconsole, targeting CVE-2011-2523 in VSFTPD 2.3.4, and demonstrating proficiency in penetration testing and post-exploitation techniques.
<h3>CVE-2011-2523 — Vulnerability Overview</h3>
VSFTPD version 2.3.4 contains a critical backdoor vulnerability (CVE-2011-2523) introduced in versions downloaded between June 30 and July 3, 2011. This backdoor opens a shell on TCP port 6200, allowing unauthenticated remote access to the system. Exploitation of this flaw can lead to full compromise of the FTP server, exposing sensitive data and potentially enabling further lateral movement within the network

<br />
<br>

<br/>
<h2>Performing Scanning Using NMAP Against DNS-Server:</h2>
<p align="center">
<img src="https://imgur.com/1dkUkND.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<br>

<br/>
<h3>Running an Active Scan Using NMAP RESULTS FOR WEB SERVER:</h3>
<p align="center">
<img src="https://imgur.com/NdEC0Xk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<br>

<br/>
<h2>Running a Connectivity Test from a Trusted Network to Untrusted Network:</h2>
<p align="center">
<img src="https://imgur.com/SBWfKHC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<br>

<br/>
<h2>Running a Connectivity Test from a Untrusted Network to Trusted Network:</h2>
<p align="center">
<img src="https://imgur.com/yGawPpd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<br>

<br/>
<h2>Capturing Packets Using WireShark:</h2>
<p align="center">
<img src="https://imgur.com/WBTZCnj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<br>

<br/>


<h2>Conclusion</h2>

<br>This project marks a significant milestone in advancing the company's IT capabilities while adhering to strict space and budget limitations. By leveraging virtualization technologies, I successfully transformed a constrained environment into a secure, scalable, and efficient network infrastructure. The deployment of key components including a Web Server, Router-Firewall, DNS Server, DMZ, and dedicated workstations ensures robust performance, enhanced security, and future-proof flexibility.
The implementation not only meets current operational demands but also lays a solid foundation for seamless expansion and integration of future technologies. Through strategic planning and execution, this project demonstrates how innovative thinking and technical expertise can overcome resource limitations and deliver enterprise-grade solutions.
As one of my key projects, it reflects my commitment to practical problem-solving, secure system design, and scalable architecture core principles that I will continue to apply in future IT initiatives.
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
