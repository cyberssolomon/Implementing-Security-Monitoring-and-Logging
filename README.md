<h1>Implementing Security Monitoring and Logging</h1>

<h2>Tools and Software Used</h2>

- <b>Windows Event Viewer (GPMC)</b> 
- <b>pfSense</b>
- <b>Snort</b> 
- <b>Tripwire (SCT)</b>

 

<h2>Environments Used </h2>

- <b>vWorkstation (Windows: Server 2022)</b> 
- <b>Switch01 (Linux: Debian 11)
- <b>pfSense (FreeBSD:pfSense)</b>



 
<h2>Description</h2>
Project consists of exploring tools and techniques that serve dofferent monitoring and loggin needs: Windows Event Viewer, Intrusion Detection System on a pfSense firewall, and the log files in a Linux environment.
<br />

### Section 1

<h2>Identify Failed Logon Attempts on windows Systems:</h2>








<p align="center">
Show the Security Event Properties dialog box on the vWorkstation: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>

 <h2>Monitor Network Activity with Snort:</h2>







<p align="center">
Show the updated Pass Lists page: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the active Snort status on the LAN interface:  <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the successful ping results:  <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the ICMP alerts in the Snort Active Log:  <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>












 ### Section 2

<h2>Identify Failed Logon Attempts on Linux Systems:</h2>










<p align="center">
Show the edited rsyslog.conf file: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the failed login attempts:  <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>
<br />
<br />
Show the last 10 log messages: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>


 <h2>Monitor File Integrity with Tripwire:</h2>










<p align="center">
Show the Object Summary section for the Tripwire report: <br/>
<img src="" height="80%" width="80%" alt="Section 1 Steps"/>










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
