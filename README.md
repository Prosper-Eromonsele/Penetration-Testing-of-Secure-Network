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


<h3>Network Diagram:</h3>
<p align="center">
<img src="https://imgur.com/U7HG1gy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br/>
<h3>IP Structure for the Network:</h3>
<p align="center">
<img src="https://imgur.com/QDXrGOn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br/>
<h3>Deploying the VMs:</h3>
<p align="center">
<img src="https://imgur.com/TQKiIUP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<h3>Setting up the CEO PC IP address:</h3>
<p align="center">
<img src="https://imgur.com/QKiOMSe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<h3>Connectivity Test on The Network using ping utility:</h3>
<p align="center">
<img src="https://imgur.com/FWBBJkF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<h3>Performing Scanning Using NMAP Against DNS-Server:</h3>
<p align="center">
<img src="https://imgur.com/1dkUkND.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<h3>Running an Active Scan Using NMAP RESULTS FOR WEB SERVER:</h3>
<p align="center">
<img src="https://imgur.com/NdEC0Xk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<h3>Running a Connectivity Test from a Trusted Network to Untrusted Network:</h3>
<p align="center">
<img src="https://imgur.com/SBWfKHC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<h3>Running a Connectivity Test from a Untrusted Network to Trusted Network:</h3>
<p align="center">
<img src="https://imgur.com/yGawPpd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />
<h3>Capturing Packets Using WireShark:</h3>
<p align="center">
<img src="https://imgur.com/WBTZCnj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br>

<br />


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
