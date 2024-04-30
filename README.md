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

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow any to creat tickets
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

 - Configure Roles
   
   -Go to Admin Panal-> Agents-> Roles

   .Roles are permissions giving to agents per department that they have accsess to. Every role has a set of permission that can be checked or unchecked for the department they have accsess to. You can create an unlimited amount of roles for agents for various departments.
   
   
   
<img src="https://i.imgur.com/FSmP19H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
   
  -  Configure Departments
    
     -Go to Admin Panel->Agents->Departments
     
     Departments are division within a organization or buisiness. Tickect are routed through departments. Each department can have its on set of settings. below we created a system administrators department.



<img src="https://i.imgur.com/nUDbqzS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<img src="https://i.imgur.com/nwCgpQW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>


  - Configure Teams

    -Go to Admin Panel->Agents->Teams

     Teams are a group of agents pulled together to handle specifc issues or tickects. The teams can be made up of agents from diffrent departments

    

</p>
<br />

<p>
<img src="https://i.imgur.com/v0GLxPS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Allow any to make a tickect

  -Admin Panal->Settings->User Settings

  Go down to the registration method and make sure its public

  <img src="https://i.imgur.com/fkETRQm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Configure Agents

    -Admin Panel-.Users->Add New

    Agents are those who are given accsess to the help desk to resolve or respond to tickects. Agents need to be assigned to a department and given a role. Agents can be assigned to multiple departments with each department assigning them a diffrent role.

  <img src="https://i.imgur.com/cSraWIj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- Configure Users (customers)
      
  -Agent Panel->Users->Add New

Users are those who make and log into accounts to create or check the status of a tickets they create. Users are identified by the emails they use to create their accounts. Tickets can be searched by searching specific usernames.

  <img src="https://i.imgur.com/133MSQ8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



- Configure SLA

  -Admin Panel->Manage->SLA
      
      
 SLA Plans or Service Level Agreements are set by the system administrators and they give the amount of time a ticket is expected to be solved by. Some agents may have accses to change or correct the SLA of a ticket after its been submitted by a user.

 
  <img src="https://i.imgur.com/srliipo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 -  Configure help topics

    -Admin Panel->Manage->Help Topics

    Help topics determine what department a ticket will be routed to and which agents will have accsess to the tickect. A help topic can also determine the SLA of a tickect.

    
  <img src="https://i.imgur.com/ggqc3B2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  






<p>

</p>
<br />
