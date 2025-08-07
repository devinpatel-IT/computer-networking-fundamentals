# Computer-Networking-Fundamentals

<p align="center">

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/16d4a0b1-0d27-4149-8e40-ca57f769a3bf" height="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/09971a7b-dd02-43ed-82c0-c5a9f91e767f" height="300"/></td>
  </tr>
</table>


</p>

<h1>Windows & Linux VM Communication on Azure with 
Wireshark Network Traffic Analysis)</h1>

Computer networking – Project Overview

This project demonstrates the deployment and configuration of two virtual machines — one running Windows Server and the other Linux (Ubuntu) — in Microsoft Azure, with the objective of enabling secure network communication between them. The primary goal is to simulate cross-platform communication within a cloud environment and analyze the network traffic using Wireshark.

By capturing and inspecting packets, I was able to observe key protocols in action (such as ICMP, SSH, RDP, DNS, and HTTP), evaluate latency, and understand how data moves between systems at a deeper level.

This project bridges cloud infrastructure, operating system administration, and network analysis, making it relevant for roles in cloud operations, cybersecurity, and system administration.


<h1>Skills Demonstrated</h1>

<p>

__1.) Azure Infrastructure Management__

Deployed and configured virtual machines in Azure

Set up virtual networks (VNets), subnets, and security groups

</p>

<br>

<p>

__2.) Cross-Platform System Administration__

Configured a Windows VM and Ubuntu Linux environment

Installed and managed services such as SSH, RDP, and DNS
</p>

<br>


<p>

__3.) Network Security & Access Control__

Created and tested firewall rules using Azure NSGs (Network Security Groups)

Controlled traffic flow and verified security boundaries
</p>

<br>

<p>
  
__4.) Network Traffic Capture & Analysis (Wireshark)__

Captured packets on both VMs

Analyzed traffic protocols (TCP/IP, ICMP, DNS, HTTP, etc.)

Identified key packet headers, handshakes, and data flow patterns

</p>

<br>

<p>


__5.) Use Cases__

Understanding real-world cloud network communication

Practicing network traffic analysis and protocol inspection

Gaining hands-on experience with Azure virtual networking

Demonstrating knowledge in both Windows and Linux environments

</p>

<br />

<h1>Step 1: Deploy Azure Virtual Machines and Virtual Network</h1>

<h3>LINUX VM DEPLOYED</h3>
<img width="2394" height="1035" alt="Screenshot 2025-08-07 154308" src="https://github.com/user-attachments/assets/da300e17-0d62-475f-a359-8cb4d0ab1253" />
<br>


<h3>WINDOWS VM DEPLOYED</h3>
<img width="2413" height="1066" alt="Screenshot 2025-08-07 154353" src="https://github.com/user-attachments/assets/b520c9bd-d534-45b6-b8d7-723a4d9f224e" />
<br>


<h3>VIRTUAL NETWORK ESTABLISHED</h3>
<img width="2283" height="662" alt="Screenshot 2025-08-07 153628" src="https://github.com/user-attachments/assets/fbdb851e-affc-4d57-9f58-3d2072c8fa5c" />
<br>


<h1>Step 2: Use Ping command and observe traffic in Wireshark</h1>


<h3>WINDOWS VM PINGS LINUX VM (10.0.0.5)</h3>
<img width="503" height="378" alt="Screenshot 2025-08-07 160306" src="https://github.com/user-attachments/assets/a7fd9ac1-ae62-4fd5-9909-a54b15619392" />
<br>


<h3>ICMP TRAFFIC OBSERVED IN WIRESHARK</h3>
<img width="1410" height="608" alt="Screenshot 2025-08-07 160510" src="https://github.com/user-attachments/assets/7dfc7698-15ae-49af-b88e-a552b79ec092" />


<h1>Step 3: Use SSH to access Linux VM terminal and observe traffic in Wireshark</h1>


<h3>USE SSH TO ACCESS LINUX TERMINAL FROM WINDOWS VM (10.0.0.5)</h3>
<img width="997" height="763" alt="Screenshot 2025-08-07 160827" src="https://github.com/user-attachments/assets/822bdc8c-3011-405d-b064-07864a513017" />
<br>


<h3>SSH TRAFFIC OBSERVED IN WIRESHARK</h3>
<img width="1409" height="853" alt="Screenshot 2025-08-07 160844" src="https://github.com/user-attachments/assets/968ba8c5-8313-46c2-b0e3-1095d8ef2c88" />


<h1>Step 4: Use DNS commands and observe traffic in Wireshark</h1>


<h3>FIND IP ADDRESS OF MICROSOFT USING NSLOOKUP</h3>
<img width="1003" height="462" alt="Screenshot 2025-08-07 161325" src="https://github.com/user-attachments/assets/5e70f24e-6017-41cf-b61e-a8fbd4a479ea" />
<br>


<h3>OBSERVE DNS TRAFFIC IN WIRESHARK</h3>
<img width="1502" height="637" alt="Screenshot 2025-08-07 161407" src="https://github.com/user-attachments/assets/47abe0b9-9e71-4f93-950e-c513f7c0b95e" />






