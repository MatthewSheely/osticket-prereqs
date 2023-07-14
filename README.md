<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuration</h1>
This tutorial outlines the configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Step 1: Log Into osTicket
- Step 2: Configure Departments
- Step 3: Configure Teams 
- Step 4: Add Agents & Assign Roles
- Step 5: Setup Service Level Agreements
- Step 6: Creating Help Topics

<h2>Installation</h2>
osTicket was installed using a Virtual Machine through(VM) Azure. This tutorial will not be covering installation.
<p></p>
<h2>Configuration Steps(Admin)</h2>
Step 1: Log Into osTicket
<p></p>
To get started you will first, log into your Virtual Machine(VM), using the VM's IP address found in your Azure Portal. Once you have logged into your VM, now log into your osTicket account using a web browser. After logging into your osTicket account select Admin Panel.  
<p></p>
- Log In
<p></p>
<img src="https://i.imgur.com/pzPw9pO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>
- Select Admin Panel (Top Right)
<p></p>
<img src="https://i.imgur.com/cdYxMM9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>
- Select Setting
<p></p>
<img src="https://i.imgur.com/bMFajag.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>

Step 2: Configure Departments
<p>
Admin Panel -> Agents -> Departments
<p></p>
Now that we have successfully logged in, let's set up Departments. This will allow us the ability to categorize incoming tickets and establish the correct access for staff members. 
<p></p>
<img src="https://i.imgur.com/YTBYpG3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>

Step 3: Configure Teams 
<p></p>
Admin Panel -> Agents -> Teams
<p>
Once Departments are created, Teams can be created and assigned to Departments. Each team may have a different level of access. 
<p>  
<img src="https://i.imgur.com/4E3ToDc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>

Step 4: Add Agents & Assign Roles
<p></p>
Admin Panel -> Agents -> Roles
<p>
When creating a new agent's profile or updating an existing agent's profile you will assign them to a department and team that will provide their access ability.
<p></p>  
<img src="https://i.imgur.com/p1foLFl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>
- Add New Agent 
<p></p>
<img src="https://i.imgur.com/5CBlcTT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>
- Select Department
<img src="https://i.imgur.com/YcwoHb6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>
- Confirm Permmissions
<img src="https://i.imgur.com/z3XxoOK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>
- Select Team
<img src="https://i.imgur.com/0LfPszh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p></p>

Step 5: Configure Service Level Agreements (SLA)
<p></p>
Admin Panel -> Manage -> SLA
<p>
<img src="https://i.imgur.com/MxP8iWW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6: Create Help Topics
Admin Panel -> Manage -> Help Topics
<p>
<img src="https://i.imgur.com/RR8tzne.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>





