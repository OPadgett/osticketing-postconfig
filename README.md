
# osticketing-postconfig
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. Now that we have osTicket successfully installed we will be making general configuration on the platform as an Admin. As we dive in we will view the basic setup and visuals of an Admin under the "Admin Panel" and the basic setup and visuals of a Agent under the "Agent Panel". <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLAs
- Configure Help Topics

<h3>Sign in Portals for Admin and Users</h3>

<img src="https://i.imgur.com/PuYpElv.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/GXtON0E.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Here is a quick visual of both sign in portals for the Admin and User. Note: the visual differences.</p>

<h3>Configure Roles</h3>

<img src="https://i.imgur.com/bMBQ717.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/BS0dYZM.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Once logged in, we will begin configuring by establishing a role named "Supreme Admin," which will let whoever is assigned to this role to do pretty much anything. Make sure you're in the Admin Panel by checking the top right, which should indicate "Agent Panel" (whatever panel you're in reflects the opposite panel as a link to access that panel). Simply create role and fill out. Path: Admin Panel -> Agents -> Roles</p>

<h3>Configure Departments</h3>

<img src="https://i.imgur.com/nJxxxFm.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/PKReGIF.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><p align="center"><img src="https://i.imgur.com/y1c8FDH.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Departments are where you will create and configure the specific departments and also a place where you can add agents to said departments. We are going to add to new department called "System Administrators", to just briefly walk through the setup of a department. Simply leave everything default and create (unless you have adjustments you wish to make). Path: Admin Panel -> Agents -> Departments</p>

<h3>Configure Teams</h3>

<img src="https://i.imgur.com/OPx0SLD.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/6AvHNwL.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Teams are where you'd want to build up a specific team of agents from any department in one group, whether to tackle certain tickets/issues or another means to allocate specific responsibilities to employees outside of a single department. Here we will simply "Add a New Team", name it, fill in any specific configurations (like adding members) and create. Path: Admin Panel -> Agents -> Teams</p>

<h3>Configure Agents</h3>

<img src="https://i.imgur.com/5DoDYax.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/81Cwoib.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Agents are where you will create agent profiles for your agents(workers). From here you can setup their privileges, status, reset password, and assign teams. Simply "Add New Agent", fill in required information, configure, and create Agent. Path: Admin Panel -> Agents -> Add New</p>

<h3>Configure Users</h3>

<img src="https://i.imgur.com/ANez3ef.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Users is where you primarily configure your osTicket customer accounts. This will allow them to submit tickets that will be handled by your Agent. To create a user profile, go to the "Agent Panel" side and choose users. Very similar to setting up an Agent profile except without most configuration options. Create once all needed information has been entered. Path: Agent Panel -> Users -> Add New</p>

<h3>Configure SLAs</h3>

<img src="https://i.imgur.com/9ka9wZA.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/6JMq0Qa.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>SLA is where you want to create SLA plans which will be attached to tickets and departments to identify the level of severity for a tickect and the schedule required to meet the service agreements made to clients(customers). Usually, these will be made based on the companies standards. If needed to create, simply click "add new SLA plan", configure, then create. Path: Admin Panel -> Manage -> SLA</p>

<h3>Configure Help Topics</h3>

<img src="https://i.imgur.com/dcXjGaH.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/1i8DArM.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<p>Help Topics are made to help identify common issues or common ticket types which can help an agent stay organized and be more efficient at prioritization of tickets. To create simply click "add new help topic", configure, and create. Path: Admin Panel -> Manage -> Help Topics</p>


<p align="center"><b>CONGRATULATIONS! Now you know how to add and basic configure most of the functions in osTicket. Well Done!</b></p>
