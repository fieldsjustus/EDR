<h1>Install Wazuh Agent & Simulate Attack on Windows Endpoint</h1>

 ### [Lab Instructions](https://app.cybrary.it/browse/virtual-lab/edr-basics?queryID=undefined&objectID=70440)

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Program walk-through:</h2>

<p align="center">
Display IP of Wazuh agent: <br/>
<img width="752" alt="Image" src="https://github.com/user-attachments/assets/a9e9feba-f507-4dee-9e41-d682ee7ff0f9" />
<img width="753" alt="Image" src="https://github.com/user-attachments/assets/1e540984-1f0b-4126-8834-3eec05f771bf" />
<br />
Deploy new agent:  <br/>
<img width="752" alt="Image" src="https://github.com/user-attachments/assets/6290c829-88ac-4808-8f97-a6aaac224bf9" />
<br />
<br />
Edit Windows configuration file to allow collected logs from Sysmon: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ennsure Wazuh agent is running:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Simulate Attack:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Invoke-AtomicTest command:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
