# Active Directory User Management

After setting up my lab environment, I started working in Active Directory on `Server2019`.

## Active Directory Domain

I installed Active Directory Domain Services on `Server2019` and set up my domain as `hamza12.com`.

<img width="1010" height="760" alt="image" src="https://github.com/user-attachments/assets/eb360ac8-1c2d-41d8-a45b-81d83a4e80e4" />

My `hamza12.com` domain set up on Windows Server 2019.

## Active Directory Users and Computers

I opened Active Directory Users and Computers from Server Manager to start working with the accounts in my domain.

<img width="1024" height="764" alt="image" src="https://github.com/user-attachments/assets/91302d56-1f80-42d7-9890-226c6809ef12" />

Active Directory Users and Computers open on my server.

## Finding Users

I practiced searching for user accounts in Active Directory. I searched the entire directory so I could find the account even if it was stored in a different folder or OU.

<img width="1016" height="768" alt="image" src="https://github.com/user-attachments/assets/b94c2344-a2e0-4539-8ef1-f29baf0ae6b9" />

Searching for a user in Active Directory.

## Creating a Help Desk Account

I created a Help Desk account in Active Directory using the copy method. I copied an existing administrator account so the new account would have the same group memberships.

<img width="1310" height="1034" alt="image" src="https://github.com/user-attachments/assets/1010adc4-2fac-461e-82a4-a042b7543b97" />

My helpdesk account with its copied administrator group memberships in Active Directory.

## Checking User Accounts

I used `net user patty /domain` and Active Directory to check user account information like password details, group memberships, account status, and last logon.

<img width="1688" height="880" alt="image" src="https://github.com/user-attachments/assets/e746a6ef-331d-4d24-a8d5-182e4f7f91c8" />

Checking a user account.

## RSAT Tools

I installed RSAT on my Windows 10 Lab machine so I could access Active Directory Users and Computers without working directly from the server.

<img width="1518" height="1374" alt="image" src="https://github.com/user-attachments/assets/fd0b79dc-27d0-423a-97e9-1bce2858538e" />

RSAT tools installed on my Windows 10 Lab machine for remote Active Directory administration.

## Local and Domain Accounts

I practiced signing into Windows with both local and domain accounts and learned how to tell which one I was using from the sign-in screen.

<img width="1492" height="1142" alt="image" src="https://github.com/user-attachments/assets/f51299ba-b94b-461a-a18a-d12788c8dfe4" />

Signing into my Windows 10 Lab with a domain account.

## Organizing Users

I created HR and IT OUs in Active Directory to organize my users. I added a user to HR and moved my Help Desk account to IT.

<img width="1786" height="858" alt="image" src="https://github.com/user-attachments/assets/dd2a05f7-79cc-4505-84db-bad9ca91ddb3" />

My HR and IT OUs with the users inside.
