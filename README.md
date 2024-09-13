<h1>Wiping a drive using the Diskpart utility in the Windows Command Prompt</h1>


<h2>Project description</h2>
For this project, I acted as a Cybersecurity Analyst on a security team for an organization. One of my job roles involved wiping a USB drive. I chose to use the diskpart command in Windows.<br/><br/>

<b>Warning: This is for educational purposes only.</b> Using this information to wipe drives can permanently erase valuable data. Proceed with extreme caution and at your own risk.<br/><br/>

<h2>Language and Applications</h2>

- <b>Command Prompt</b>
- <b>Diskpart</b></br></br>

<h2>Environments Used </h2>

- <b>Windows 11</b></br></br>

<h2>Search for Command Prompt</h2>
I began by typing "Command Prompt" in the Windows search bar.</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/4tfaGs4.png" height="80%" width="80%" alt="Open the file that contains the allow list"/>
<br />
<br />
</p>

<h2>Right-click and Run as Administrator</h2>
Then I right-clicked on the "Command Prompt" result and selected "Run as administrator."</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/7bCi1DW.png" height="30%" width="30%" alt="Open the file that contains the allow list"/>
<br />
<br />
</p>

<h2>Command Prompt</h2>
The Command Prompt opened.</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/gxojtvH.png" height="80%" width="80%" alt="Open the file that contains the allow list"/>
<br />
<br />
</p>

<h2>Diskpart</h2>

In the command prompt, I typed `diskpart` and pressed Enter.</br></br> 

<p align="center">
<img src="https://i.imgur.com/TGhFnGl.png" height="80%" width="80%" alt="Read the file contents"/>
<br />
<br />
</p>

<h2>List Disk</h2>

After Dispart opened, I typed `list disk` and pressed Enter.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/E8W9BR7.png" height="80%" width="80%" alt="Convert the string into a list"/>
<br />
<br />
</p>

<h2>List of Disks</h2>

A list displayed of all connected disks.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/mxKdhnd.png" height="80%" width="80%" alt="Iterate through the IP addresses list"/>
<br />
<br />
</p>

<h2>Disk Number</h2>

I carefully reviewed the list and identified the disk that I needed to wipe. I typed `select disk 1` and pressed Enter.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/TbdSwtf.png" height="80%" width="80%" alt="Remove IP addresses that are on the remove list"/>
<br />
<br />
</p>

<h2>Clean Command</h2>

Then in the diskpart prompt I entered `clean` and pressed Enter. I made sure that I had the correct disk before proceeding knowing that this process will permanently erase all data on the selected disk. This was done by double-checking the disk number before proceeding, as wiping the wrong disk can have irreversible consequences.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/caTn1Ec.png" height="80%" width="80%" alt="Update the file with the revised list of IP addresses"/>
<br />
<br />
</p>

<h2>Dispart Succeeded</h2>

Once the process was finished, I saw a message indicating that Diskpart succeeded in cleaning the disk.</br></br>

<p align="center">
<img src="https://i.imgur.com/SpBLgP4.png" height="80%" width="80%" alt="Update the file with the revised list of IP addresses"/>
<br />
<br />
</p>

After I was finished, I typed `exit` to leave Diskpart and closed the Command Prompt window.</br></br>

<h2>Summary</h2>

In this excerise, I demonstrated the use of diskpart to wipe a drive as a Cybersecurity Analyst. This example displayed how drives can easily be wiped for reuse.


