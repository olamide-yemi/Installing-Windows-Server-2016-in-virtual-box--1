`# Installing-Windows-Server-2016-on-virtual-box-

<h1>Step 1 : Download Windows Server 2016 ISO</h1>
<a href="https://www.microsoft.com/en-us/evalcenter/download-windows-server-2016">Click here</a> to visit the Official Microsoft site and download Windows Server 2016 ISO 60-bit edition and start the download.
<img src="Folder/stp-1-download-wn-server-2016-iso.PNG" height='200' weidth='300'>

<h1>Step 2: Create a New Virtual Machine</h1>
If you haven’t downloaded and installed virtual box, I have created a guide here  on how to go about it. Open Virtual-box and click on ‘New’ to create a new virtual machine.
<img src="Folder/create-new-vm.PNG">

<h2>Name your machine:</h2>
You are at liberty to call it ‘windows server 2016 ’ and it should automatically change the version to windows 2016 64-bit, so make sure that's highlighted if it didn't automatically do it.
<img src="Folder/version-windows-2016(64-bit).PNG">


<h2>Create a Virtual Hard-disk:</h2>
Recommended to have at least 2GB of Base Memory. You could increase if your system has more resources.
<img src="Folder/atleast-2-gb.PNG">

Cycle through and complete by clicking Finish to create your virtual machine.
<br>

<img src="Folder/finish.PNG">




<h2>Configure VM settings:</h2>
Next go to the Virtual Machine ‘settings’ go to the storage tab, empty disk, locating where you downloaded server 2016 ISO and get it inserted. Then click OK.
<img src="Folder/iso-image.PNG">
<img src="Folder/iso-image-insert.PNG">
<img src="Folder/iso-image-insert-ok.PNG">







<h1>Step 3: Start up the virtual machine</h1>
Click 'Start' to start the virtual machine, or rather start installing the server.



<h2>Setting Up Windows Server 2016:</h2>
It loads a blue boot screen then the setup screen
Pick the language, time and keyboard formats as you need, hit next then hit install now
<img src="Folder/install-next.PNG">
<img src="Folder/install-now.PNG">





It will ask which version to pick. Pick the ones with desktop experience, choose the server 2016 standard with desktop experience and hit next 

<img src="Folder/dsktp-exprience.PNG">

Agree with the license terms, hit next

<img src="Folder/accept-license.PNG">

Type of install, choose custom

<img src="Folder/custom.PNG">

Make sure the drive is selected, hit next

<img src="Folder/driver-select-next.PNG">

It will go through the install and when done, let it restart. Click nothing as it boots-up into the setup, let it finish
<img src="Folder/finish-installing-windows-2.PNG">
<img src="Folder/finish-installing-windows-restart.PNG">

Set up password for the administrator account. 
<img src="Folder/setup-password-finish.PNG">
>input>keyboard>insert ctrl, alt, delete to unlock
<img src="Folder/press-ctrl-alt-delete-to-unlock.PNG" width="500" height="300">
<img src="Folder/Screenshot (7179).png">

Enter the password as it logs in the account for the first time
<img src="Folder/password.PNG">

Then finally the desktop will load up
<img src="Folder/finish-finally.PNG">




