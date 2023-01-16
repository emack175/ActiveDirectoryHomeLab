<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
In this lab I will be setting up a virtual environment that runs Active Directory and using PowerShell to create about a thousand users in that environment. The purpose of this lab is to demonstrate how businesses, offices, and many other institutions uses Active Directory to monitor users on their system and to maintain control of who has access to which resources.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>DHCP</b>

<h2>Environments Used </h2>

- <b>Oracle Virtual Box</b>
- <b>Server 2019 ISO</b>
- <b>Windows 10 ISO</b>

<h2>Program walk-through:</h2>
<p align="center">
Open up Virtual Box and then create a Domain Controller with a server 2019 ISO. Then create two NICs, one for the internet running NAT and the other for the internal vm network : <br/>
https://imgur.com/j4ykeyC
<br />
<br />
Set up IP Addressing: </h2>
https://imgur.com/jm7KGkU
<br />
<br/>
Install active directory domain services and create domain: </h2>
https://imgur.com/gwkngKB
<br />
<br />
Install RAS/NAS on DC to allow clients to be on private virtual network but still able to access internet through DC: </h2>
https://imgur.com/q5d3ta4
<br />
<br />
Set up DHCP server on DC to allow windows 10 clients to get IP address to browse internet on the private network.
https://imgur.com/baFj6WM
<br />
<br />
Set Up domiain with all users and run powershell script: </h2>
https://imgur.com/7jL4AmU
<br />
<br />
Create Windows 10 Virtual Box: </h2>
https://imgur.com/2zjLE0J
<br />
<br />
Sign with any of the created users!: </h2>
https://imgur.com/4PzLk1R
<br />
<br />
