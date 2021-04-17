# LIS 4488 - Network Administration

## Jamel Douglas

### Lab 6: Server Administration Tools

#### Objectives


#### Tasks
- Connect to the CCI Virtual Lab environment
- Select your Microsoft Windows 10 virtual workstation.
- Examine the Windows Server 2019 Server Manager Dashboard
- Examine the Windows Server 2019 Event Viewer
- Examine the Windows Server 2019 Performance Monitor 

#### Deliverables (W/ Responses)
- Deliverable 1: From Action 1, write your name, the number of your team, the name of your partners, and the date. 
> - Jamel Douglas, Team 12
> - 2/18/2021
> - Humzah Mohyuddin, Matthew Lewis, Zachary Bresler
- Deliverable 2: From Action 2, what utility are you using to connect to your virtual instance for this lab? Is it Microsoft Remote Desktop, or is it something else?
> RemoteApp Virtual Machine Connection
- Deliverable 3: From Action 3, what resources local to the machine from which you are attempting to create a remote connection (e.g. the lab iMac) would be accessible by the virtual instance by default? 
> *Note: This deliverable was not stated in the lab instructions, professor told us to ignore it*
- Deliverable 4: From Action 4, what is your general impression of the state of your server? Do you see any errors or warnings? If so, what are they? 
> Everything is good, only an alert about promoting the server to domain controller
- Deliverable 5: From Action 4, what are the six general tools visible in this tool? (Hint: Properties should be the first of six.) What set(s) of Tasks stood out in your mind? 
> Properties, Events, Services, Best Practices, Analyzer, Roles and Features.
- Deliverable 6: From Action 5, what is the event’s level, date and time, and Event ID? Looking in the pane below, in very brief summary, what is the nature of this particular Event ID? Briefly, what does that Event ID denote as having occurred? 
> 2/4/2021 2:26:01 PM, Information, 1074. The nature of this is a restart has been initiated. This alert means that the computer is rebooting.
- Deliverable 7: From Action 5, what is the event’s level, date and time, and Event ID? Looking in the pane below, in very brief summary, what is the nature of this particular Event ID? Briefly, what does that Event ID denote as having occurred? 
> 2/18/2021 2:28:54 PM, Information, 8010. The nature of this is the system failed to register DNS PTR records for the network adapter.  Non-Delivery report.
- Deliverable 8: From Action 5, what word(s) did you choose? How effective was this approach in answering the question of when the server was rebooted and by whom? 
> Reboot, no result; Restart, Pulled up results
- Deliverable 9: From Action 5, how many times was your server rebooted? When and by whom? 
> The server has been restarted 6 times, 2 times on 2/4/21, and 4 times on 12/26/2020. Reboot was done by various administrator accounts like NT AUTHORITY\SYSTEM
- Deliverable 10: From Action 5, how many times has user AdminLitelogged into your team server successfully? Unsuccessfully? What tool(s) did you use to answer these questions? 
> The user has logged in on multiple occasions. Found using Event Viewer Windows Security Logs
- Deliverable 11: From Action 6, from the System Summary, how many available Mbytes of memory does your team server presently have? What % Committed Bytes in use? Memory is one of the major server subsystems summarized here: what are the other three? 
> 554,000 MBytes Available, 54.85% Committed MBytes; Network, Disk, Processor
- Deliverable 12: From Action 6, what are three problems with your server that stand out in your mind upon first glance at this report? 
> I only notice high RAM utilization, which is at 75%. There are also warnings that the CPU and Disk Ratings for the system are poor and they may cause performance issues.
- Deliverable 13: From Action 6, what are the Status, Utilization, and Details for your CPU, Network, Disk, and Memory? In your opinion, are these aspects of your server acceptable? 
> CPU, Network, and Disk are Idle. Memory is Normal. I think everything but the memory is acceptable.
- Deliverable 14: From Action 6, what is the peak Interrupts/Sec on your graph after two minutes? Is there any apparent correlation between Network Interface Card (NIC) interrupts per second and total processor utilization? 
> 3 Interrupts/Sec. I didn't see any correlation.

Extra Credit Deliverables [5 points each] 
- Extra Credit Deliverable 1: From Action 5, do you think that Event ID 1074 represents all of the reboots of your team’s Windows 2019Server instance? Why or why not? What other types of reboots might you suspect? 
> I believe 1074 refers to reboots 
- Extra Credit Deliverable 2: From Action 7, answer the following: 
    + What was the duration of the data collection sample you took? 
    + What were the minimum, mean, and maximum Available Mbytes? 
    + What were the minimum, mean, and maximum Available Committed Bytes? 
    + What were the minimum, mean, and maximum Available Pages/Sec? 
    + Which metrics were the spikiest, and which metrics were relatively flat?
> *Note: Did not answer this extra credit question*