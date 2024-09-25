# Task Eleven - Cloud VM Setup and Interaction

## Objective
This task involves creating a free Virtual Machine (VM) in a cloud environment interacting with it from a Kali Linux environment, and documenting the process.

## Steps

1. **Research and create a free VM:**
   - Researched how to create a free VM on the selected cloud platform.
   - Followed the steps to launch the VM in the cloud account .Here i use Azure account.
   - Documented the steps in a text file.

2. **Retrieve VM IP Address:**
   - After the VM was created, noted down its public IP address from the cloud provider's portal.

3. **Ping the VM from Kali Linux:**
   - Tried pinging the VM from Kali Linux. If it didn’t work initially, appropriate network/security settings in the cloud provider were adjusted to allow ICMP requests (ping).

4. **Login via SSH:**
   - Logged into the VM using SSH from Kali Linux.
         ssh -i <path of private key file> username@IP
   - Ran the command `ip a` to display the VM’s network interfaces.
   - Took a screenshot of the result.

5. **Ping the Public IP from the VM:**
   - Found the public IP of Kali Linux.
   - Tried pinging the public IP from the cloud VM and noted whether it was successful.
   - Took a screenshot of the result.

6. **Explore the VM:**
   - Explored the VM environment to understand its configuration and capabilities.
   - Shut down the VM after completing the exploration.

7. **Terminate the VM:**
   - Finally, destroyed/terminated the VM from the cloud provider’s portal to avoid incurring charges.

## Files in this repository

-  Azure VM.txt: A text file detailing the step-by-step process followed to create, interact with, and terminate the VM.
-  Screenshot of Kali Linux pinging the VM.
-  Screenshot of the `ip a` command output after logging into the VM.
-  Screenshot of the VM pinging the public IP address of Kali Linux.

## Conclusion
This task provided hands-on experience in setting up and interacting with a cloud VM. The steps followed, the interaction through SSH, and the network testing all contributed to understanding cloud networking and VM management.
