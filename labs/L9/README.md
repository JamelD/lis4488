# LIS 4488 - Network Administration

## Jamel Douglas

### Lab 8: Enterprise Information Discovery

#### Objectives
The objective of the lab is to use the tools found in Microsoft Windows 2016 Server to explore the network you have built in the previous labs, gain a general idea as to its structure, and identify weaknesses and strengths, threats and opportunities. You will use this information in subsequent labs, for your Buildout Team projects.

#### Tasks
- Connect to the CCI Virtual Lab environment
- Select your Microsoft Windows 10 virtual workstation.
- Determine General Structural Information for this Enterprise Network
- Determine the Number of Assets and User Accounts in the Enterprise 
- Examine Your Team’s Computers for Effects of Existing Group Policies
- Examine Your Team’s Computers for Configuration

#### Deliverables (W/ Responses)
- Deliverable 1: From Action 1, write your name, the number of your team, the name of your partners, and the date. 
> - Jamel Douglas, Team 12.
> - 3/11/2021
> - Humzah Mohyuddin, Matthew Lewis
- Deliverable 2: From Action 4, what is the name of the enterprise’s root Domain? 
> CCI-LAB-DOM
- Deliverable 3: From Action 4, what is the Domain functional level? What is the Forest functional level? Does the Forest contain the Domain, or does the Domain contain the Forest? 
> Windows Server 2016, Windows Server 2016, Forrest contain the domain.
- Deliverable 4: From Action 4, are there any trust relationships between the Domain under examination, and any other Domains? 
> None
- Deliverable 5: From Action 4, does the tree expand to reveal more Domains? From what you have discovered in this tool, would you describe the general of your lab enterprise network as “flat”, with only one Domain that also happens to be the root Domain, or does there appear to be a hierarchy of parent and child Domains? 
> Nope, This is a flat network.
- Deliverable 6: From Action 5, do you see any Sites existing within this Active Directory structure? If so, what are they? What function does an Active Directory Site perform? 
> Default-First-Site-Name
- Deliverable 7: From Action 6, how many Organizational Unit (OU) containers exist within your Active Directory? Are any OU containers nested within any other OU containers? Would you consider the enterprise OU structure to be “flat”? What is the name of your own team’s Organizational Unit (OU)? 
> 22 OUs. Yes, there are some. structure is flat for the most part. Team-12.
- Deliverable 8: From Action 7, how many computers reside within your OU? How many are servers? How many are workstations? Are any Domain Controllers? What operating systems do they use? 
> 3 Computers: no servers, all workstations. No domain controllers in OU.
- Deliverable 9: From Action 7, how many group objects exist within your OU? Of which Group Type? 
> 2 Groups. Security Groups.
- Deliverable 10: From Action 7, how many user objects exist within your OU? 
> 3 Users
- Deliverable 11: From Action 8, answer the following question: How many user objects exist in your entire enterprise, in all Domains, Sites, and Organizational Units? How many of these user accounts are enabled, and how many user accounts are disabled? 
> 52 Total, 50 Active, 2 Disabled.
- Deliverable 12: From Action 9, name the Group Policy Objects (GPO) that are being enforced against the computers in your Organizational Unit, and their scopes. 
> Install Putty 2. DC=CCI-LAB_DOM,DC=loc
- Deliverable 13: From Action 10, select two of the manageable items above –e.g. an event, a share, a performance metric, a device or disk status, or a service status –and report something about it.
> *Error: Computer Lab-Win10-12A.CCI-LAB-DOM.loc cannot be managed. Verify that the network path is correct, the computer is available on the network, and appropriate firewall rules are enabled on target computer.*