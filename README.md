# Cyber-Security-Week-1-Assignment
Cyber Security Lab Setup
# Cybersecurity Testing Lab

## Setup Steps

1. **Install VirtualBox**
   - Install Oracle VirtualBox on the host computer.

3. **Create the Network**
   - Open VirtualBox → **Tools → Network Manager**.
   - Create an **Internal Network** for the lab.
   - Use the same network name for all VMs.

4. **Create Kali Linux VM**
   - Create a Kali Linux virtual machine.
   - Configure its network adapter to the lab's **Internal Network**.

5. **Create Windows VM**
   - Create a Windows virtual machine.
   - Connect its network adapter to the same **Internal Network**.

6. **Create Android VM**
   - Create an Android virtual machine.
   - Connect it to the same **Internal Network**.

7. **Start All VMs**
   - Start Kali Linux, Windows, and Android.
   - Check that each VM has an IP address.

8. **Test Connectivity**
   - Use the `ping` command between the VMs.
   - Verify that Kali, Windows, and Android can communicate with each other.

9. **Lab Ready**
   - The isolated virtual network is ready for safe cybersecurity testing and learning.
