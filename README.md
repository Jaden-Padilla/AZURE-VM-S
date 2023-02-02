# AZURE-VM
I will be showing users how to create an Azure Virtual Machine, in a easy to follow step by step guide. 
<p align="center">
<img src="https://i.imgur.com/0JqzG9w.png" alt="osTicket logo"/>
</p>


A virtual machine, also known as a "VM," offers the advantage of a virtual platform without the need to purchase and maintain physical hardware. Azure VM is a cost-effective solution that allows you to run additional virtual machines as needed and shut them down when not in use. Azure Virtual Machines have various use cases, such as hosting cloud applications, extending a data center, and facilitating development. For example, you can use an Azure Virtual Machine to create a specific configuration for writing code or testing applications.




<h1>Azure Virtual Machine. - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the Azure Virtual Machine.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro </b> (Version 21H2)

<h2>List of Prerequisites</h2>

- Active and running account with Microsoft Azure- If account has not already been made you can create a free acccount with 200$ worth of credits.

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/QjuBv2n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Navigate to portal.azure.com, Once you're signed into your Azure account with your free subscription, navigate to the "Resource Groups" tab and create a Resource Group. 
</p>
<br />

<p>
<img src="https://i.imgur.com/OxKYmjn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Select your active subscription, and name your Resource Group-NOTE it can be named anything. The region you place your Resource Group in will have to match with the region where you place your VM in, so take note of it. 

</p>
<br />

<p>
<img src="https://i.imgur.com/Sjyv2JQ.png**" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. After Reviewing & creating your RG you’ll now be able to deploy it. Take note of your Location.

</p>
<br />
<p>
<img src="https://i.imgur.com/COWvQ76.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Navigate to either the top search bar, or “Recent Services” where you will find “Virtual Machines”, both will take you tothe Virtual Machine creation page.

</p>
<br />
<p>
<img src="https://i.imgur.com/s3U0HSL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Navigate to either the top left corner of the screen or the bottom of the middle screen and create your VM, both will yield the same options.

</p>
<br />
<p>
<img src="https://i.imgur.com/Z75UIq5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Before you’ve created your Virtual Machine specifications on what, how, and where you want your VM to run will be displayed to you. Depending on your project specifications you will find all that you need  to fulfill those certain specifications here. Other than that now you choose your active free subscription, along with the Resource Group we just previously made. Name your Virtual Machine, and for Region place your VM in the same region the Resource Group was made. 

</p>
<br />
<p>
<img src="https://i.imgur.com/gJTstCv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Select which image or Operating System you would like your VM to be deployed in, for this test we will select “Windows 10 Pro, Version 21H2”. Scrolling down you will find the “Size” section where you can choose the size of the virtual CPU’s, GiB's, as well as the monthly costs that best suite your project.

</p>
<br />
<p>
<img src="https://i.imgur.com/JYjlDNe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. After confirming and checking both of the check boxes you are ready to deploy your virtual machine where you can now use it as a wide array of tasks. Be sure to delete your Resource Group after you're done which will also subsequently delete the Virtual Machine associated with it, so you do not waste any uneccesary money. 
</p>
<br />


Remote access to your Virtual Machine 

1. Search for "Virtual Machines" in the search bar or find it under the "Azure Services" tab
2. Select the name of your VM to access the overview page, which displays information about your VM, including a public IP address and a private IP address
3. Copy or note down the public IP address
4. If using Windows, open the start menu and search for "Remote Desktop"
5. Enter the public IP address into the remote desktop screen, along with the username and password used to create the VM
6. If a warning message appears, ignore it and click "Yes"
7. The virtual machine should open on the screen and start loading
8. Enter the username and password when prompted to access the virtual machine



