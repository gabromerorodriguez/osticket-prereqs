<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS) with CGI and common HTTP features.
- Install PHP manager and Rewrite Module.
- Install C++ Redistributable.
- Install MySQL Database.
- Configure permissions and install osTicket. 

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
We finished installing all programs needed to support osTicket. Next, we moved to the configuration inside IIS by registering the PHP
</p>
<br />
