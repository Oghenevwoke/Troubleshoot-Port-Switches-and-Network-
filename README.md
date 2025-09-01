# Troubleshoot-Port-Switches-and-Network-


<h2>Description</h2>
This Project shows steps taken to troubleshoot a store register that went offline, this was essentially an rj45 issue. Not only so, but also shows power of collaboration and communication across different stakeholders, support level, proper troubleshooting steps as well as escalation, procurement of new device and returns.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Network Tester</b> 
- <b>Cable  </b>

<h2>Environments Used </h2>

- <b>Switches</b>
- <b>Wall Jack</b>
- Network Cables
- Patch Panel
- Network Rack
- Register (Windows 11)

<h2> Troubleshooting Steps </h2>

First i had read the scope of work to understand the problem, then aslo investigating in the location with an open end question  to analyze and create a thoery whihc assisted to me determine probable culprit( in this case a broken LAN) The LAN is a gray color rj45 connected from station mini CPU to wall jack labelled 9D1. The LAN was broken so swapped with a new one, also from the network rack the rj45 going from the patch panel to the switch ( 9D1 to swb port 28 was switched and replaced).



The workstation had an internet after that was done , but connecting with internal support we had to migrate to port to port 30 on the same switch but lost internet after that, which i think it is pretty normal due to port security protocol on a managed switch.



Connected with diverse remote team member to fix the issues but apparently end of day, the register couldn’t lunch xstore which is the app for transacting. final decision was to order a new HDD for that register while staging can be done remotely for the device. 



Before leaving, I had cleaned my work stataion and educated the manager.
<img src="https://imgur.com/a/q6EqfOD.jpeg"
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
