# Project Description: Basic Active Directory Setup with Organizational Units and User Management
## Objective: 
To set up a basic Active Directory (AD) infrastructure that organizes users, computers, and resources into a logical structure. This project aims to streamline user and resource management by setting up Organizational Units (OUs) by geographic location, creating user accounts and groups, and establishing basic user support capabilities such as password reset and account unlock functionalities.



## Why Active Directory?
Active Directory (AD) is a directory service for Windows network environments. It is a distributed, hierarchical structure that allows for centralized management of an organization's resources, including users, computers, groups, network devices, file shares, group policies, devices, and trusts. 

<h2>Objective:</h2>

##  Part 1. Setting up an AD domain from scratch
 - Install Windows Server in virtual machine
 -  Promote the server to the domain controller (DC)
 -  Create an AD domain (e.g., <code style="color : aqua">Exmaple.local)</code>
  -  Here is the link: https://github.com/JohnPaulPamintuan/Setting-up-Active-directory

## Part 2. Create Organizational Unit for different departments (e.g., USA, EU / IT, Sale):

  <img src="https://i.imgur.com/VaOHL80.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/MKHQNxU.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/xI2xtmk.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>


## Part 3. Add following groups: Users, Computer and Servers:

  <img src="https://i.imgur.com/j7yZ4Ik.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/VI793hs.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>

## Part 4. Create Groups and Users account within Organizational Unit: 

  <img src="https://i.imgur.com/3B9pVhe.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/IcP0y0k.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/wLn97Uv.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>

 ## Group Scopes: </b>
 - <ins>Universal</ins> : Account from any domain in the same forest Global groups from any domain in the forest. Other Universal groups from any domain in the same forestù
 - <ins>Global</ins>: Accounts from the same domain. Other Global gorups from the same domain.
 - <ins>Domain Local</ins>: Accounts from any domain or any trsuted domain Global groups from any domain or any trusted domain. 

 ## Group types: </b>
 - <ins>Security Groups</ins>: Use to assign permision and user rights to shared resources.
   - *Assign permission (for a shared resources)* : Determines who can access certain resources and level of access (Full access control, read and modify)
   - *Assign user rights*:
     -  <b>Built-in security groups</b>: Domain admins for IT staff (Remote users desktop - users need remote access.)
     -  <b>Custom security groups</b>: Finance and HR department (Access financial apps and data.) 

  <img src="https://i.imgur.com/feNXqWz.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/TaxDjqY.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/PQQgzZc.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/ib7GCWI.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>


## Part 5. Resetting User's Passwords + Unlock: 

  <img src="https://i.imgur.com/wZ7cPZt.png" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/lE5Vj4A.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/8ISlDxn.png" height="70%" width="80%" alt="Disk Sanitization Steps"/>

