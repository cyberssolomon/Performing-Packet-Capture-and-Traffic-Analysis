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
    Ap1,
    Sta1,
    Sta2,
    Sta3,

 
<h2>Description</h2>
Project consists of using Wireshark's analysis capabilities to review captured traffic at a packet level: running a capture session and generating common network traffic, using Wireshark to analyze the captured data.
<br />

### Section 1

<h2>Configure Wireshark and Generate Network Traffic:</h2>








<p align="center">
Show the successful FTP and SFTP file transfers: <br/>
<img src="https://i.imgur.com/ui0CKSW.png" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Analyze Traffic Using Wireshark:</h2>







<p align="center">
Show the ICMP Payload: <br/>
<img src="https://i.imgur.com/LrI1tkL.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Last Login information in the Packet Details pane:  <br/>
<img src="https://i.imgur.com/0oihPmF.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the SSHv2 encryption and mac selections for the SSH connection:  <br/>
<img src="https://i.imgur.com/Hl3WgQL.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the highlighted encrypted data in the Packet Bytes pane:  <br/>
<img src="https://i.imgur.com/yMFpc6U.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the passive port specified by the FTP server in the Packet Details pane:  <br/>
<img src="https://i.imgur.com/34MYpz0.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Destination Port field value in the Packet Details pane:  <br/>
<img src="https://i.imgur.com/hFjkHSp.png" height="80%" width="80%" alt="Section 1 Steps"/>



 

 ### Section 2

<h2>Configure Wireshark and Generate Network Traffic:</h2>










<p align="center">
Show the sta1-wlan0 connected to the SecureLabs-WiFi network: <br/>
<img src="https://i.imgur.com/49vAuBq.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the updated security mode on the Status page:  <br/>
<img src="https://i.imgur.com/AcqhIdC.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the connection to the now-encrypted WLAN:  <br/>
<img src="https://i.imgur.com/Xuqyk6u.png" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Analyze Traffic Using Wireshark:</h2>










<p align="center">
Show the SSID and channel in the Packet Details pane: <br/>
<img src="https://i.imgur.com/wWAr1pH.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Packet Details for the ICMP packet:  <br/>
<img src="https://i.imgur.com/A179tO3.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the Packet Details for the HTTP packet:  <br/>
<img src="https://i.imgur.com/VzYHDMR.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the key information for Message 3 in the four-way handshake:  <br/>
<img src="https://i.imgur.com/ORj7kYF.png" height="80%" width="80%" alt="Section 1 Steps"/>





 ### Section 3

<h2>Generate Malicious Network Traffic:</h2>










<p align="center">
Show the aireplay-ng --deauth output: <br/>
<img src="https://i.imgur.com/wjKfVKX.png" height="80%" width="80%" alt="Section 1 Steps"/>



 <h2>Analyze Malicious Network Traffic:</h2>










<p align="center">
Show one of the deauth packets that you generated between the BSSID and your selected station: <br/>
<img src="https://i.imgur.com/cmimqDJ.png" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the packets related to the four-way handshake:  <br/>
<img src="https://i.imgur.com/SoaaGZ3.png" height="80%" width="80%" alt="Section 1 Steps"/>







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
