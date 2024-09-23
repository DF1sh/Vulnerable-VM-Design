# 💻🔧Vulnerable-VM-Design

The vulnerable virtual machine was created for the Ethical Hacking exam at Sapienza University. Its purpose is to provide a realistic and challenging environment for practicing penetration testing. The VM is based on Ubuntu Server 20.04 LTS 64-bit and runs several services, some of which contain hidden vulnerabilities that can be exploited for local access. Additionally, the VM offers multiple methods for a local user to escalate their privileges and gain root access.

There are three distinct paths ($${\color{green}easy}$$, $${\color{orange}medium}$$, $${\color{red}hard}$$) to achieve local access and escalate privileges to root. Each path requires the attacker to first gain local access and then elevate their privileges to root, providing challenges suitable for different skill levels.

### Download
The VM is available for download from Google Drive at the following link: [Download VM](https://drive.google.com/drive/folders/1M4-EpXrN4JHkClAVfyBYH6qS_WBWMGFe) 

### Setup
  - Import the VM into **VirtualBox** virtualization software.
  - Set the network interface of both the VM and the attacker’s machine to "**NAT Network**", ensuring they are on the same LAN and can communicate with each other. Here’s how to do it:
  - Open VirtualBox and select the VM (and the attacker’s machine if applicable) from the list.
  - Click on Settings in the top menu.
  - Go to the Network tab.
  - On Adapter 1, make sure the adapter is enabled (Enable Network Adapter).
  - In the dropdown next to "Attached to", select "NAT Network".
  - If no NAT Network exists, click the icon next to the dropdown menu to create a new NAT Network. Set a name and confirm.
  - Make sure to repeat these steps for both the vulnerable VM and the attacker’s machine, so **they are connected to the same network**.
  - Have fun hacking!

### VM Design Report 🚑
For a detailed design and exploitation guide, refer to the VM Design Report:
