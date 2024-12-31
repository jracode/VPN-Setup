# VPN-Setup
This tutorial outlines the prerequisites and installation 
# Steps 
1. - Locate Local IP
2. - Setting Up VM Using Azure
3. - Locating IP Through VM (France)
4. - Connecting to VPN Through VM
5. - Locating IP Through VPN (Japan)
# Installation
1. - Locate your own personal IP address by going to "www.whatismyipaddress.com" which will be able to show your local IP address. We will use this later as well. See EXAMPLE 1A below.
<img width="1201" alt="Screen Shot 2024-12-31 at 4 19 50 PM" src="https://github.com/user-attachments/assets/e163284e-9868-41b0-a211-0f4d0ae7e758" />
Next we will set up a virtual machine on Azure.


2. - Go to www.portal.azure.com and find Virtual Machines. (Create a free account with $200 if you need to). See Example 2A looking at the Virtual Machine set up page.
Example 2A
<img width="720" alt="Screen Shot 2024-12-31 at 4 57 21 PM" src="https://github.com/user-attachments/assets/5013000d-a272-4dde-b6a8-1c202aff6dca" />

Creating the Virtual Machine on Example 2B the VM as “VM-FranceCentral” and select that for the REGION as well. Ensure the other items are selected as shown in EXAMPLE 2B & 2C.

EXAMPLE 2B

<img width="602" alt="Screen Shot 2024-12-31 at 5 03 28 PM" src="https://github.com/user-attachments/assets/dcd3ea35-d48f-422f-8b17-fa6c1867517d" />

For the Username and Password you can create your custom information, just record it personally.


EXAMPLE 2C

<img width="645" alt="Screen Shot 2024-12-31 at 5 06 59 PM" src="https://github.com/user-attachments/assets/c3022958-0088-4fe9-96c5-071d292af6c5" />

Select the “Networking” tab towards the top of the page and view EXAMPLE 2D inputs to match.


EXAMPLE 2D

<img width="526" alt="Screen Shot 2024-12-31 at 5 09 48 PM" src="https://github.com/user-attachments/assets/51274533-a112-491c-b4f9-bad96f5398bc" />

Then select “Review and Create”, once it passes validation select “Create” at the bottom.


NEXT: At the Virtual Machine we find that the IP to the Virtual Machine is “20.216.176.18”. See EXAMPLE 2E

EXAMPLE 2E


