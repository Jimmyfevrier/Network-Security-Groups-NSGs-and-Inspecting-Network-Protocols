<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1: I created a Virtual Machine (VM) in Azure using Window 10 Pro
- Step 2: Installed Microsoft Remote Desktop (for Mac) 
- Step 3: Installed Wireshark onto the VM
- Step 4: Observed various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)

<h2>Actions and Observations</h2>

<p><h3> ICMP </h3> </p>
<p>
ICMP (Internet Control Message Protocol) which is used by network devices like routers and computers to send error messages and information in order to help diagnose network problems and manage traffic. 

  Within the VM that I created, I was able to observe this traffic in Wireshark.
</p>
<p>
<<img width="858" alt="Image" src="https://github.com/user-attachments/assets/e1764ef2-2d73-4300-afbc-59c1da5ef404" />
</p>

<br />
<p><h3> SSH </h3> </p>
<p> 
SSH (Secure Shell) sends a stead flow of encripted data to prevent other from being about to see what messeage is being sent across the network. 

  You can use it to: 
  - remotely control another computer (like logging into a server from far away)
  - Run commands on it.
  - Transfer files securely.
</p>
<br>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
