<h1>Using Atomic Red Team to activate Events on Splunk</h1>



<h2>Description</h2>
This project utilizes Atomic Red Team's comprehensive library of adversary emulation techniques to simulate real-world cyber threats. By leveraging Atomic Red Team's PowerShell payloads, we aim to activate specific events on Splunk, a leading SIEM platform, by invoking PowerShell commands on target machines. This approach allows us to validate the effectiveness of our detection and response capabilities within Splunk, ensuring our organization is well-prepared to detect and mitigate potential cyber threats.





<br />


<h2>Tools Used</h2>

- <b>Atomic Red Team</b>
- <b>Mitre Att&ck framework</b>

<h2>Environments Used </h2>

- <b>VirtualBox VM</b>
- <b>Kali Linux</b>
- <b>Windows 10</b>
- <b>Windows Server 22</b>
- <b>Ubuntu Server 22.04</b>

<h2>Project walk-through:</h2>

<p align="center">
Network Diagram: <br/>
<img src="https://imgur.com/pEdUmkX.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
  
<h2>Using Mitre Att&ck Framework and Atomic Red Team:</h2>

Our project integrates the MITRE ATT&CK framework and Atomic Red Team methodology to simulate and assess cyber threats. Specifically, we leverage these frameworks to execute PowerShell commands on target systems, mimicking adversary behavior. This approach enables us to comprehensively test our organization's detection and response capabilities against real-world attack scenarios, enhancing our cyber defense posture and resilience.
  
<br />

<p align="center">
Mitre Att&ck framework: <br/>
<img src="https://imgur.com/W8NQ80l.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Atomic Red Team: <br/>
<img src="https://imgur.com/Dv6FAeh.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Invoke Atomics T1059.001 : <br/>
<img src="https://imgur.com/gvoZp1C.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
Splunk showing Powershell being used: <br/>
<img src="https://imgur.com/WQa6etw.png" height="80%" width="80%" alt="Project walk-through"/> 

  
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
