<h1>Software packaging and file archiving on Windows</h1>


<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
In this lab, you learned how to install and remove software in the Windows GUI and CLI, and work with zipped files. You installed a text editor, called Sublime Text, and extracted/unextracted .tar files. You also used Windows Powershell to install and uninstall programs on Windows. 
<br/>
<br />

This exemplar is a walk-through of the previous Qwiklab activity, including detailed instructions and solutions. You may use this exemplar if you were unable to complete the lab and/or you need extra guidance in competing lab tasks. You may also refer to this exemplar to prepare for the graded quiz in this module.
<br />
<br />
<h2>Scenario</h2>
You have a bunch of tasks for this lab. First, you'll install and remove software using the Windows graphical user-interface (GUI). Second, you'll remove and install software using the Windows Command Line Interface (CLI), known as Powershell. Third, you'll extract and compress files into a .zip archive in the GUI and CLI.

Install Sublime Text using Windows GUI

Extract files using 7-Zip and Powershell

Install VLC using Windows Powershell

Uninstall GIMP using Windows Powershell

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Installing and uninstalling software using Windows GUI:</h2>

<p align="center">
Installing Sublime Text: </br>
<img src="Installing Sublime Text.png" height="80%" width="80%" alt="Installing Sublime Text"><br />
<img src="Installing Sublime Text(02)" height="80%" width="80%" alt="Installing Sublime Text"><br />
<br />
First, you'll install the Sublime Text editor. Using Google Chrome, visit 
https://www.sublimetext.com to download the latest version of Sublime Text. Once you have downloaded the file, open your Downloads folder under C:\Users\qwiklabs\Downloads. 
You should see the installer, called sublime_text_build_4126_x64_setup.exe. Double click the executable and the process should begin.<br/>
<b>sudo dpkg -i /home/qwiklab/downloads/sublime-text_build-3211_amd64.deb  </b>
<br />
<br /> 
<br />
Sublime Text Successfully Installed: <br/>
<img src="Successfully installed Sublime Text.png" height="80%" width="80%" alt="Successfully installed Sublime Text"> <br />
Now, click on the Install button. When the installation is finished, click the Search icon in the bottom-left of the taskbar, 
and start typing “Sublime Text” to search (as shown below).
<br />
<br />
<br />
Extracting using 7-Zip: <br/>
<img src="Extracting file.png" height="80%" width="80%" alt="Extracting file using 7Zip"/><br/>
<img src="Extracted files.png" height="80%" width="80%" alt="Extracted files result"/>
<br />
<br />
<br />
Compressing and archiving a file:  <br/>
<img src="Files to compress.png" height="80%" width="80%" alt="Files to compress"/><br />
Now you'll perform the other half of the process, bundling multiple files into a .zip archive. 
Navigate to C:\Users\Qwiklab\Documents and find the three files named, Earth, Mercury, and Venus
<br />
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
</br>
</br>
<img width="1022" height="366" alt="OBERZ" src="https://github.com/user-attachments/assets/53bba908-5c18-49bf-81ed-de16c411368e" />
</br>
</br>
<img src="OBERZ.png" alt="Italian Trulli">
