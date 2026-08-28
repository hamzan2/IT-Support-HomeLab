# Active Directory User Management

After setting up my lab environment, I started working in Active Directory on `Server2019`.

## Active Directory Domain

I installed Active Directory Domain Services on `Server2019` and set up my domain as `hamza12.com`.

[SCREENSHOT]

My `hamza12.com` domain set up on Windows Server 2019.

## Active Directory Users and Computers

I opened Active Directory Users and Computers from Server Manager to start working with the accounts in my domain.

[SCREENSHOT]

Active Directory Users and Computers open on my server.

## Finding Users

I practiced searching for user accounts in Active Directory. I searched the entire directory so I could find the account even if it was stored in a different folder or OU.

[SCREENSHOT]

Searching for a user in Active Directory.

## Creating a Help Desk Account

I created a Help Desk account in Active Directory using the copy method. I copied an existing administrator account so the new account would have the same group memberships.

[SCREENSHOT]

My Help Desk account created in Active Directory.

## Checking User Accounts

I used `net user username /domain` to check domain user account information, including password information, group memberships, and account status.

[SCREENSHOT]

Checking a domain user account from the command line.

## Joining a Computer to the Domain

I configured my Windows 10 lab machine so it could communicate with `Server2019` and joined it to my `hamza12.com` domain.

[SCREENSHOT]

My Windows 10 Lab joined to the `hamza12.com` domain.

## RSAT Tools

I installed RSAT on my Windows 10 Lab machine so I could access Active Directory Users and Computers without working directly from the server.

[SCREENSHOT]

My Windows 10 Lab using Active Directory.

## Local and Domain Accounts

I practiced signing into Windows with both local and domain accounts and learned how to tell which one I was using from the sign-in screen.

[SCREENSHOT]

Signing into my Windows 10 Lab with a domain account.
