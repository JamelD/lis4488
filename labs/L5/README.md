# LIS 4488 - Network Administration

## Jamel Douglas

### Lab 5: Join Computers to Domains

#### Objectives
The objective of the lab is to familiarize you with various Windows NT modes (Standalone Server,Member Server, and Domain Controller), what it means to be a member of a Domain, and the Windows Server 2019 management environment. This lab continues with the management basic Active Directory (AD) objects, as well as the management of Active Directory users and groups.

#### Tasks
- Connect to the CCI Virtual Lab environment
- Select your Microsoft Windows 10 virtual workstation
- Observe Changes to Server Joined to Domain in Previous Lab
- Join Workstation to Domain
- Log in to your Windows 10ComputerUsing a Domain Account
- Observe Changes to Workstation Joined to Domain 
- Move Domain-joined Workstation into Team Organizational Unit

#### Deliverables (W/ Responses)
- Deliverable 1: From Action 1, write your name, the number of your team, the name of your partners, and the date. 
> - Jamel Douglas, Team 12
> - 2/11/2021
> - Humzah Mohyuddin, Matthew Lewis, Zachary Bresler
- Deliverable 2: From Action 3, what user do you see as default? What is this user’s context? Is this a local user or a Domain user? 
> Admin Lite, domain user.
- Deliverable 3: From Action 4, what is the name of your computer? To which workgroup does it belong? 
> Lab-Win2019-12; belongs to the domain CCI-LAB-DOM.loc
- Deliverable 4: From Action 4, what do you see? What are the names of any Domain Controllers you see? What Operating System is it running (be specific) and what is its FQDN? 
> DC: CCI-LAB-DC1; Windows Server 2019 Datacenter; CCI-LAB-DC1.CCI-LAB-DOM.loc 
- Deliverable 5: From Action 4, what do you see? How many computers do you see? What do you think the nature of these computers are, e.g. modes? Choose one: What Operating System is it running (be specific) and what is its FQDN? 
> List of computers joined to domain; 17; These are computers that are joined to the domain; Windows Server 2019 Datacenter; Lab-Win2019-12.CCI-LAB-DOM.loc 
- Deliverable 6: From Action 4, what mode do you think that all servers in the Domain Controllers folder are in? What mode do you think that all servers in the Computers folder are in? What Standalone servers do you see in either? 
> Servers in the domain controller folder are in domain controller mode. Computers in the computers folder are in domain member mode. We shouldn't see any standalone servers because they are not joined to the domain.
- Deliverable 7: From Action 5, what is the FQDN of your team server and what is its DC type? What operating system does it presently run? 
> Lab-Win2019-12.CCI-LAB-DOM.loc; workstation or server; Windows Server 2019 Datacenter
- Deliverable 8: From Action 5, what is the Event ID of the event that you chose, when was it logged, and what was the event? 
> 7036; 2/11/2021 4:40:50 PM; Network Setup Service has entered the stopped state
- Deliverable 9: From Action 7, what is the default context into which the workstation is attempting to log you in? Is it a Domain context, or a local one? 
> Domain context
- Deliverable 10: From Action 8, who and what is a member of the local Administrators group? What would user CCI-LAB-DOM\Administrator be allowed to do to your Domain-joined Windows 10 computer? By default, what is local user yourWorkstationName\admin” or yourWorkstationName\Administrator allowed to do on the Domain, and on your team server? 
> admin, helpdesk, Administrator, CCI-LAB-DOM\Domain Admins. Domain admins are local administrators. Local admins cannot even login to the domain or team server because these accounts are only local
- Deliverable 11: From Action 8, could you guess about what time this machine was joined to a Domain? If so, when was it joined? 
> 2/11/2021 5:35:24 PM
- Deliverable 12: From Action 8, what do the last ten log entries tell you? 
> Event viewer error. "Event viewer cannot open the event log or custom view"
- Deliverable 13: From Action 9, what do you see? Do you see your team members’ workstations? What are the names of these workstations? 
> Lab-Win10-12A, Lab-Win10-12B, Lab-Win10-12C
- Deliverable 14: From Action 9, what do you see? What happens? 
> Error, "[Computer] cannot be managed. Verify network path, the computer is available on network, and correct firewall rules"
- Deliverable 15: From Action 10, list all of the entities now in your team’s OU.
> Lab-Win10-12A, Lab-Win10-12B, Lab-Win10-12C, Team Twelve, Jamel Douglas, Matthew Lewis, Humzah Mohyuddin