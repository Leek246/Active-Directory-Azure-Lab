# Active-Directory-Azure-Lab
This project documents the step by step process of setting up a basic ** Active Directory 

##Tools & Environment
- **Azure**: used to host a Winsows Server VM
-**Windows Server 2019/2022**: Deployed via Azure 
-**Remote Desktop (RDP)**: Used to connect to the server 
-**Active Directory Domain Services**: 
- **Server Manager**

  **Steps Completed**
##1. Azure Setup 
- Created a **Windows Server VM** in Azure 
- Enabled **RDP Access** and connecetd via remote desktop 

##2. Installed Actiove Directory Domain Services (AD DS)
- Launched **Server Manager**
- Added the **Active Directory Domain Services** role via " Add Roles and Features"
- Chose to create a **New Forest**
- Set domain name

##3. Active Directory Configuration 
- Opened **Active Directory Users and Computers**
- Created custom **Organizational Units**: Users, Groups 
  Test Labs, Workstations etc 

##4. Created Security Groups 
- Example group: IT Admin 
- Type: **Security**
- Scope: **Global**
-Added test users to the group : Malik Clarke 

##5 Created and Shared a Folder 
- Created " Employee PW " folder on server 
- Assigned NTFS permissions to " IT Admin" group 
  
![Screenshot 2025-07-06 121201](https://github.com/user-attachments/assets/03fe1e34-74bf-432a-b67b-1219024![Screenshot 2025-07-06 214104](https://github.com/user-attachments/assets/8cf88b3a-5c83-41c1-a306-d151d2af80e6)
![ss for github](https://github.com/user-attachments/assets/5b225e41-3b2d-42e0-8cb2-9ad5beeb0327)
![ss for github 3](https://github.com/user-attachments/assets/8deb9a96-868d-4e7a-b6d3-72af14926ed4)
![ss forgit hub 4](https://github.com/user-attachments/assets/a1f3ad9d-4981-41f5-981d-39334cb99c32)
![ss for github 5](https://github.com/user-attachments/assets/55835525-f86b-4c4d-b617-f7b12eb8be6d)
186fd)
![Screenshot 2025-07-06 095917](https://github.com/user-attachments/assets/5a5eed81-938f-41e9-b665-c51f7a51b2a5)
![Screenshot 2025-07-06 095634](https://github.com/user-attachments/assets/4e45b44f-da56-48d3-8757-b5f6d29dba1e)
![Screenshot 2025-07-06 093703](https://github.com/user-attachments/assets/e4a2bd54-a909-4953-8dec-112564f78bee)
![Screenshot 2025-07-05 152225](https://github.com/user-attachments/assets/14287347-c2fa-45b9-b6c2-cf3452ccd5dd)
