<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Post Installation Configuration Setup</h1>
In this walkthrough, I will be demonstrating a couple of examples of system administration work after successfully installing the osTicket ticketing system. This will include configuring roles, creating SLAs, etc.
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuartion Steps</h2>

<p>
</p>
<p>
</p>
</p>
<p>
To configure roles, go to the Admin panel-> Agents-> Roles. We will create a Supreme Admin. 
Click on "Add new role", then enter the name of the new role. You can also modify any specific role permissions. Since we are creating a Supreme Admin, they will be given all permissions. Roles are used to determine an agent's permissions so that not all agents will have unlimited access. After following the steps correctly, your screen should look like the screen below. 
</p>
<img src="https://github.com/user-attachments/assets/c224d60a-0894-4404-8c18-03089f16cf4b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
Next, create a new department. Select the "Departments" button in the agents tab. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. We will be creating the "System Administrators" department. This is where the Supreme Admins will be designated. Other specific settings, such as SLAs, managers, and other email settings, can also be created in the departments tab. 
</p>
<br />
<p>
<img src="https://github.com/user-attachments/assets/2cfddda4-9a72-4c2b-a8d2-87aefa148564" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/4faa7eeb-9d04-4676-9a28-b1e0a4a6faaf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department, we will set up a new team. Teams allow you to pull agents from different departments. To set up a team, go to Agents->Teams. A Level I support team has been created by default. In this example, we will create a Level II Support Team. Here, I created an "Online Banking" Team.
</p>
<br />
<p>
<img src="https://github.com/user-attachments/assets/66df49f1-8222-47cf-9e8f-f5facb6bc142" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/05eb6665-ea5d-49e3-9521-9d50edb407ce" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
<br />
</p>
<p>
Next, we will create Agents. Agents are the employees of the helpdesk who will work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Permissions, Access, & Teams are to be assigned in the Agents tab. Agents can be given access to other departments other than their own and can also have different roles depending on which department they're in. 
</p>
<br />
<img src="https://github.com/user-attachments/assets/ba12766f-0515-4b4b-82e6-0704a8a0624f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/b3eecbac-be23-4128-8ce7-12db4eb0f364" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/4b88bcf5-22bb-4a92-ba2a-9e5e18240502" height="80%" width="80%" alt="Disk Sanitization Steps"/>
"/>
</p>
<p>
Users are customers who create tickets when they are having issues. To create a user, navigate to the Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<img src="https://github.com/user-attachments/assets/c0c3f8a2-ddc6-4300-913c-7f005be2676e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by navigating to Admin Panel->Manage->SLA Plans. Each SLA has a schedule. Within these schedules, there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<img src="https://github.com/user-attachments/assets/44134158-903a-407d-93da-a093f92c7a18" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/7bc7548f-01e5-4eff-93bd-271272f3c86f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/6084bd1b-b964-4549-9843-5d6d286f8d05" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics help users categorize their tickets. In the example below, we have made a help topic for "Business Critical Outage", along with a couple of other help topics that could be realistically used. 
</p>
<br />
<img src="https://github.com/user-attachments/assets/aa85d914-7b62-412f-90bb-a7a8fee911be" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/a726de7b-1bbe-43a1-a00f-14987e5ded19" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/d775fc2b-86f2-423b-9c15-e6d5f87e944c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
