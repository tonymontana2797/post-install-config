# post-install-config 

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Setup</h1>
This tutorial outlines the post-install configuration and setup of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

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
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
 To configure roles, first go to Admin Panel -> Agents -> Roles.
</p>
<p>
 Then type role title, for this case is Supreme Admin:
</p>
<p>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/d099d93f-eb75-44f8-98fd-823940bcc11b"/> 
</p> 
<p>
  Add Permissions and tasks then add role 
</p> 
<p>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/9cb1a640-4631-4d6d-9983-99d948d0fa26"/>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/e550475a-2979-41a8-b9ce-dcf550debdb5"/> 
</p>
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
 To configure departments go to Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/402814a5-7047-43bc-94e8-87dcc0aa2e7f"/>

</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
 To configure teams, go to Admin Panel -> Agents -> Teams.
</p>
<p>
  Add New Team called Level II Support:
</p>
<p>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/1f493662-f7d9-42db-bc1f-286321664f4c"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
      Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/246046bc-6d5f-4b7e-81c6-6083cf96258e"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
 To configure agents go to Admin Panel -> Agents -> Add New.
</p>
<p>
  Add new agent Jane Doe and John Doe:
</p>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/8da74830-663e-4eb7-a921-40f98dc6a8e3"/> 
  <img src= "https://github.com/ethansevilla/post-install-config/assets/170621372/31e3b925-9a5b-48f0-b5df-ed80ad9d1850"/>

<p>
 
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
 Go to Admin Panel -> Users -> Add New.
</p>
<p>
 Create Daniel User:
</p>
  <img src="![Screenshot 6 (Daniel user)](https://github.com/ethansevilla/post-install-config/assets/170621372/8bbb90a5-4679-4c21-83e3-984dec5b6fdd"/>
<p>
  Repeat the same above for Karen User and any other users if applied.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  To configure SLA go to Admin Panel -> Manage -> SLA.
</p>
<p>
 Create new SLA Plan Sev-A (1 hour, 24/7).
</p>
<p>
 Create new SLA Plan Sev-B (4 hours, 24/7).
</p>
<p>
  Create new SLA Plan Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/3cacd0e9-c072-4d88-9e7f-aee3ed1b892e"/>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/02a14336-a803-4645-b03d-abe3ebccf25a"/>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/b2ff0c27-3979-45a2-8a63-192468b1994f"/>
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  To configure and update Help Topics go to Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/5785168e-102f-4ca4-83af-c689ae11c341"/>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/22307e0e-ef63-4b77-889c-d6b6a3287948"/>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/77db9ab0-d9a3-45aa-9f4f-46486df9e6e6"/>
  <img src="https://github.com/ethansevilla/post-install-config/assets/170621372/af4ce553-3b8e-423e-a36a-503bf5c02040"/>
</p>
<br />
<br />
<p>
  And now we are done configuring the osTicket post install config . I hope this tutorial helped. All that's left is to practice triaging and solving tickets.
</p>
<p>
  This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>
