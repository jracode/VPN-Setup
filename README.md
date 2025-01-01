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

<img width="642" alt="Screen Shot 2024-12-31 at 5 22 26 PM" src="https://github.com/user-attachments/assets/1b5bc44a-1f0a-4b12-b2ea-73285fd30bf0" />

STEP 3 – Log Into the VM and Find IP Address

Now that we have set up the Virtual Machine we will connecting to it using the application “Remote Desktop Connection” (EXAMPLE 3A) and input the IP address for the VM that we located in EXAMPLE 2E and then input the set credentials we set when creating the VM (see EXAMPLE 3B). Once logged in, we will open the web browser and again look up www.whatismyipaddress.com (EXAMPLE 3C).


EXAMPLE 3A

<img width="644" alt="Screen Shot 2024-12-31 at 5 27 26 PM" src="https://github.com/user-attachments/assets/695d25da-8888-4268-be4a-64e680ccc4e0" />

EXAMPLE 3B

<img width="647" alt="Screen Shot 2024-12-31 at 5 33 43 PM" src="https://github.com/user-attachments/assets/95e38dca-6a9f-4c93-8660-ea26f9f121cf" />

When we look up the IP address for this VM through www.whatismyipaddress.com we see that this VM is showing the location for France (EXAMPLE 3C).


EXAMPLE 3C

<img width="637" alt="Screen Shot 2024-12-31 at 6 52 17 PM" src="https://github.com/user-attachments/assets/10b8924d-a229-4b52-b512-f6f8a7276b91" />

STEP 4 – CONNECTING TO VPN (Free Version)

Using the local computer go to protonvpn.com and create a free account (if you use the VM then French will display on your browser, so use local computer desktop). Once you are logged into your account, copy the URL from the Proton VPN website 


Once you have logged into your Proton VPN account on the VM, you will select “Downloads” and choose to download the “Windows” version. Once the application Proton VPN is installed we will log in using the credentials we used when setting up a free account on Proton VPN. Then connect to the VPN through the installed app. See EXAMPLE 4B when this steps are completed.

EXAMPLE 4B

<img width="663" alt="Screen Shot 2024-12-31 at 7 00 57 PM" src="https://github.com/user-attachments/assets/736b941c-92bd-432e-b208-33a5c30f99dc" />

On the left hand side of the VPN you can select a country where you want your VPN to be, the image below shows the VPN being connected to an IP in Japan. See EXAMPLE 4C


EXAMPLE 4C

<img width="637" alt="Screen Shot 2024-12-31 at 7 02 31 PM" src="https://github.com/user-attachments/assets/f4e758e2-f01c-40b3-91c1-fb9a156097e8" />
