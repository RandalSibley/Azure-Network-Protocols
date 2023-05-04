<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://youtu.be/gU8ZmJkoGWc)

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

- Create a resource group in Azure 
- Create a virtual network and subnets
- Download and install WireShark to observe the traffic
- Use PowerShell to communicate between the virtual machine
- Observe the inbound and outbound traffic from WireShark

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/gxOdS6v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this photo I am creating a resource group in Azure with two virtual machines, one running Windows 10 and the other running Ubuntu/Lenix. At the same time I will be creating a virtual network and subnets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/atI0sxI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this photo I will login to both virtual machines using remote desktop. Once logged into VM-1,  I will download and install WireShark to observe the traffic between the two virtual machines.
</p>
<br />

<p>
<img src="https://i.imgur.com/xNhDOLM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this photo I am opening the NSG in the Ubuntu VM in Azure and creating a firewall by disabling inbound ICMP traffic.
</p>
<br />
