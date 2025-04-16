<p align="center">
    <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
<p>This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.</p>

<h2>Video Demonstration</h2>
<ul>
    <li><a href="https://www.youtube.com/watch?v=mbckqBHjLxM">YouTube: How To Configure osTicket, post-installation</a></li>
</ul>

<h2>Environments and Technologies Used</h2>
<ul>
    <li>Microsoft Azure (Virtual Machines/Compute)</li>
    <li>Remote Desktop</li>
    <li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating Systems Used</h2>
<ul>
    <li>Windows 10 (21H2)</li>
</ul>

<h2>Post-Install Configuration Objectives</h2>
<ul>
    <li>Configure Admin and Agent user roles</li>
    <li>Set up Departments and Teams</li>
    <li>Create Service Level Agreements (SLAs)</li>
    <li>Customize Help Topics and Ticket Filters</li>
    <li>Configure Email Settings and Templates</li>
</ul>

<h2>Configuration Steps</h2>

<p>
    <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="osTicket Admin Panel"/>
</p>
<p>
    After installing osTicket, log in to the Admin Panel using the credentials created during setup. Navigate to the "Manage" section to begin configuring user roles. Define permissions for Admin and Agent accounts to control access levels and capabilities within the system.
</p>
<br/>

<p>
    <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Departments Configuration"/>
</p>
<p>
    Next, go to the "Agents" tab and select "Departments" to create organizational units such as IT, Customer Support, and Sales. Assign agents to their respective departments and set up teams for collaborative ticket handling. This ensures tickets are routed to the appropriate personnel.
</p>
<br/>

<p>
    <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="SLA Configuration"/>
</p>
<p>
    In the "Manage" section, configure Service Level Agreements (SLAs) to define response and resolution times for tickets based on priority levels. For example, set a 1-hour response time for urgent tickets and a 24-hour resolution time for standard requests. Apply these SLAs to departments or specific ticket types as needed.
</p>
<br/>
