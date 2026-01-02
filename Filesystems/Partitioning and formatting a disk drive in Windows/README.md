<h1>Active Directory</h1>


<h2>Description</h2>
How to partition and format a disk drive in Windows. artitions are important because a file system can't function without one. When you acquire a new disk drive, at least one partition is required in order to be able to write files to the file system. Different partitions can then have different file formats, depending on their purpose.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Disk Mangement through Control Panel</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Open Control Panel and navigate to System and Security and click on Administrative Tool: <br/>
<img src="System and Security.png" height="80%" width="80%" alt="System and Security"/>
<br />
<br />
Select Administrative tool and double click on Computer Management:  <br/>
<img src="Administrative tools.png" height="80%" width="80%" alt="Administrative tools"/>   
<br />
<br />
Select Disk Management and bring Disk 1 online: <br/>
<img src="Disk Management.png" height="80%" width="80%" alt="Disk Management"/> <br />
<img src="OFFLINE DISK.png" height="80%" width="80%" alt="OFFLINE DISK"/>
<br />
<br />
Disk 1 is now online:  <br/>
<img src="Computer Management ONLINE DISK.png" height="80%" width="80%" alt="Disk 1 Online"/>
<br />
<br />
Shrink Volume (D:) to create space for new partition(Enter 20,480MB to partition the disk into two partitions of 30GB and 20GB each):  <br/>
<img src="Shrink Volume DISK D.png" height="80%" width="80%" alt="Shrink Volume DISK D"/> <br />
<img src="Volume Shrinked.png" height="80%" width="80%" alt="Shrinked Volume DISK D"/>
<br />
<br />
Creating a new partition with the space left on the storage:  <br/>
<img src="Creating new partition.png" height="80%" width="80%" alt="Creating new partition"/> <br />
<img src="Creating new partition 02.png" height="80%" width="80%" alt="Creating new partition"/> <br />
<img src="NEW partition of storage left.png" height="80%" width="80%" alt="Partition E selection with reamaining storage space"/> <br />
<img src="NEW DRIVE Finished.png" height="80%" width="80%" alt="NEW DRIVE and formatted NTFS Filesystem Successful"/> <br />
<br />
<br />
New volume (Volume E:) successfully created: <br />
<img src="New Volume completed.png" height="80%" width="80%" alt="new volume succesfully created"/> <br />
</p>

<h2>Description</h2>
Formatting a Partition with existing Filesystem(NTFS) with a new Filesystem (FAT32)
<br />

<p align="center">
Formatting Volume E: <br/>
<img src="Formatting new drive E.png" height="80%" width="80%" alt="Formatting Volume E"/>
<br />
<br />
Formatted to new Filesystem(FAT32): <br/>
<img src="Formatted to FAT32.png" height="80%" width="80%" alt="Formatted to FAT32"/> <br />
<img src="Formatted to FAT32 02.png" height="80%" width="80%" alt="Formatted to FAT32 02"/> <br />
<br />
<br />
Volume succesfully formatted to FAT32 Filesystem: <br/>
<img src="NEW Filesystem Successful.png" height="80%" width="80%" alt="NEW Filesystem Successful"/>
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

