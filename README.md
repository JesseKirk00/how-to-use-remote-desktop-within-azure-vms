How to Remote Desktop to Azure VMs
This tutorial will guide you through the process of connecting to an Azure Virtual Machine (VM) using Remote Desktop Protocol (RDP).

Prerequisites :

An active Azure subscription

A Windows VM created in Azure

RDP client installed on your local machine

: Navigate to Your VM in the Azure Portal :

![Screenshot 2025-01-08 201202](https://github.com/user-attachments/assets/33429a58-bb90-4341-b41e-76465d5e3380)

Select the VM you want to connect to from the list.

: Ensure the correct IP address and port are selected, then click copy :

![Screenshot 2025-01-08 202110](https://github.com/user-attachments/assets/32143f75-736a-4ecc-af07-23345548e0db)

Open remote desktop connection (RDP)

: Paste the VM's Public IP and click connect :

![Screenshot 2025-01-08 202233](https://github.com/user-attachments/assets/b6694e5e-a4af-4918-91e9-888402adc25b)


Enter Credentials
Enter the username and password for the VM. (These credentials were set when the VM was created)
Click OK to connect.

Step 5: Accept the Certificate
You may receive a certificate warning. Check the box for Don't ask me again for connections to this computer and click Yes.

Step 6: You're Connected!
You should now be connected to your Azure VM via Remote Desktop.
