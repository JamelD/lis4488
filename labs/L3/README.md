# LIS 4488 - Network Administration

## Jamel Douglas

### Lab 3: Server Local User, Group, NTFS Permission, & Share Execise

#### Objectives
The objective of the lab is to familiarize you with the Windows Server 2019management environment and introduce you to the creation and management of local users and groups on servers, and of shares and NTFS permissions on servers.

#### Tasks
- Connect to the CCI Virtual Lab environment
- Select your Microsoft Windows 10 virtual workstation
- Confirm Windows 2019 Server Operation
- Create folder
- Create local users and local groups
- Add local users to local groups
- Share folder
- Set NTFS Permissions
- Set share permissions
- Test share
    + Map network drive

#### Deliverables (W/ Responses)
- Deliverable 1: From Action 1, write your name, the number of your team, the name of your partners, and the date. 
> - Jamel Douglas
> - 1/28/2021
> - Team 12
> - Humzah Mohyuddin, Matthew Lewis, Zachary Bresler
- Deliverable 2: From Action 4, what is the name of your team server? Which versions of which operating system is it using? To which workgroup does it belong? 
> Lab-Win2019-12; Windows Server 2019 Datacenter; WORKGROUP
- Deliverable 3: From Action 4, how much RAM is assigned to it? How many processors? 
> 2 GB RAM, 1 Processor with 2 Cores.
- Deliverable 4: From Action 5, does your team’s server have connectivity with the internal DNS server? With the Internet? 
> Yes, able to connect to the local DNS server and the Internet
- Deliverable 5: From Action 5, does your team’s server have a static IP address, or one assigned via DHCP? 
> DHCP: no; Static IP: 192.168.50.220
- Deliverable 6: From Action 7, what is the username of the account you created? For this deliverable, each team member will write down his or her own created username.
> jameld
- Deliverable 7: From Action 8, what is the name of the group that you created to place your team members in? 
> Group12
- Deliverable 8: From Action 9, name two groups other than the ones you just created. What do you think they do? 
> Guests - guest users, Power Users - administrators
- Deliverable 9: From Action 9, what were the full context names of the two users you chose to place in that group, i.e. something/somethingelse? 
> Lab-Win2019-12\Humz_96 , Lab-Win2019-12\jameld
- Deliverable 10: From Action 10, what are some feature tabs that you don’t recall seeing in Windows 10 local users properties? 
> I don't recall anything different
- Deliverable 11: From Action 10, what are the full context names of the users that you placed in the Auditors group? 
> Lab-Win2019-12\MauriceC , Lab-Win2019-12\Lewism
- Deliverable 12: From Action 12, what are members of the Users group allowed to do by default? 
> Users can Read&Execute, List Contents, Read, and Special Permissions.
- Deliverable 13: From Action 13, what happens when you attempt to remove Users from the OurSharefolder’s permissions? 
> It displays an error
- Deliverable 14: From Action 13, which boxes did you select? 
> Modify, Read & Execute, List Contents, Read, Write
- Deliverable 15: From Action 14, which boxes did you select? 
> Read, List Contents
- Deliverable 16: From Action 15, what share permissions did you create for the group you created for your team? 
> Read
- Deliverable 17: From Action 15, what share permissions did you create for the group Auditors? 
> Read
- Deliverable 18: From Action 15, what is the full name of the Uniform Naming Convention (UNC) for this share? 
> \\LAB-WIN2019-12\Our Share"
- Deliverable 19: From Action 17, do you see a file in this folder? What is its name? What is its contents?
> I can connect to the share with my username and password but I receive an error and it doesn't allow me to view any folders or files