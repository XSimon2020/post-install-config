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
<img width="1168" alt="Screenshot 2024-04-05 at 8 41 13 AM" src="https://github.com/XSimon2020/post-install-config/assets/111246513/6d399883-9b6f-4016-abac-b74026286c34">
<img width="1168" alt="Screenshot 2024-04-05 at 8 42 27 AM" src="https://github.com/XSimon2020/post-install-config/assets/111246513/7e6d406b-d784-4770-8df3-faf69cc8f147">
<img width="1168" alt="Screenshot 2024-04-05 at 8 38 13 AM" src="https://github.com/XSimon2020/post-install-config/assets/111246513/15125377-ec34-43ba-bee6-534315b07039">
<img width="1168" alt="Screenshot 2024-04-05 at 8 39 44 AM" src="https://github.com/XSimon2020/post-install-config/assets/111246513/1334290b-954b-464f-8cf1-48b1336fd406">
</p>
On the "Admin Panel", go to "Agents" within the "Agents" tab to start adding new agents. Click "Add New Agent" and fill out the information like it is shown in the screenshots. Reapeat this process to add another agent except assign this agent with "Expanded Access" and instead of "All Access" and assign to "Level II Support" instead of "Level I Support". You should have a total of two new agents created.
<p>
<br />


