# Wireshark-Firewall
<p>
<img src="https://i.imgur.com/FfOEYxy.png" height="80%" width="80%"/>
</p>
<p>

<h1>Wireshark  - Prerequisites and Installation</h1>
Brief tutorial on how to install and observe firewall.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Ubuntu 

<h2>List of Prerequisites</h2>

- Created Resouce Group
- Windows/Ubuntu Virtual Machines

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/WYsfRU5.png" height="80%" width="80%"/>
</p>
<p>
1. Use remote Desktop to connect to Windows 10 Virtual Machine (take a moment to check the topology, via Azure)
</p>
<br />

<p>
<img src="https://i.imgur.com/yGc1e9W.png" height="80%" width="80%"/>
</p>
<p>
2. Login using created username and password.
3. Download Wireshark via, Wireshark.com.

</p>
<br />

<p>
<img src="https://i.imgur.com/vRJVQ5h.png" width="80%"/>
</p>
<p>
4. Download and install Wireshark.
</p>
<br />

<p>
<img src="https://i.imgur.com/1v6bEPj.png" height="80%" width="80%"/>
</p>
<p>
6. Observe ICMP Traffic.

<p>
<img src="https://i.imgur.com/Ag3CujO.png"80%" width="80%"/>
</p>
<p>
7. Ping private address of Ubuntu VM and ping address in Windows /
8. In Wireshark put IMCP in the search area, observe traffic, and prepare to block chosen traffic.

<p>
<img src="https://i.imgur.com/YK7v4j9.png" height="80%" width="80%"/>
</p>
<p>
10. Add security rule for IMCP traffic; deny, "anything."

<p>
<img src="https://i.imgur.com/Dx6QmE0.png" height="80%" width="80%"/>
</p>
<p>
11. Observe the traffic, and what has been blocked due to the new rule. (Switch to DHCP traffic not, DNS)
</p>
<br />

<p>
<img src="https://i.imgur.com/mmolGPg.png" height="80%" width="80%"/>
</p>
<p>
12. Observe DHCP traffic, use ipconfig to find the ethernet information.
</p>
<br />

<p>
<img src="https://i.imgur.com/HTnmtgc.png" height="80%" width="80%"/>
</p>
<p>
12. Observe SSH traffic, ping the private address of Ubuntu VM.
</p>
<br />

<p>
<img src="https://i.imgur.com/yxr1j5W.png" height="80%" width="80%"/>
</p>
<p>
13. Observe DNS traffic.
</p>
<br />

<p>

