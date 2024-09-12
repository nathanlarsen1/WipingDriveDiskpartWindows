<h1>Wiping Drive using Diskpart with Command Prompt in Windows</h1>


<h2>Project description</h2>
For this project, I acted as a Cybersecurity Analyst on a security team for an organization. One of my job roles involved wiping a USB drive. I chose to use the diskpart command in Windows.<br/><br/>

$\color{red}{Warning:\ This\ is\ for\ education\ purposes\ only.\ Use\ this\ knowledge\ wisely.\ You\ can\ easily}$
$\color{red}{wipe\ drives\ with\ valuable\ information\ with\ this\ information.\ Use\ this\ at\ your\ own\ risk.}$

<h2>Command Prompt</h2>
Open a Command Prompt as an administrator.</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/QnMexuQ.png" height="40%" width="40%" alt="Open the file that contains the allow list"/>
<br />
<br />
</p>

<h2>Diskpart</h2>

In the command prompt, type diskpart and press Enter.</br></br> 

<p align="center">
<img src="https://i.imgur.com/vGlvRmr.png" height="80%" width="80%" alt="Read the file contents"/>
<br />
<br />
</p>

<h2>List Disk</h2>

After dispart opens, type list disk and press Enter.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/OF8HuwC.png" height="60%" width="60%" alt="Convert the string into a list"/>
<br />
<br />
</p>

<h2>List of Disks</h2>

The list of disks will be displayed.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/Bix4Ivp.png" height="60%" width="60%" alt="Iterate through the IP addresses list"/>
<br />
<br />
</p>

<h2>Disk Number</h2>

From the diskpart prompt you must select a disk number. For example, if the target disk was DISK 1 then the proper command would be select disk 1 and press Enter.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/hYY5ore.png" height="40%" width="40%" alt="Remove IP addresses that are on the remove list"/>
<br />
<br />
</p>

<h2>Clean Command</h2>

Then in the command prompt enter clean and press Enter.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/sLpgJFv.png" height="80%" width="80%" alt="Update the file with the revised list of IP addresses"/>
<br />
<br />
</p>

<h2>Dispart Succeeded</h2>

You will know that the wipe succeeded when you see output reads Diskpart succeeded in cleaning the disk.</br></br>

<p align="center">
<img src="https://i.imgur.com/VPiPHkO.png" height="60%" width="60%" alt="Update the file with the revised list of IP addresses"/>
<br />
<br />
</p>

After you are finished you can close the Command Prompt window.</br></br>

<h2>Summary</h2>

In this excerise, I demonstrated the use of diskpart to wipe a drive as a Cybersecurity Analyst. This example displayed how drives can easily be wiped for reuse.


