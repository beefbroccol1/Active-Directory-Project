# Active-Directory-Project
This repo documents setting up a virtual environment utilizing Oracle's VirtualBox with Kali Linux, Windows 10, and Windows Server to practice configuring networks, security tool installions (Splunk), and security testing.

Step 1. Setting up the VMs for Windows 10, Kali Linux, Ubuntu Server, and Window Server
<img width="179" height="228" alt="image" src="https://github.com/user-attachments/assets/f9ae2fba-de1c-452e-bae2-9778ccf10505" />

Step 2a. Create a NAT network for the VM's to communicate to each other.
<img width="287" height="197" alt="image" src="https://github.com/user-attachments/assets/5f85a3a4-8a67-45b0-a654-567c7d6cdbe9" />

Step 2b. Set the virtual machines NAT network
<img width="551" height="265" alt="image" src="https://github.com/user-attachments/assets/acc8d822-fc79-420d-a8cf-517349a07507" />

Step 3. Splunk installion
1. On the Ubuntu server VM I ran the command "sudo apt-get install virtualbox-guest-additions-iso".
2. Reboot the machine.
3. Next ran the command "sudo apt-get install virtualbox-guest-utils".
4. Reboot the machine again.
5. Add the user to group "vboxsf"
   <img width="434" height="81" alt="image" src="https://github.com/user-attachments/assets/92f9b932-1d5e-41df-b4ab-2e3ceb5c5ac0" />
6. Mounted vboxsf group to the share folder
   <img width="1087" height="219" alt="image" src="https://github.com/user-attachments/assets/fb448c54-c7e3-4329-ae78-ebef754aeb1f" />
   VM now has access to host machines shared folder.
7. <img width="1060" height="262" alt="image" src="https://github.com/user-attachments/assets/6d12b42a-8370-443f-acb8-4e508008c9a2" />
    run command "sudo dpkg -i splunk-10.2.2....." to finally install splunk.

Step 4. Opening splunk on target PC
<img width="1372" height="967" alt="image" src="https://github.com/user-attachments/assets/f6433491-baf6-4dec-83d4-9e0c803afead" />

1. Downloading Sysmon and olaf sysmon configuration.
   <img width="538" height="173" alt="image" src="https://github.com/user-attachments/assets/8ff7cd37-d93c-430e-a96a-1093eafd1722" /> <img width="395" height="465" alt="image" src="https://github.com/user-attachments/assets/929e4f5e-5ae5-4f6f-8459-2b864e0cb035" />

2. Installation of Sysmon with config
   <img width="640" height="136" alt="image" src="https://github.com/user-attachments/assets/9549a684-6eff-49d9-aa41-0e5fad2afc9b" />
3. Login to Splunk
   <img width="1005" height="407" alt="image" src="https://github.com/user-attachments/assets/9fd12c6c-d256-4cd6-97ab-3d075c57fb53" />
4. Configure Splunk to receive data
   <img width="1012" height="396" alt="image" src="https://github.com/user-attachments/assets/ed2b0616-5baf-4a49-90ec-3b313244a003" />
   <img width="1001" height="370" alt="image" src="https://github.com/user-attachments/assets/440e92ba-6bc9-4199-a674-9a3659b6183b" />
5. 




   






