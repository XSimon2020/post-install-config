# post-install-config

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
This demonstration outlines the various configurations that can be used when setting up the open-source help desk ticketing system osTicket after installation.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machine (VM)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- macOS

- Windows 10 VM</b> (21H2)

<h2>List of Prerequisites</h2>

- Completion of [osTicket: Prerequisites and Installation](https://github.com/XSimon2020/osticket-prereqs)

- http://localhost/osTicket/scp/login.php

- http://localhost/osTicket/

<h2>Steps</h2>

<p>
1) Log in to the helpdesk login page.
<img width="1156" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/ff365804-8e17-4687-8f9a-e5a574313faf">
</p>
Copy the link URL: http://localhost/osTicket/scp/login.php and paste it onto Microsoft Edge within the vm to get to your helpdesk login page. Type the username and password you set up previously. 
<p>
<br />

<p>
2) Add team.
<img width="1156" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/c5fe7d4c-201d-4879-a71e-069421f36637">
<img width="1156" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/567a6437-6ac2-41ca-aaca-fafcaa6e9e4d">
</p>
On the "Admin Panel", go to "Teams" within the "Agents" tab to add a new team. Click "Add New Team" then type "Level II Support" for the name of the team within the "Team" tab then click "Create Team".
<p>
<br />

<p>
3) Add agents.
<img width="1156" alt="Screenshot 2024-04-05 at 8 00 15 AM" src="https://github.com/XSimon2020/post-install-config/assets/111246513/8449d792-78ea-43fd-b1ec-8f081b19736d">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/33384238-95b3-42f5-9065-bc3ebcdd5af5">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/3c5cb283-6def-4f5b-9ff3-53341cfe4e84">
<img width="1168" alt="Screenshot 2024-04-05 at 8 38 13 AM" src="https://github.com/XSimon2020/post-install-config/assets/111246513/15125377-ec34-43ba-bee6-534315b07039">
<img width="1168" alt="Screenshot 2024-04-05 at 8 39 44 AM" src="https://github.com/XSimon2020/post-install-config/assets/111246513/1334290b-954b-464f-8cf1-48b1336fd406">
</p>
On the "Admin Panel", go to "Agents" within the "Agents" tab to start adding new agents. Click "Add New Agent" and fill out the information like it is shown in the screenshots. Reapeat this process to add another agent except assign this agent with "Expanded Access" and instead of "All Access" and assign to "Level II Support" instead of "Level I Support". You should have a total of two new agents created.
<p>
<br /> 

<p>
4) Add help topics.
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/5a1d3afd-c61e-49a0-91a9-028671c55b76">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/a82d35fc-ae24-497a-976f-3481bc6a468e">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/f65f9df6-14d5-45dd-8135-1fc54b67f6cb">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/ce79038c-b184-4fd2-a470-f3b6dd717bad">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/1db5d787-8f89-46d0-992e-9a1d55973241">
</p>
On the "Admin Panel", go to "Help Topics" within the "Manage" tab to add help topics. Click "Add New Help Topic" then type out all the help topics as shown in the screenshots tab. Click "Add Topic" for each topic.
<p>
<br />

<p>
5) Add SLA plans.
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/950cc6dc-11d1-4642-8e9f-4d7b2d98aff9">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/4347a947-f026-4b99-afd4-0dc6a63fb339">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/dad21765-6b1b-417a-80f6-a20b54ab0bba">
</p>
On the "Admin Panel", go to "SLA" within the "Manage" tab to add SLA plans. Click "Add New SLA Plan" then type out each plan as shown in the screenshots. Click "Add Plan" for each plan.
<p>
<br />

<p>
6) Add users.
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/23f5bbef-21c5-417e-b9ed-2f71df01c0f2">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/602f1cae-7dbf-4464-9c25-4d62f5c1253b">
<img width="1168" alt="image" src="https://github.com/XSimon2020/post-install-config/assets/111246513/05d1457c-25b9-4405-9f5e-dd784adba55c">
</p>
On the "Agent Panel", go to "User Directory" within the "Users" tab to add users. Click "Add User" then type out each user like how its shown in the screenshots. You should have a total of two users added.
<p>
<br />







