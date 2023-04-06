# Configuring Active Directory Within Azure
<p>
<img src="https://i.imgur.com/UyS596d.png" height="80%" width="80%"/>
</p>
<p>

<h1>Active Directory  - Prerequisites and Installation</h1>
Brief tutorial on how to install and use Active Directory.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Ubuntu 

<h2>List of Prerequisites</h2>

- Created Resouce Group
- Windows/Ubuntu Virtual Machines

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/uSYum1d.png"80%" width="80%"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/1vaZnic.png" height="80%" width="80%"/>
</p>
<p>


</p>
<br />

<p>
<img src="https://i.imgur.com/F5xnPBY.png" width="80%"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/IiWeC4q.png" height="80%" width="80%"/>
</p>
<p>
6. Observe ICMP Traffic.

<p>
<img src="https://i.imgur.com/LnvE2LN.png"80%" width="80%"/>
</p>
<p>
7. Ping private address of Ubuntu VM and ping address in Windows /
8. In Wireshark put IMCP in the search area, observe traffic, and prepare to block chosen traffic.

<p>
<img src="https://i.imgur.com/3RzWlbw.png" height="80%" width="80%"/>
</p>
<p>
10. Add security rule for IMCP traffic; deny, "anything."

<p>
<img src="https://i.imgur.com/8jkkZct.png" height="80%" width="80%"/>
</p>
<p>
11. Observe the traffic, and what has been blocked due to the new rule. (Switch to DHCP traffic not, DNS)
</p>
<br />

<p>
<img src="https://i.imgur.com/AMjJjsr.png" height="80%" width="80%"/>
</p>
<p>
12. Observe DHCP traffic, use ipconfig to find the ethernet information.
</p>
<br />

<p>
<img src="https://i.imgur.com/SFqdjbU.png" height="80%" width="80%"/>
</p>
<p>
12. Observe SSH traffic, ping the private address of Ubuntu VM.
</p>
<br />

<p>
<img src="https://i.imgur.com/d3TGm5M.png" height="80%" width="80%"/>
</p>
<p>
13. Observe DNS traffic.
</p>
<br />

<p>

