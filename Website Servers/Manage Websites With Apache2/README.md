<h1>Process Management</h1>


<h2>Description</h2>

Managing web servers is one of the most common tasks done by systems administrators. The web server could be hosting an informational website, a content management system, or even a full-blown e-commerce site. Whatever the content is, it's important to understand how to manage the web server that is being used to serve those pages.
Installation of Apache2, a widely used web server software.  Also, enabling a site that is different from the default and enabling additional features on the server.<br/>
<br />


<h2>Software</h2>

- <b>Apache2</b>


<h2> Objectives </h2>

- <b> Getting familiar with Apache2 </b>

- <b>Configuring Apache2 on Linux </b> 

- <b>Enabling and Disabling websites in Apache2 </b> 


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
