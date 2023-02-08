<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/Virtual_Private_Network_overview.svg/330px-Virtual_Private_Network_overview.svg.png" alt="Virtual Private Networks"/>
</p>

<h1>Setting Up and Using A Virtual Private Network (VPN) with an Azure Virtual Machine</h1>
This tutorial will observe the setup and use of a VPN on an Azure Virtual Machine. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN Client

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

**Part 1(Create Virtual Machine in Azure)**
- Browse to https://whatismyipaddress.com/ and take note of this in a text file
- Create a Resource Group
- Create a Windows 10 Virtual Machine in another geographic location (try a different country)
- Log into the VM with Remote Desktop
- Browse to https://whatismyipaddress.com/ and take note of this in a text file

**Part2(Sign up for ProtonVPN and test the VPN connection)**
- On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
- Back within your VM, download the Proton VPN client
- Login to the VPN and choose a VPN server in yet another country (such as Japan)
- Browse to https://whatismyipaddress.com/  and take note of this in a text file
- Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different


<h2>Example Screenshots</h2>

