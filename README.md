<h1>Performing Packet Capture and Traffic Analysis</h1>

<h2>Tools and Software Used</h2>

- <b>Wireshark</b> 
- <b>PuTTY</b>
- <b>FileZilla</b>
- <b>Mininet-WiFi</b>
- <b>Airodump-ng</b>
- <b>Aireplay-ng</b>


<h2>Environments Used </h2>

- <b>Switch01 (Linux: Debian 11)</b>
- <b>pfSense Office (FreeBSD)</b>
- <b>Mininet01 (Linux: Ubuntu 20)</b>
    Ap1
    Sta1
    Sta2
    Sta3

 
<h2>Description</h2>
Project consists of using Wireshark;s analysis capabilities to review captured traffic at a packet level: running a capture session and generating common network traffic, using Wireshark to analyze the captured data.
<br />

### Section 1

<h2>Scan the Network with Zenmap:</h2>








<p align="center">
Show the contents of the Ports/Hosts tab from the SYN scan for fileserver01.securelabsondeman.com: <br/>
<img src="https://i.imgur.com/RsdN9Aa.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the contents of the Host Details from the OS scan for fileserver01.securelabsondemand.com:  <br/>
<img src="https://i.imgur.com/ptaiUzA.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the details in the Ports/Hosts tab from the Service scan for fileserver01.securelabsondemand.com: <br/>
<img src="https://i.imgur.com/6yb1r5n.png" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Conduct a Vulnerability Scan with Nessus:</h2>







<p align="center">
Show the Nessus report summary: <br/>
<img src="https://i.imgur.com/TJrpqi7.png" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Evaluate Your Findings:</h2>







<p align="center">
Summarize the selected vulnerability, icluding the CVSS risk score, and recommend a mitigation strategy: <br/>
<img src="https://i.imgur.com/RfV3hV2.png" height="80%" width="80%" alt="Section 1 Steps"/>

 ### Section 2

<h2>Scan the Network with Nmap:</h2>










<p align="center">
Show the results of the traceroute command: <br/>
<img src="https://i.imgur.com/Dx587yu.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the results of the Nmap scan with the OS detection activated:  <br/>
<img src="https://i.imgur.com/I9cwbXR.png" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Conduct a Vulnerability Scan with OpenVAS:</h2>










<p align="center">
Show the detailed OpenVAS scan results: <br/>
<img src="https://i.imgur.com/ynJCPgr.png" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Prepare a Penetration Test Report:</h2>










<p align="center">
Target, Purpose, Scope: <br/>
<img src="https://i.imgur.com/Gb4ZcwM.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Summary of Findings: <br/>
<img src="https://i.imgur.com/fOviUv5.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Conclusion: <br/>
<img src="https://i.imgur.com/HBNtH8v.png" height="80%" width="80%" alt="Section 1 Steps"/>


### Section 3

<h2>Scan the Domain Controller with Nmap:</h2>










<p align="center">
Show the results of your targeted port scan on the domain controller: <br/>
<img src="https://i.imgur.com/Ef2Qtkf.png" height="80%" width="80%" alt="Section 1 Steps"/>



 <h2>Scan the Domain Controller with Nessus:</h2>










<p align="center">
Show the Nessus report summary for the domain controller: <br/>
<img src="https://i.imgur.com/dcbpBmC.png" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Prepare a Penetration Test Report:</h2>










<p align="center">
Target, Purpose, Scope: <br/>
<img src="https://i.imgur.com/kmqOzU8.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Summary of Findings: <br/>
<img src="https://i.imgur.com/se7lBVR.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Conclusion: <br/>
<img src="https://i.imgur.com/UKaA59e.png" height="80%" width="80%" alt="Section 1 Steps"/>



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
