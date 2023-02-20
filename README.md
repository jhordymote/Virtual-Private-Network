# Virtual-Private-Network
<p align="center">
<img src="https://i.imgur.com/DtZFcId.jpg" alt="Traffic Examination"/>
</p>

<h1>Setup and Usage Virtual Private Network</h1>
In this part you will see step by step with some configuration how to connect to virtual private network (VPN) and more other details. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Get Ip of your computer
- Get Ip of Azure computer
- Download Proton
- Get Ip of Proton computer

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/XJ7pUSu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
this part will show us by help of Whatismyipaddress.com we get our machine IP adddress of your computer and your location.
</p>
<br />

<p>
<img src="https://i.imgur.com/aq9jCY1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
on this part we will create a virtual machine in Azure as we showed in my first lab which you can find details in the first link of my page, and by connecting we will check if the IP's of both computer remain the same.
</p>
<br />

<p>
<img src="https://i.imgur.com/y1HG08Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
as we can see both IP's are different and location change, this change because firstable it is an another computer inside the physique one and when we made a virtual machine our location/region was different to our actual region that is why the location of our Azure IP indicate Japan.
</p>
<br />

<p>
<img src="https://i.imgur.com/9NhIB9P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As we can verify here, our network is connected to japan server and everything online turn in japanese language.
</p>
<br />

<p>
<img src="https://i.imgur.com/3iJ2Fqw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
inside this we will experiment a new thing, we will download an app call ProtonVPN to create and connect to VPN, we will see if this triangle of connection will give us one of the IP's
</p>
<br />

<p>
<img src="https://i.imgur.com/cGmdto4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
in this part we can see our computer or proton is connected and give us some choice of VPN to connect with, and my choice is with Netherland VPN.
</p>
<br />

<p>
<img src="https://i.imgur.com/N4C0OWs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
we are connect to Netherland's VPN and after checking whatismyipaddress.com website, shows us our computer is in Netherland with different different IPaddress from that country, VPN change your location base of the location choose.
</p>
<br />
