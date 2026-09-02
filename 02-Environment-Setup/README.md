# Environment Setup

I built the lab in Oracle VirtualBox on my Windows 11 Pro computer. I have one Windows Server 2019 VM and two Windows 10 VMs. I use these machines throughout the project to practice Active Directory and common help desk tasks.

## Virtual Machines

I created three virtual machines for the lab:

| Machine | Operating System | Purpose |
|---|---|---|
| Server 2019 Lab | Windows Server 2019 | Server used for Active Directory and user management |
| Windows 10 Lab | Windows 10 | User computer for testing and support scenarios |
| Help Desk | Windows 10 | Support computer used to work through help desk tickets and user issues |


### VirtualBox Setup

<img width="658" height="354" alt="image" src="https://github.com/user-attachments/assets/f517fe90-44e7-409f-82ff-251559f2d59d" />

My three lab machines set up in VirtualBox.

## Windows Server 2019

I created my Windows Server 2019 VM in VirtualBox and gave it 6 GB of RAM. I then created the virtual hard drive, attached the Windows Server 2019 ISO, and installed the Desktop Experience version.

### Server Setup

<img width="1094" height="516" alt="image" src="https://github.com/user-attachments/assets/d0246181-2770-4067-9805-3610192e4f1e" />

My Windows Server 2019 VM set up with 6 GB of RAM.

After the installation, I changed the computer name to `Server2019` so the server would be easy to recognize while working with it later in the lab.

### Server Name

<img width="558" height="136" alt="image" src="https://github.com/user-attachments/assets/e454cfe2-eba0-4d6a-92c4-85144edd2426" />

My server renamed to `Server2019`.

## Windows 10 Machines

I set up two Windows 10 VMs named `Windows 10 Lab` and `Help Desk`. One is used as the user's computer, while the other is used for help desk support. I'll use them both to work through help desk tickets, including locked accounts, password resets, disabled accounts, and other user account issues.

### Windows 10 Setup

<img width="1506" height="1250" alt="image" src="https://github.com/user-attachments/assets/2635905e-d833-4faa-8369-bec9402bcbfc" />

My Windows 10 VM set up in VirtualBox.
