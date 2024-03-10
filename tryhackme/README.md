# TryHackMe Instructions

All instructions are applicable to kali linux, since kali is the biggest linux distro for pentesters  
and that is also what I use everyday.

Before starting your work on any tryhackme rooms, you need to establish a VPN connection to the tryhackme network. This  
will allow you to be able to scan, test and connect to the live virtual machines that you boot up, as if being directly connected  
to the tryhackme LAN (Local Area Network).

Follow the steps below to access the tryhackme network from your machine:

1. Click on your avatar (upper right corner of the screen).
2. Select **Access** from the dropdown menu.
3. In the machines tab, under VPN server select a region that is closest to your physical location.
4. Click **Download configuration file** and save the downloaded file somewhere in your file system.
5. Open up **Terminal** and type in `sudo openvpn <location of the downloaded file>`.
6. The connection should be complete when you read **Initialization Sequence Completed** toward the bottom of the openvpn output.