

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives is to configure:</h2>

- Roles
- Departments
- SLA's
- Teams
- Agents
- Users

<h2>1. Configure Roles</h2>

<p>
<img src="https://i.imgur.com/c3GNPxa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <ol>
    <li>Admin Panel -> Agents -> Roles</li>
    <li>Name: Supreme Admin</li>
    <li>Assign everything</li>
    <li>Save changes</li>
  </ol>
</p>
<br />

<h2>2. Configure Departments </h2>

<p>
<img src="https://i.imgur.com/DAm5NVo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <ol>
    <li>Admin Panel -> Agents -> Departments</li>
    <li>Create a New Department</li>
    <li>Name: System Administrators</li>
  </ol>
</p>
<br />



<h2>3. Configure Teams </h2>

<p>
<img src="https://i.imgur.com/2GSJNNI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <ol>
    <li>Admin Panel -> Agents -> Teams</li>
    <li>Level I Support</li>
    <li>Add a new team.</li>
    <li>Name: Level II Support</li>
  </ol>
</p>
<br />



<h2>4. Allow anyone to create tickets. </h2>

<p>
<img src="https://i.imgur.com/Yg2QkCe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <ol>
    <li>Admin Panel -> Settings -> User Settings</li>
    <li>Registration Required: Require registration and login to create tickets</li>
   </ol>
 </p>
<br />



<h2>5. Configure Agents (workers)</h2>

<p>
<img src="https://i.imgur.com/71VDmdo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <ol>
    <li>Admin Panel -> Agents -> Add New</li>
    <li>Add: Jane Doe</li>
    <li>Add: John Doe</li>
    <li>Set Username, email, and password for both.</li>
    <li>Add both agents in a specific Department and Team</li>
    <li>When finished, click "create".</li>
  </ol>
</p>
<br />



<h2>6. Configure Users (customers)</h2>
<p>
<img src="https://i.imgur.com/wGXyBcc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<ol>
    <li>Agent Panel -> Users -> Add New</li>
    <li>Add: Karen</li>
    <li>Add: Ken</li>
  </ol>
</p>
<br />



<h2>7. Configure SLA's</h2>
<p>
<img src="https://i.imgur.com/0PVyvcx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <ol>
    <li>Admin Panel -> Manage -> SLA</li>
    <li>Add new SLA Plan</li>
    <li>Sev-A (1 hour, 24/7)</li>
    <li>Sev-B (4 hours, 24/7)</li>
    <li>Sev-C (8 hours, business hours)</li>
  </ol>
</p>
<br />



<h2>9. Configure Help Topics </h2>

<p>
<img src="https://i.imgur.com/ltqaLPS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <ol>
    <li>Admin Panel -> Manage -> Help Topics</li>
    <li>Add new Help Topics -></li>
    <li>Business Critical Outage</li>
    <li>Personal Computer Issues</li>
    <li>Equipment Request</li>
    <li>Password Reset</li>
 </ol>
</p>
<br />
