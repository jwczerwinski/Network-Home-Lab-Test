<h1>Network Home Lab</h1>

<h2>Description</h2>
Virtualize Network Home Lab with GNS3 and VMware Workstation Player. Install and configure NAT, DNS and DHCP on Ubuntu Linux Server. Deploy and configure a Windows admin client to manage network infrastructure and a Kali Linux user client. Configure 3 routers with static routes, OSPF, QoS and SNMP. Configure 3 swtiches with VLANs, RSTP, QoS, security features/protocols, VRRP and SNMP. Configure 1 firewall with ACLs, IPS/IDS, antivirus, VPN, content filtering, segmented security zones and implicit deny rules. <br />

<h2>Languages and Utilities Used</h2>
- <b>PowerShell</b> <br />
- <b>Bash</b> 

<h2>Environments Used </h2>
- <b>GNS3</b> (2.2.43) <br />
- <b>VMware Workstation 17 Player</b>  <br />
- <b>Kali</b> <br />
- <b>Windows 10</b> (22H2) <br />
- <b>Ubuntu Server</b> (22.04.3) <br />
- <b>Cisco 7200</b> (153-3.XB12) <br />
- <b>Cisco ASAv</b> (9.16.2 CML) <br />
- <b>Cisco IOSvL2</b> (15.2(20200924:215240)) <br />

<h2>Diagram </h2>
<img src="https://i.imgur.com/X1JOLQk.png" height="80%" width="80%" />

<h2>Walk-through:</h2>
<p align="center">
 
[Download GNS3](https://www.gns3.com/software/download)<br />
[Download VMware Workstation 17 Player](https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html)<br /> 
[Download Kali](https://www.kali.org/get-kali/#kali-virtual-machines)<br /> 
[Download Windows 10](https://www.microsoft.com/software-download/windows10)<br />
[Download Ubuntu Server](https://ubuntu.com/download/server)<br />
[Download Cisco 7200](https://www.gns3.com/marketplace/featured/cisco-7200)<br />
[Download Cisco ASAv](https://www.gns3.com/marketplace/featured/cisco-asav)<br />
[Download IOSvL2](https://www.gns3.com/marketplace/featured/cisco-iosvl2)<br />

<br />
<br />
While installing VMware Workstation Player select Enhanced Keyboard Driver. Open GNS3 VM.ova file to import GNS3 VM into VMware Workstation Player. In VMware, Edit virtual machine settings for GNS3 VM to be 8 GB RAM, 4 CPU cores and 40 GB storage: <br/>
<img src="https://i.imgur.com/UayaJ9M.png" height="80%" width="80%" />
<img src="https://i.imgur.com/dmumRjj.png" height="80%" width="80%" />
<img src="https://i.imgur.com/ES5lToG.png" height="80%" width="80%" />
<img src="https://i.imgur.com/E6KwymH.png" height="80%" width="80%" />
<br />
<br />
While installing GNS3 select GNS3 VM, VMware Workstation, and "No" to SolarWinds. Start GNS3, while in the setup wizard, add the GNS3 VM: <br/>
<img src="https://i.imgur.com/VtmYWLI.png" height="80%" width="80%" />
<img src="https://i.imgur.com/EmOB8FV.png" height="80%" width="80%" />
<img src="https://i.imgur.com/DRa1tFv.png" height="80%" width="80%" />
<img src="https://i.imgur.com/9y7nyWw.png" height="80%" width="80%" />
<br />
<br />
Import GNS3 Appliance images: See diagram for appliances and NICs: File > Import Appliance > select images "cisco-7200.gns3a", "cisco-asav.gns3a", and "cisco-iosvl2.gns3a": <br/>
<img src="https://i.imgur.com/VtmYWLI.png" height="80%" width="80%" />
<br />
<br />


