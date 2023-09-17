# Client-Creation-VM-

All IT demonstrations going forward will be performed using this virtual desktop client

<h2>Requirements</h2>

-  <b><a href="https://www.virtualbox.org/wiki/Downloads">Virtual Box</a></b>
-  <b><a href="https://www.microsoft.com/en-us/software-download/windows10">Microsoft Windows 10 iso</a></b>

<h2>Virtual Machine Resouce allocation</h2>
Open virtual box and click on new                                                        (c1)

Name the virtual machine and click on next

<h3>Resource Allocation</h3>

-  Set the base memory to 4096 mB                                                        (c2)
-  Set processors to 2 
-  img (placeholder of next screen)                                                       (c3)
-  Set virtual hard disk to 50.00 GB then click on finish

<h3>Networking</h3>
Connecct adapter to the internal NIC, created during server creation
-img placeholder                                                                         (showing setting network adapter 1)(c4)
open settings then click on network, adapter 1 and select internal network.

<h3>Input ISO img</h3>
Select the newly created virtual machine then on start
-img                                                                                      (placeholder showing new window that pops up after this)\(c5)
Input the iso image and click on mount and retry boot

<h3>Windows 10 Setup</h3>
imgplaceholder of all steps                                                                   (c6 - c11)

The VM will restart
ssetup continued ----                                                                        (c12 - c15)

<h3>Connect to internal network</h3>                                                        (c16)
 Click on start and search for "run" and type in "cmd" to open the command prompt            (c17,c18)
in command prompt type in "ipconfig"                                                         (c19)
confirm NAT is working by pinging a website.                                                 (c20)

<h3>Add client to the Domain</h3>
Right click on start > system > then scroll down and click on "rename this PC (advanced)"    (c21)
input admin credentials, the client will restart (c22, dc58)
