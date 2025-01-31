# Navagating OS Ticket and OS Ticket Users
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

## Environments and Technologies Used

- Microsoft Azure Virtual Machine
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10 (21H2)

### Basic Instillation Steps

![Screenshot (141)](https://github.com/user-attachments/assets/fc20f480-4001-4510-9988-11976fd0135c)
In this Step, I opened the instillation files to install the database.

![Screenshot (142)](https://github.com/user-attachments/assets/a12b1efb-61d6-4de8-b6d8-86b9bfb98ce4)
In this step, I configured the settings to turn on IIS.

![Screenshot (145)](https://github.com/user-attachments/assets/e078a137-5b46-482b-b3ff-6d9d1656a8f2)
This is showing that I successfully configured the IIS settings.

![Screenshot (146)](https://github.com/user-attachments/assets/ad9a961e-023f-40de-b45c-a143426c8e1b)
This is further instillation steps of the database

![Screenshot (148)](https://github.com/user-attachments/assets/f4604574-921b-4fd3-bb6a-4402cb7c9bb1)
I attempted to change my password here, because I couldn't log in into the osTicket database because I forgot
my password.

![Screenshot (150)](https://github.com/user-attachments/assets/0bf1a09c-4e54-487b-84b4-354c3c1cdff6)
I Used PHP code to change change the current password to a new one, so I could log in

![Screenshot (147)](https://github.com/user-attachments/assets/4dd38bf0-1cbb-408d-8fac-a262e31bbad7)
This shows that I successfully installed the database with all the contents in the database

![Screenshot (149)](https://github.com/user-attachments/assets/80685135-3361-42a1-aca2-75dfe9a9a684)
I successfully changed the password and was able to log into OsTicket database successfully.

### Navagating OsTicket
![Screenshot (40)](https://github.com/user-attachments/assets/2551eba8-9d9c-4873-93de-f0b3201d8deb)
Here I'm navigating OsTicket and adding a Premium Admin role and an All Access role.

![Screenshot (41)](https://github.com/user-attachments/assets/665f79e8-c957-4c96-afcd-689a722fb511)
Here I created a group for System Administrators with currently 0 agents

![Screenshot (42)](https://github.com/user-attachments/assets/c50e82d5-481c-477d-a1f8-7e6fc238a0e9)
In this step I created a new team called Bank Agents and added two new users to go  into the new team

![Screenshot (43)](https://github.com/user-attachments/assets/e965afdc-229f-44ca-8bd0-9802faa994c9)
I successfully created the group along with the two new members being in the group

![Screenshot (44)](https://github.com/user-attachments/assets/4f792efe-f99a-4178-afba-d746b356df7d)
Here I Added two new members to the System Administrators group and also showing that the Bank Agents is apart of the supprt group

![Screenshot (45)](https://github.com/user-attachments/assets/e25352f4-15c6-48dc-bbd2-103fd33079f9)
Here I created a new user  named Karen Basset

![Screenshot (47)](https://github.com/user-attachments/assets/58a7ce4e-1bd1-4006-b985-fb15a9002835)
Here I created two new Help Topics, one being an Equipment reset, and another being a password reset.

![Screenshot (48)](https://github.com/user-attachments/assets/66c4850f-abf3-4516-9bcc-baa17f8fc1c1)
Here I created a mock Ticket and logged into OsTicket as one of the users I created named Judah. I set the Ticket priority as high.

![Screenshot (50)](https://github.com/user-attachments/assets/89740da1-3b09-4809-a84b-fd33f93c773d)
I used my Admin account to assign the ticket to Judah and had Judah transfer the ticket to his support group

![Screenshot (51)](https://github.com/user-attachments/assets/a92cb20d-17c9-4d49-bb0b-c4e2cd4b4054)
Here I am the user Judah and changed the severity of the ticket from sevB to sevA to make sure it gets done immediately, because the whole system is down and I assigned it to the Bank agents group that I created earlier.

![Screenshot (52)](https://github.com/user-attachments/assets/cb55c82e-5f05-4f15-94d4-eff424897a58)
Here it shows that the ticket assigned has been assigned, transfered, resolved and closed.

![Screenshot (53)](https://github.com/user-attachments/assets/688ca55e-e5f4-4fb7-9c69-e9e77f5d9db2)
Here I am the user Judah again and I am solving the ticket given by Karen Basset. I have informed her that I took a look at the charger port of her laptop and that I have ordered the part for her to have it fixed.

![Screenshot (54)](https://github.com/user-attachments/assets/bf77aa1b-5840-4fd5-bb79-521d32b78881)
Here It shows that I have changed the ticket status to resolved.























