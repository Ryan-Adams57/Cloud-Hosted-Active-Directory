# Cloud-Hosted-Active-Directory
is tutorial provides a guide for setting up on-premises Active Directory using Azure Virtual Machines.
Environments and Technologies Used

Microsoft Azure (Virtual Machines/Compute)
Remote Desktop
Active Directory Domain Services
PowerShell
Operating Systems

Windows Server 2022
Windows 10 (21H2)
Deployment and Configuration Steps In this lab, we will deploy two virtual machines within the same virtual network (VNET). One VM will act as the Domain Controller, while the other will serve as the Client machine. The Domain Controller will be assigned a static IP address to provide Active Directory services to the Client machine. The Client machine will be added to the domain and configured to use the Domain Controller as its DNS server.
