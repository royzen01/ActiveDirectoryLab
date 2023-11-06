<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.709 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Sun Nov 05 2023 18:50:41 GMT-0800 (PST)
* Source doc: Controls assessment exemplar
* Tables are currently converted to HTML tables.
----->



# Controls assessment 


## Current assets

Assets managed by the IT Department include: 



* On-premises equipment for in-office business needs  
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Vendor access management
* Data center hosting services  
* Data retention and storage
* Badge readers
* Legacy system maintenance: end-of-life systems that require human monitoring_ _

<table>
  <tr>
   <td colspan="4" >
<strong>Administrative Controls</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Control Name</strong>
   </td>
   <td><strong>Control type and explanation</strong>
   </td>
   <td><strong>Needs to be implemented (X)</strong>
   </td>
   <td><strong>Priority</strong>
   </td>
  </tr>
  <tr>
   <td>Least Privilege
   </td>
   <td>Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Disaster recovery plans
   </td>
   <td>Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Password policies
   </td>
   <td>Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Access control policies
   </td>
   <td>Preventative; increase confidentiality and integrity of data
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Account management policies
   </td>
   <td>Preventative; reduce attack surface and limit overall impact from disgruntled/former employees
   </td>
   <td>X
   </td>
   <td>High/
<p>
Medium
   </td>
  </tr>
  <tr>
   <td>Separation of duties
   </td>
   <td>Preventative; ensure no one has so much access that they can abuse the system for personal gain
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="4" ><strong>Technical Controls</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Control Name</strong>
   </td>
   <td><strong>Control type and explanation</strong>
   </td>
   <td><strong>Needs to be implemented</strong>
<p>
<strong>(X)</strong>
   </td>
   <td><strong>Priority</strong>
   </td>
  </tr>
  <tr>
   <td>Firewall
   </td>
   <td>Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network
   </td>
   <td>NA
   </td>
   <td>NA
   </td>
  </tr>
  <tr>
   <td>Intrusion Detection System (IDS)
   </td>
   <td>Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Encryption
   </td>
   <td>Deterrent; makes confidential information/data more secure (e.g., website payment transactions)
   </td>
   <td>X
   </td>
   <td>High/
<p>
Medium
   </td>
  </tr>
  <tr>
   <td>Backups
   </td>
   <td>Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Password management system
   </td>
   <td>Corrective; password recovery, reset, lock out notifications
   </td>
   <td>X
   </td>
   <td>High/
<p>
Medium
   </td>
  </tr>
  <tr>
   <td>Antivirus (AV) software
   </td>
   <td>Corrective; detect and quarantine known threats
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Manual monitoring, maintenance, and intervention
   </td>
   <td>Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="4" ><strong>Physical Controls</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Control Name</strong>
   </td>
   <td><strong>Control type and explanation</strong>
   </td>
   <td><strong>Needs to be implemented</strong>
<p>
<strong>(X)</strong>
   </td>
   <td><strong>Priority</strong>
   </td>
  </tr>
  <tr>
   <td>Time-controlled safe
   </td>
   <td>Deterrent; reduce attack surface/impact of physical threats
   </td>
   <td>X
   </td>
   <td>Medium/
<p>
Low
   </td>
  </tr>
  <tr>
   <td>Adequate lighting
   </td>
   <td>Deterrent; limit “hiding” places to deter threats
   </td>
   <td>X
   </td>
   <td>Medium/
<p>
Low
   </td>
  </tr>
  <tr>
   <td>Closed-circuit television (CCTV) surveillance
   </td>
   <td>Preventative/detective; can reduce risk of certain events; can be used after event for investigation
   </td>
   <td>X
   </td>
   <td>High/
<p>
Medium
   </td>
  </tr>
  <tr>
   <td>Locking cabinets (for network gear) 
   </td>
   <td>Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear
   </td>
   <td>X
   </td>
   <td>Medium
   </td>
  </tr>
  <tr>
   <td>Signage indicating alarm service provider
   </td>
   <td>Deterrent; makes the likelihood of a successful attack seem low
   </td>
   <td>X
   </td>
   <td>Low
   </td>
  </tr>
  <tr>
   <td>Locks
   </td>
   <td>Preventative; physical and digital assets are more secure
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Fire detection and prevention (fire alarm, sprinkler system, etc.)
   </td>
   <td>Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.
   </td>
   <td>X
   </td>
   <td>Medium/
<p>
Low
   </td>
  </tr>
</table>



<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
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
