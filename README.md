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

Step 4.





