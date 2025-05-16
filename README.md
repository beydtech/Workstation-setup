# Workstation-setup
**Document the process of setting up a secure and isolated environment for ethical hacking activities. Include the installation and configuration of virtualization software, operating systems, and networking setup.**

1. Choose a Virtualization Software  
To create an isolated environment, use virtualization software. The most popular free options are VirtualBox and VMware Workstation Player. These allow you to run multiple operating systems as virtual machines on your main computer.

2. Install the Virtualization Software  
Download and install the virtualization software from the official website. Follow the installation prompts to complete the setup.

3. Download Ethical Hacking Operating Systems  
For ethical hacking, Kali Linux is the most widely used operating system. Download the ISO file from the official Kali Linux website. You can also use other OS like Parrot Security OS.

4. Create a Virtual Machine  
Open your virtualization software and create a new virtual machine. Assign a name like Kali Linux. Choose Linux as the OS type and Debian or Ubuntu depending on the Kali version. Allocate memory between 2GB to 4GB and create a virtual hard disk of at least 20GB.

5. Install the Operating System
 Start the new virtual machine and load the Kali Linux ISO file. Follow the installation steps which include language selection, disk partitioning, and user creation. Once complete, reboot the VM and Kali Linux will launch.

6. Update the System  
After installation, update Kali to ensure you have the latest tools and patches. Use the following command in the terminal  
sudo apt update && sudo apt upgrade

7. Install Additional Tools  
Depending on your needs, you can install extra tools using the Kali Linux package manager or manually. Tools like Wireshark, Nmap, Metasploit Framework, and Burp Suite are commonly used.

8. Isolate the Virtual Network  
To ensure security, configure the VM to use Host-Only or Internal Networking. This setting allows the virtual machine to communicate only with your host or other VMs but not the internet, which prevents accidental external attacks.

9. Create a Snapshot  
Before conducting any hacking activity, create a snapshot of your virtual machine. This allows you to revert to a clean state if anything goes wrong.

10. Practice in a Safe Lab Environment
Only perform ethical hacking in a lab environment using vulnerable machines like Metasploitable or DVWA. Never test tools or exploits on systems you do not own or do not have permission to test.

