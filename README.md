# Client-Creation-VM-

All IT demonstrations going forward will be performed using this virtual desktop client

<h2>Requirements</h2>

-  <b><a href="https://www.virtualbox.org/wiki/Downloads">Virtual Box</a></b>
-  <b><a href="https://www.microsoft.com/en-us/software-download/windows10">Microsoft Windows 10 iso</a></b>

<h2>Virtual Machine Resouce allocation</h2>
<br>
<div>
Open virtual box and click on new.
 </div>
 <br>
<div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c1.JPG" height=500>
</div>
<br>
<div>
Name the virtual machine and click on next.
 </div>

 <br>
 
<h3>Resource Allocation</h3>
<br>
<div>
Set the base memory to 4096 mB, set processors to 2, set virtual hard disk to 50.00 GB then click on finish.
</div>
<br>
<div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c2.JPG" width=500 >
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c3.JPG" width=500 >
</div>

<h3>Networking</h3>
<br>
<div>
Connect adapter to the internal NIC, created during server creation, open settings then click on network, adapter 1 and select internal network.
</div>
<br>
<div
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c4.JPG" width=600 >
</div>

<br>

<h3>Input ISO img</h3>
<br>
<div>
Select the newly created virtual machine then on start. Input the iso image and click on mount and retry boot.
 </div>
 <br>
 <div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c5.JPG"  height=200>
</div>

<br>

<h3>Windows 10 Setup</h3>
<br>
<div>Follow the prompts
</div>
<br>
<div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c6.JPG" width=500 >
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c7.JPG" width=500 >
</div>
 <br>
 <br>
 <div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c8.JPG" width=500 >
 <img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c9.JPG" width=500>
 </div>
 <br>
 <div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c10.JPG" width=500>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c11.JPG" width=500>
 </div>
 <br>
 <div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c12.JPG" width=500 >
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c13.JPG" width=500 >
 </div>
 <br>
<br>
<div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c14.JPG" width=500 >
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c15.JPG"  width=500>
</div>

 <br>
 
<h3>Connect to internal network</h3>
<br>
<div>
  Click on start and search for "run" and type in "cmd" to open the command prompt.
</div>
<br>
<div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c16.JPG" width=300 >
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c17.JPG" width=300 >
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c18.JPG" width=300 >
</div>
<br>
<div>
Once command prompt is open type in "ipconfig" and confirm NAT is working by pinging a website.
</div>
<br>
<div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c19.JPG" width=500 >
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c20.JPG" width=500 >
</div>

<br>

<h3>Add client to the Domain</h3>
<br>
<div>
Right click on start system then scroll down and click on "rename this PC (advanced)" to make the PC more recognizable to the eye when viewing organization units in active directory. Input admin credentials, the client will restart.
</div>
<br>
<div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c21.JPG" width=500 >
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/c22.JPG" width=500 >
</div>
<br>
<br>
<div>
<img src="https://github.com/narvee09/IT-images/blob/main/Basic%20IT/Client/dc58.JPG">
</div>
