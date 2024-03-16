<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create an Azure Virtual Machine Windows 10 with at least 2 vCPUS
- Install/Enable IIS in windows with CGI and Common HTTP Features
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

![image](https://github.com/reecepadilla/osticket-prereqs/assets/163461509/4707bfd6-1854-4caf-b8b3-b1d366c88034)


<p>

</p>
<p>
  To start off, you need to have a Microsoft Azure account in order to create the Windows 10 virtual machine(vm). Once your account is created go into the upper search bar and lookup "Virtual Machine". Create a new virtual machine and resource group. Make sure to select Windows 10 and a size of at least 2 vCPUS as shown in the image above. Next create a username and password that you will remember. Next click create. Once created, use your personal computer to open remote desktop. Login in using your virtual machine's public IP address and username and password that you created.
</p>
<br />

<p>
  
![image](https://github.com/reecepadilla/osticket-prereqs/assets/163461509/e31afec1-d1bd-4d89-90c4-fcacf71e96bf)



</p>
<p>
Once you are logged in to your virtual machine, right click the windows button in the bottom left corner and click "run". Next type "control" and click ok. You will be take to the control panel where you will then click on "Programs". Underneath "programs and features" there should be a "turn Windows features on or off' button that you will click. Scroll down and select "Internet Information Services". Click the plus to the left of it to revel the dropdown. Next click the "World Wide Web Services" dropdown button. Then click the "Application Development Feature" dropdown button. Enable CGI by clicking on the box. Minimize the "Application Development Feature" drodown and select "Common HTTP Features" dropdwon and make sure all boxes are selected. Then click "ok" in the bottom right.
</p>
<br />

<p>
  
![image](https://github.com/reecepadilla/osticket-prereqs/assets/163461509/451ea13f-844a-4510-8ef5-4cc0d62506f7)

</p>
<p>
After changes have been applied, download <a href="https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6">Installation Files</a> and install them on your Windows 10 virtual machine. After you have downloaded and installed all files create a new folder labeled "PHP" on the root of C drive.
</p>
<br />
