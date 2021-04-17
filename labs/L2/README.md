# LIS 4488 - Network Administration

## Jamel Douglas

### Lab 2: Workstation User, Group, NTFS Permission, & Share Exercise

#### Objectives
The objective of the lab is to familiarize you with the Windows 10workstation management environment and introduce you to the creation and management of local users and groups, and of shares and NTFS permissions. 

#### Tasks
- Connect to the CCI Virtual Lab environment
- Select your Microsoft Windows 10 virtual workstation
- Create Folder
- Create local users
- Create local groups
- Add local users to local groups
- Share Folder
- Set share and NTFS Permissions
- Test shares

#### Deliverables (W/ Responses)
- Deliverable 1: From Action 1, write your name, the name of your partner, and the date 
> Jamel Douglas, Partner; 1/21/21
- Deliverable 2: From Action 2, what is the name of your computer? 
> Lab-Win10-12B
- Deliverable 3: From Action 4, what is the name of your partner’s computer? 
> Lab-Win10-12A
- Deliverable 4: From Action 5, does your workstation have IP connectivity with your partner’s workstation? What do you think its IP address is? 
> Ping request timed out. IP [[fe80::4c9a:4d53:895f:b54c%7 ]]
- Deliverable 5: From Action 7, what is the username of the account you created? 
> jdouglas
- Deliverable 6: From Action 7, what is the username of the account you created for your partner? What means did you use to coordinate passwords? Did you do anything special to help ensure that you wouldn’t continue knowing your partner’s password? What was it, if so? 
> Matt_L
- Deliverable 7: From Action 7, what is the username of the account that your partner created for you? 
> Jamel_D
- Deliverable 8: From Action 7, did you do anything special to reduce exposure of this person’s account prior to his or her first day of work? If so, what was it that you did? 
> I selected the checkbox to disable the account when I created
- Deliverable 9: From Action 8, what is the name of the group that you created to place your partner in? 
> Group12
- Deliverable 10: From Action 9, what users do you see as members in the Users group? Do you see any groups as members of the Users group?
> - jdouglas
> - Matt_L
> - jdoe
> - NT AUTHORITY\Authenticated Users (S-1-5-11)
> - NT AUTHORITY\INTERACTIVE  (S-1-5-4)
- Deliverable 11: From Action 9, what was the full context name of the user, i.e. something/somethingelse? 
> LAB-WIN10-12B\Matt_L
- Deliverable 12: From Action 10, what was the full context name of the group, i.e. something/somethingelse? Do you think that context of user or group has any significance? Is user Machine-1\Administrator the same entity as user Machine-15\Administrator? 
> LAB-WIN10-12B\Auditors
- Deliverable 13: From Action 11, which entities are members of the] [Adminstrators] group? Of the entities listed, which of the two cannot be deleted, only renamed? 
> admin, helpdesk, Administrator. 'Administrator' cannot be deleted
- Deliverable 14: From Action 13, what are members of the Authenticated Users and Users groups allowed to do by default?
> - Authenthicated users can modify, read+execute, list, read, and write
> - Users can read+execute, list, and read
- Deliverable 15: From Action 14, which boxes did you select? 
> I only had to select the 'modify' box for Action 14
- Deliverable 16: From Action 15, what is the full name of the Uniform Naming Convention (UNC) for this share? what do you think this share’s UNC would be? (i.e. ``` \\something\something ```) 
> ``` \\LAB-WIN10-12B\MyShare ```
- Deliverable 17: From Action 16, what do you think this share’s UNC would be? (i.e. ``` \\something\something ```) 
> ``` \\LAB-WIN10-12A\MyShare ```
- Deliverable 18: From Action 16, do you see a file in this folder? What is its name? What are its contents? 
> Class Notes text file