# Active-Directory-Home-Lab-Project
# Basic Home Lab Running Active Directory

The Goal of this project was to demonstrate an understanding of Active directory while setting up a virtual environment with 1000 users. This is similiar to something that would be established at an organization or school.

This repository contains steps on how I set up a basic home lab running Active Directory following a tutorial by [Josh Madakor](https://www.youtube.com/@JoshMadakor)

## Diagram
![Diagram](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/1.Network%20Infrastructure.png)

## Download and install Oracle VirtualBox from the official website.
[Oracle Virtual Box](https://www.virtualbox.org/)

## Download the Windows 10 and Server 2019 ISO files.
[Windows 10 iso](https://www.microsoft.com/en-us/software-download/windows10ISO)
[Windows Server 2019](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019)


## Create a new virtual machine by clicking on "New" in VirtualBox, naming it "Domain Controller," and selecting the "Windows Server 2019" ISO file as the boot media.

![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/2.%20Creater%20sever%20VM.png)


##  Configure the virtual machine by giving it two network adapters: one for connecting to the internet and the other for the private network.

![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/3.%20Network%20Settings%201.png)

![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/4.%20Network%20Settings%202.png)

##  Install Server 2019 on the virtual machine then configure intranet settings and configure server roles eg. AD, DHCP, Remote Access
![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/5.%20Ensure%20Intranet%20network%20is%20properly%20configed.png)

![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/6.%20Ensure%20proper%20set%20up%20of%20SEVER%20roles.png)




##  Run the PowerShell script to create 1000 users in Active Directory.

[Power Shell script for creating users](https://github.com/joshmadakor1/AD_PS)

##  Make a new virtual machine named "Client1" and install Windows 10 iso on it.

![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/7.%20Create%20CLient%201%20with%20windows%2010.png)


##  Connect the client machine to the private network test with cmd and then connect to domain.
![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/8.%20Set%20up%20client%20and%20ensure%20testing.png)

![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/9.%20Join%20client%20to%20domain.png)
##  Log into the client machine with a domain account.

![](https://github.com/Malikj10/Active-Directory-Home-Lab-Project/blob/main/10%20Log%20in.png)

