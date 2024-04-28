<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


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

- Step 1 - Create Resources; Create a Resource Group, Create a Windows 10 Virtual Machine (VM), Create a Linux (Ubuntu) VM, Observe Virtual Network within Network Watcher
- Step 2 - Observe ICMP Traffic; Use Remote Desktop to connect to Windows 10 Virtual Machine, Within Windows 10 Virtual Machine Install Wireshark, Open Wireshark and filter for ICMP traffic only,
Retrieve the private IP address of the Ubuntu VM and attempt to ping it from within the Windows 10 VM, Observe ping requests and replies within WireShark, From The Windows 10 VM open command line or PowerShell and attempt to ping a public website and observe the traffic in WireShark, Initiate a perpetual/non-stop ping from Windows 10 VM to Ubuntu VM
- Step 3 - Observe SSH Traffic; In Wireshark, filter for SSH traffic only.
- Step 4 - Observe DHCP Traffic; In Wireshark, filter for DHCP traffic only.
- Step 5 - Observe DNS Traffic; In Wireshark, filter for DNS traffic only.
- Step 6 - Observe RDP Traffic; In Wireshark, filter for RDP traffic only.


