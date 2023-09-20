# Client-Creation-VM-

All IT demonstrations going forward will be performed using this virtual desktop client

<h2>Requirements</h2>

-  <b><a href="https://www.virtualbox.org/wiki/Downloads">Virtual Box</a></b>
-  <b><a href="https://www.microsoft.com/en-us/software-download/windows10">Microsoft Windows 10 iso</a></b>

<h2>Virtual Machine Resouce allocation</h2>
Open virtual box and click on new                                                        (c1)
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c1.JPG" width=600 height=300>


Name the virtual machine and click on next

<h3>Resource Allocation</h3>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c2.JPG" width=600 height=300> <img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c3.JPG" width=600 height=300>
-  Set the base memory to 4096 mB                                                        (c2)
-  Set processors to 2 
-  img (placeholder of next screen)                                                       (c3)
-  Set virtual hard disk to 50.00 GB then click on finish

<h3>Networking</h3>
Connecct adapter to the internal NIC, created during server creation
-img placeholder                                                              
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c4.JPG" width=600 height=300>(showing setting network adapter 1)(c4)
open settings then click on network, adapter 1 and select internal network.

<h3>Input ISO img</h3>
Select the newly created virtual machine then on start
-img
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c5.JPG" width=600 height=300>(placeholder showing new window that pops up after this)\(c5)
Input the iso image and click on mount and retry boot

<h3>Windows 10 Setup</h3>
imgplaceholder of all steps                                                                   (c6 - c11)
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c6.JPG" width=600 height=300>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c7.JPG" width=600 height=300>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c8.JPG" width=600 height=300>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c9.JPG" width=600 height=300>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c10.JPG" width=600 height=300>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c11.JPG" width=600 height=300>
The VM will restart
ssetup continued ----
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c12.JPG" width=600 height=300>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c13.JPG" width=600 height=300>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c14.JPG" width=600 height=300>(c12 - c15)
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c15.JPG" width=600 height=300>

<h3>Connect to internal network</h3>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c16.JPG" width=600 height=300>(c16)
 Click on start and search for "run" and type in "cmd" to open the command prompt
 <img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c17.JPG" width=600 height=300> <img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c18.JPG" width=600 height=300>(c17,c18)
in command prompt type in "ipconfig"
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c19.JPG" width=600 height=300>(c19)
confirm NAT is working by pinging a website.
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c20.JPG" width=600 height=300>(c20)

<h3>Add client to the Domain</h3>
Right click on start > system > then scroll down and click on "rename this PC (advanced)"
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c21.JPG" width=600 height=300>(c21)
input admin credentials, the client will restart
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c22.JPG" width=600 height=300>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/dc58.JPG">(c22, dc58)
