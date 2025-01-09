How to Use Remote Desktop Within Azure VMs
This tutorial will guide you through the process of connecting to an Azure Virtual Machine (VM) using Remote Desktop Protocol (RDP).

Prerequisites
An active Azure subscription
A Windows VM created in Azure
RDP client installed on your local machine

Step 1: Navigate to Your VM in the Azure Portal

Go to the Azure Portal and sign in with your Azure account.
In the left-hand menu, select Virtual machines.
Select the VM you want to connect to from the list.
!Azure Portal VM List

Step 2: Connect to the VM
On the VM's overview page, click the Connect button at the top.
!Connect Button

In the Connect to virtual machine pane, select RDP.
!RDP Option

Ensure the correct IP address and port are selected, then click Download RDP File.
!Download RDP File

Step 3: Open the RDP File
Locate the downloaded RDP file on your local machine and open it.
You may receive a security warning. Click Connect to proceed.
!RDP Security Warning

Step 4: Enter Credentials
Enter the username and password for the VM. These credentials were set when the VM was created.
Click OK to connect.
!Enter Credentials

Step 5: Accept the Certificate
You may receive a certificate warning. Check the box for Don't ask me again for connections to this computer and click Yes.

Step 6: You're Connected!
You should now be connected to your Azure VM via Remote Desktop.
