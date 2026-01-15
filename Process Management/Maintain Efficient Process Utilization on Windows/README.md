h1>Process Management</h1>


<h2>Description</h2>
This project demonstrates practical skills in monitoring and managing system processes on a Windows operating system. The focus is on maintaining efficient process utilization, a core responsibility of an IT Support Specialist and System Administrator.<br/> <br/>

Using a Windows virtual machine, the project involves collecting real-time process information, identifying inefficient or unnecessary processes, and safely terminating them using both graphical and command-line tools. The lab emphasizes understanding how system resources are consumed and how improper process management can impact system performance.<br/>

The project also introduces the use of Windows PowerShell for advanced process control, highlighting the importance of automation and command-line proficiency in modern IT environments.
<br />


<h2>Tools Used</h2>

- <b>Task Manager/ Task Viewer</b>
- <b>PowerShell</b> 


<h2> Objectives </h2>

- <b> Monitor and analyze running processes on a Windows system </b>

- <b>Identify processes that negatively impact system performance </b> 

- <b>Terminate individual processes using Windows PowerShell </b> 

- <b>Terminate multiple processes simultaneously using PowerShell commands </b> 

- <b>Improve overall system efficiency through proper process management </b> 


<h2>Program walk-through:</h2>

<p align="center">
Launch PowerShell with Administrative access: <br/>
<img src="Administrative PowerShell.png" height="80%" width="80%" alt="PowerShell using Administrative permission"><br />
<br />
<br />
List of processes using the [Get-Process] command in PowerShell Command Line Interface:  <br/>
<img src="List of Processes.png" height="80%" width="80%" alt="List of Processes"/>
<br />
<br />
Searching for specific process, "totally_not_malicious": <br/>
<img src="Specific process search.png" height="80%" width="80%" alt="Specific process search"/>
<br />
<br />
Terminating process "totally_not_malicious":  <br/>
<img src="Process terminated.png" height="80%" width="80%" alt="Process terminated"/>
<br />
<br />
Verifying terminating process "totally_not_malicious":  <br/>
<img src="Process verification.png" height="80%" width="80%" alt="Process verification"/>
<br />
<br />
Searching and termination of multiple Processes "explorer" process and all processes with "*razzle*:  <br/>
<img src="Multiple Process termination.png" height="80%" width="80%" alt="Multiple Process termination"/><br/>
<br />
<br />
Verifying if the processes have been sucessfully terminated:  <br/>
<img src="Multiple processes verified.png" height="80%" width="80%" alt="Multiple processes verified"/>
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
