# windows_server_setup
# What I am Creating
- This is a project of a walkthrough of setting up windows server 2022 using VMWare virtualization
- This will be the initial configuration of a network architecture 
- I will be creating the initial configuration to install the windows server image to a VMWare Virtual Machine
- After the initial configuration I will be setting this server up to become a Domain Controller for an AD DS
- Next I will be installing the DHCP service on the virtual machine and then creating the DNS server for the network
- This is a basic test environment in a normal production environment there would be more isolation so the Domain controller, DHCP server and DNS server would have their own machines.

# What is Needed
- I will be using VMWare Workstation Pro but you can use Oracle Virtual Box or windows Hyper-V for your virtualization software
- Make sure to have to have a Windows Server 2022 ISO image downloaded.  

# Machine Requirements
1. Windows Server machine
- minimum of 1 CPU but at least 2 is recommended 
- 2 GB of RAM
- 32 GB minimum of storage but 40 GB is recommended
- TPM 2.0
- Secure Boot
# Walkthrough
# What I have learned