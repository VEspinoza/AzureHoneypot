<h1>Azure Honeypot Lab</h1>

<h2>Description</h2>
Project consists of creating a simple honeypot environment through Microsoft Azure. This involves creating a Windows 10 virtual machine with the firewall turned off. We configure a report in Microsoft Sentinal to check for failed RDP log in attempts. The report is generated using KQL, the query language used in Azure. We also use a powershell script in the windows 10 machine to continually update a log with these failed log in attempts that we source from windows' event viewer.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Microsoft Azure Virutal Machines</b>
- <b>KQL</b>
- <b>Microsoft Sentinal</b>
- <b>Microsft Defender for Cloud</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Microsoft Azure</b>

<h2>Program walk-through:</h2>
Our Windows Server 2019 virtual machine will be configured with 2 NICs. One to access the internet and one for our internal network. It will act as our Domain Controller, DHCP server, and a DNS server.
<br/>
<br/>

<p align="center">
Place holder text: <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text <br/>
<br/>
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text <br/>
<br/>
Place holder text: <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br/>
<br/>
Place holder text: <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text <br/><br/>
Place holder text: <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br/>
<br/>
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text <br/><br/>
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text:  <br/>
<img src="https://i.imgur.com/" height="80%" width="80%" alt="Azure Setup"/>
<br />
<br />
Place holder text
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
