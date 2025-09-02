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
<img src="https://github.com/user-attachments/assets/5d9e69c8-0c3b-4614-9416-6834ae5c2083" alt="Image 1" width="500" height="500">
<img src="https://github.com/user-attachments/assets/c1ee839b-9f88-4dc4-a8a0-884e5abeac4b" alt="Image 2" width="500" height="500">
<img src="https://github.com/user-attachments/assets/24bb1c53-4290-40c0-817b-594666acbf27" alt="Image 3" width="500" height="500">
<img src="https://github.com/user-attachments/assets/a14bdf06-a8a7-44b6-909b-3b83cfbd0404" alt="Image 4" width="500" height="500">
<img src="https://github.com/user-attachments/assets/047cf4cd-2054-448e-a49f-c539124b3fb1" alt="Image 5" width="500" height="500">
<img src="https://github.com/user-attachments/assets/0427d146-2fd1-4b99-81b3-a5be782893cd" alt="Image 6" width="500" height="500">
<img src="https://github.com/user-attachments/assets/97ebd3d5-d5bb-4ada-9b30-374b5d8d9523" alt="Image 7" width="500" height="500">
<img src="https://github.com/user-attachments/assets/d235e3e7-fa34-4812-be30-40003aa5e429" alt="Image 8" width="500" height="500">
<img src="https://github.com/user-attachments/assets/2eccadf3-47a1-4503-b61a-5d03f0365954" alt="Image 9" width="500" height="500">
<img src="https://github.com/user-attachments/assets/201aa385-1614-41bb-be0e-e3d238025537" alt="Image 10" width="500" height="500">
<img src="https://github.com/user-attachments/assets/0b1d09d2-5640-44fe-8144-e6421db1d241" alt="Image 11" width="500" height="500">
<img src="https://github.com/user-attachments/assets/6e981196-3cff-4a5f-b628-e12ea6baf750" alt="Image 12" width="500" height="500">
<img src="https://github.com/user-attachments/assets/d3d28fb4-6d51-4a0d-af91-fa3b83317331" alt="Image 13" width="500" height="500">
<img src="https://github.com/user-attachments/assets/b3c7acef-d6c9-48a5-aadd-0e50c4a8a2cb" alt="Image 14" width="500" height="500">



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
