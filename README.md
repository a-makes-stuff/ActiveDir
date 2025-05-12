<h1>Active Directory Setup</h1>

<h2>Description</h2>
This simulation consists of using Virtual Box to simulate Domain controller to add users to our Active Directory Setup. I used Windows 10 installed Virtual Machines to simulate Clients and We also use a powershell script to simulate Adding 1000 users to the active directory 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows Server 19(Domain Controller)</b> 
- <b>Windows 10</b> (21H2)
- <b>VirtualBox</b> 

<h2>Simulation walk-through:</h2>


<p align="center">

Architecture for the simulation : <br/>
<img src="1.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Setup Domain Controller in Virtual Box: <br/>
<img src="DS.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Install Active Directory Software onto The domain controller :  <br/>
<img src="ADS install.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Configuring DHCP: <br/>
<img src="Configure DHCP.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
NAT Setup<br/>
<img src="NAT Setup.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Run powershell Script in the VM to add users from text file <br/>
<img src="ps script.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Create Client VM <br/>
<img src="Creating Client VM.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Verify the users that have been added can access the Network using credentials <br/>
<img src="client.png" height="80%" width="80%" alt="loading"/>
<br />
<br />

