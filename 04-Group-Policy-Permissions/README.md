# Group Policy, Permissions & Access Management

After users and OUs in Active Directory, I started working with Group Policy to manage settings for my domain.

## Password and Account Lockout Policy

I looked through the password and account lockout policies for my domain. These settings control things like how long a password is good for, password requirements, and how many failed login attempts a user gets before being locked out.

I changed the maximum password age to 90 days and set the account lockout threshold for failed login attempts.

<img width="512" height="306" alt="unnamed" src="https://github.com/user-attachments/assets/1feabd78-0f87-440b-b620-01157a0f33c7" />

My password and account lockout settings in Group Policy.

## Applying and Checking Group Policy

I used 'gpupdate /force' to apply Group Policy changes and `gpresult /r` to check which policies were being applied to the user.

I also tested Group Policy by blocking Task Manager and password changes for Patty, applied it to the HR OU and made sure the restrictions worked on her computer.

<img width="512" height="393" alt="unnamed" src="https://github.com/user-attachments/assets/5fdd6a29-b200-4759-b808-1b742a3de93e" />

Checking Group Policy and the restrictions applied to Patty.

## Shared Folders

I created HR and Personal shared folders on my server to practice giving users access to network folders.

<img width="512" height="244" alt="unnamed" src="https://github.com/user-attachments/assets/81ad8476-d208-41eb-8804-756172aaa0a1" />

My HR and Personal shared folders on the server.

## Security Groups and Folder Permissions

I created HR-Access and Personal-Access security groups and added Patty to both groups. I then set the folder permissions so only the correct security group could access each shared folder.

<img width="450" height="338" alt="image" src="https://github.com/user-attachments/assets/ded39608-0c23-4c89-a17e-7b83919f8afa" /> <img width="484" height="338" alt="image" src="https://github.com/user-attachments/assets/db828e81-1730-4fb1-a35b-2fc32765a632" />

My security groups and shared folder permissions.

## Mapping a Network Drive

I logged in as Patty and mapped the HR shared folder as the 'Z:' drive. I set it to reconnect so the drive would still be there when she signs back in.

<img width="1086" height="590" alt="image" src="https://github.com/user-attachments/assets/c348a6ea-08ad-4d35-8bf4-11539f731023" />

My HR shared folder mapped as the Z: drive.

## Personal User Drive

I set up a personal drive for Patty through her Active Directory profile. When she signed in, her personal folder was created and mapped as the 'P:' drive.

<img width="1146" height="376" alt="image" src="https://github.com/user-attachments/assets/ede3d93e-6bd2-4397-a66f-70e1c21dfe49" />

Patty's personal P: drive mapped on her computer.
