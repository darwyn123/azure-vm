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
