<p align="center">
<img src="https://i.imgur.com/kAB3p31.png![image](https://github.com/user-attachments/assets/f2041d5d-0df1-4fdd-af4c-53b74d06289d)">
</p>

<h1>VPN - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation using a VPN.<br />




<h2>Environments and Technologies Used</h2>

- A VPN (Proton VPN)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Steps Included</h2>

- Locate Local IP
- Setting Up VM Using Azure
- Locating IP Through VM
- Connecting to VPN Through VM
- Locating IP Through VPN (Japan)

<h2>Installation Steps</h2>

![Screen Shot 2025-01-02 at 8 05 26 PM](https://github.com/user-attachments/assets/62c0058b-5022-46be-a4f2-b04fe834cb26)

Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE and take note of this in a text file

</p>
<br />

![Screen Shot 2025-01-02 at 7 52 09 PM](https://github.com/user-attachments/assets/f9577ee4-9909-4f63-9040-d07bebbc0837)

![Screen Shot 2025-01-02 at 7 53 10 PM](https://github.com/user-attachments/assets/8af52a50-b0e4-4673-a868-4f96bb324fce)

![Screen Shot 2025-01-02 at 7 53 30 PM](https://github.com/user-attachments/assets/86556f16-ff1b-453c-8432-8019bc50eff4)

Create a new Virtual Machine within Azure. Take note of the username and password that you create as well.
</p>
<br />

![Screen Shot 2025-01-02 at 7 59 20 PM](https://github.com/user-attachments/assets/3ed449c6-6be3-40a8-b308-9c5de924a496)

Add a new PC on your Windows remote desktop and insert the Public IP Address of your VM. You may name it whatever you'd like.
</p>
<br />

![Screen Shot 2025-01-02 at 8 10 30 PM](https://github.com/user-attachments/assets/73f73815-3f88-4ff4-9dc2-84ea1958bb5f)

From within your VM, look up what the IP Address is and take note of it.
<br />

![Screen Shot 2025-01-02 at 8 21 11 PM](https://github.com/user-attachments/assets/21953d73-f967-424a-91e9-f24efd0c72aa)

On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en. Make not of the username/email and password.
<br />

![Screen Shot 2025-01-02 at 8 27 47 PM](https://github.com/user-attachments/assets/13f51cb5-e66e-4efb-8f66-70e5e4ae3825)

Back within your VM, login and download the Proton VPN client.
<br />

![Screen Shot 2025-01-02 at 8 31 32 PM](https://github.com/user-attachments/assets/980df9c7-36f4-4ced-ad2b-ca4a307acf8f)

Login to the VPN (https://account.protonvpn.com/login) and choose a VPN server in yet another country (such as Japan)
<br />

![Screen Shot 2025-01-02 at 8 38 55 PM](https://github.com/user-attachments/assets/16fa85b1-b058-4f2c-93fa-db265784b3e5)

Browse to https://whatismyipaddress.com/  and take note of this.
<br />

Throughout this exercise, we utilized 3 different IP Address from using just your local home internet. Your Home IP Address (USA), your VM IP Address (USA), and your VM VPN IP Address (Japan)

If you no longer need the VM, ensure to remove it from the Asure account for unwanted charges.
