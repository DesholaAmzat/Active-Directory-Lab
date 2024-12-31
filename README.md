<h1>Active Directory Home Lab<br/> 

<h2>Description</h2>
In this lab, I was able to create an Active Directory home lab Environment using Oracle Virtual Box. Configuring and running this lab helped develop my understanding of how active directory and Windows networking works, so l'd highly recommend giving this lab a try in order to familiarize yourself with domain and networking environments. Please let me know if you have any questions!


<h2> Languages and Utilities Used</h2>

- PowerShell 
- Oracle VirtualBox


<h2> Environments Used</h2>

- Windows 10 (21H2)
- Windows Server 2019

<h2> Program Walk Through</h2>

<img src="https://i.imgur.com/Re1nd8Z.png" height="88%" width="80%" />
Installed Windows Server 2019.iso on a virtual machine



<img src="https://i.imgur.com/5VwGm0y.png" height="88%" width="80%" />
Used IP Addressing to determine which network interface card was external and facing the internet and which one was internal for devices only on the network
<img src="https://i.imgur.com/9RaEerQ.png" height="88%" width="80%" />
   assigned the VM the role of Domain Controller
<img src="https://i.imgur.com/QjOn79O.png" height="88%" width="80%" />
Created the domain called "AMZAT" and logged into it with admin account
<img src="https://i.imgur.com/gCncqPF.png" height="88%" width="80%" />
Used a powershell script to automate the account creation of over 1000 users in Active Directory
<img src="https://i.imgur.com/iWCBjo0.png" height="88%" width="80%" />
Used another Virtual Machine as a client PC and logged into the AMZAT domain. Pinged Google to confirm network connectivity
