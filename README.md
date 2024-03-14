<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS) with CGI and common HTTP features
- Install PHP manager and Rewrite Module
- Install C++ Redistributable
- Install MySQL Database
- Configure permissions and install osTicket

<h2>Installation Steps</h2>
<p>
<img width="346" alt="Capture1" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/d7de077f-d3ad-41e0-803b-956d9fe17678">
<img width="342" alt="Capture2" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/ae6b5a19-709e-4f3c-8845-88a5934109b8">
<img width="642" alt="Capture3" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/b0ccb974-f924-4193-9a49-be30b91208f1">
</p>
<p>
Enabling Internet Information Services (IIS) and activating Common Gateway Interface (CGI) on a Windows-based system through the Control Panel configuration. For verification and testing purposes, we opened the web browser and enter "http://127.0.0.1" in the address bar and IIS welcome page displayed.
</p>
<br />

<p>
<img width="446" alt="Capture4" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/1a281bcf-5367-46c0-b07d-27e9fe986635">
<img width="513" alt="Capture6" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/6e11868b-0a4c-4091-9949-753df76f63ce">
<img width="397" alt="Capture5" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/9af94946-b6a1-4417-92c9-1625c976615e">
</p>
<p>
We installed PHP manager and Rewrite Module. PHP Manager is a tool used to simplify the configuration and management of PHP on Internet Information Services (IIS) web servers. Rewrite Module is commonly used to enhance website functionality, improve search engine optimization (SEO), and create user-friendly URLs. In addition we downloaded PHP.7.3.8 version and unzipped in the PHP folder that we created for this lab. 
</p>
<br />

<p>
<img width="458" alt="Capture7" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/b755c687-ddea-49b6-a856-fdd4e89dc9ff">
</p>
<p>
At this point, programs MySQL and C++ Redistributable were installed. When installing MySQL we configured the credentials to finsish the install process. 
</p>
<br />

<p>
<img width="504" alt="Capture8" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/d3d08a6a-a379-40af-9b53-07f724f3e399">
</p>
<p>
We finished installing all programs needed to support osTicket. Next, we moved to the configuration inside IIS by registering the PHP version and then restarted IIS. 
</p>
<br />

<p>
<img width="612" alt="Capture9" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/f0d66b7a-e8fc-4c11-9590-5e6a6ddf46be">
</p>
<p>
From previous configurations, we were able to install osTicket successfully but some extensions had to be enable in order to continue. 
</p>
<br />

<p>
<img width="547" alt="Capture10" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/e7af66bb-3dc2-4aea-b240-3f417f3912bb">
</p>
<p>
Inside IIS we enabled three PHP extensions to expand the options and features that osTicket offers. 
</p>
<br />

<p>
<img width="618" alt="Capture11" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/deef1cff-bfd3-4d71-8408-aef788af97ba">
</p>
<p>
We continued setting up osTicket basic installation by providing information such as admin username and system settings. 
</p>
<br />

<p>
<img width="517" alt="Capture12" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/1e612af5-90d9-424b-8203-907876b08f6e">
<img width="711" alt="Capture13" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/78d1480b-11c4-496c-ad26-4b1d55e13d60">
</p>
<p>
From the osTicket basic installation page, we had a last section to complete named "Database Settings." In order to continue, we installed HeidiSQL to set up a database and connect to a SQL server. We created a new connection to the database called "osTicket."
</p>
<br />

<p>
<img width="354" alt="Capture14" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/674884cd-82e6-43e9-9fb6-ab407f2948a4">
</p>
<p>
At this point, we had all the informaton needed to complete the database settings. We provided MySQL credentials that were configured in the installation process from previous steps then we provided the name of our SQL database "osTicket."
</p>
<br />

<p>
<img width="456" alt="Capture15" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/faeb2fff-c265-45ab-ad98-b88504f97374">
<img width="748" alt="Capture16" src="https://github.com/gabromerorodriguez/osticket-prereqs/assets/163021104/5c22d130-c279-48b7-8b7e-b2f7111bb807">
</p>
<p>
osTicket was successfully installed and we were able to log in with the user admin credentials.  
</p>
<br />


