<p align="center">
<img <img width="512" height="321" alt="azure-vm" src="https://github.com/user-attachments/assets/0b27eb59-3a55-42bf-a6d3-7ec116faa741" />
</p>

<h1>Azure Virtual Machine Creation</h1>
This tutorial outlines how to create VM (Virtual Machine) & Using it with a Remote Desktop Connection.<br />


<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<br />

<h2>Getting Started</h2>

  - Head over to the Azure Portal and sign in (create an account and start a subscription if needed).
  - Now head over to the Virtual Machine section (in the search bar type "Virtual Machines") than click "Create" and than "Virtual Machine".

<p>
<img <img width="1233" height="653" alt="Azure_CreateVM" src="https://github.com/user-attachments/assets/3a75fb76-e3fc-4476-9087-9f1de7dc7ba3" />
</p>

<br />

<h2>Settings Configuration</h2>

NOTE: The configuration options below should be adjusted accordingly based on location and use case.

<h3>Basics Tap</h3>

  Subscription

     Select an active subscription.

Resource Group

     Click Create new and enter osTicket, then click OK.

Virtual machine name

     Enter osTicket-vm.

Region

     Enter preferred region to host the VM.

Availability options

     Select No infrastructure redundancy required.

Security type

     Select Trusted launch virtual machines.

Image

     Search for and select Windows 10 Pro, version 22H2 - x64.

VM Architecture

     Select x64.

Size

     Select Standard_D2s_v3 - 2 vcpus, 8 GiB memory.

Username & Password

     Set up a secure username and password.

Licensing

     Check the I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights checkbox.

<p>
<img <img width="574" height="678" alt="Azure_SettingsBasics" src="https://github.com/user-attachments/assets/4334afe0-03e5-4f45-8cf5-1173aa50ee03" 
 />
</p>

<br />

<h3>Networking Tap</h3>

      Select the new virtual network it created.

<p>
<img <img width="807" height="678" alt="Azure_NetworkingSettings" src="https://github.com/user-attachments/assets/ec582073-92d0-429d-b09a-ee8bcc8f27bb" />
</p>

<br />

   Click the Review + Create. Verify that validation has passed. Than, click Create.

<br />

<h2>Accessing the Virtual Machine Remotely</h2>

On Mac: Head over to the App store, download Windows App.

    On Azure Virtual Machine Section, copy the public IPv4 Address of the VM you've created.
    Open Windows App, click the + button on the top right. Than click "Add PC".
    
<p>
<img <img width="1301" height="558" alt="RemoteDeskSetup" src="https://github.com/user-attachments/assets/1a76733b-f69b-4b0a-88ea-ed1bb05b1d56" />
</p>

In the PC name field: Paste the public IPv4 address of the virtual machine you created. Than click, Add.

<p>
<img <img width="631" height="587" alt="RemoteIP" src="https://github.com/user-attachments/assets/430bb1a3-8063-4c02-9c1e-1216f83287db" />
</p>

Enter the username and password that was set up earlier during the creation of the Azure virtual machine.

<p>
<img <img width="708" height="553" alt="RemoteUserName" src="https://github.com/user-attachments/assets/3dcf57fa-fff5-43c4-9d38-d70ca08bccbd" />
</p>

Click Continue if this prompts.

<p>
<img <img width="708" height="553" alt="RemoteCon" src="https://github.com/user-attachments/assets/96197ff7-9a54-4a57-af54-a86b548b4079" />
</p>

You are now connected to the Virtual Machine!

<p>
<img <img width="708" height="553" alt="RemoteWelcome" src="https://github.com/user-attachments/assets/5ede2de2-2609-44fe-9a39-75dd81ca544e" />
</p>

On Windows:
Press Win+R, type in mstsc and then click OK to open the Remote Desktop Connection window.
On Linux: 
Use Remmina or a similar client in substitution of Microsoft Remote Desktop.



    
      
