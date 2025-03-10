# Installing Vms on Virtual Box

Virtual Box is an effective and free methods of installing and running virtual machines.
 
-  <b> Step 1 Locating the VirtualBox set up wizard  </b>

     -   Go to [VirtualBox.org](https://www.virtualbox.org/) and select download to get to the Platform packages and selected the respective OS your machine is on and download the VirtualBox set up wizard.
     
 <p>
<img src="https://sigmawire.net/i/03/DxiKaI.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
</p>
 
<p align="left">
<img src="https://sigmawire.net/i/03/2udB9Y.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
</p>

 - <b> Step 2 Installing the Oracle Virtual Box Manager</b>
    - Start up the wizard and go through the options accepting the EULA, click next, then proceeding with installation and once you see the "Oracle Virtual Box Manager" after successfully opening the software, you are now ready to install your first virtual machine on the program.
    (Note: In the picture below, it already has the windows virtual OS installed. You will not have it there just yet. See the next steps to aquire windows 10 virtual OS.)
  <p>
<img src="https://sigmawire.net/i/03/6Y4yWU.png" height="40%" width="40%" alt="VirtualBox set up wizard"/>
</p>
 
- <b> Step 3 Installing the ISO image</b>
   - In order to run an OS that is not the host on your machine, you need the ISO file for the OS when using VirtualBox. You can locate the ISO by searching [Windows10 ISO download](https://www.microsoft.com/en-us/software-download/windows10?msockid=2caccc00ea4761a20775d9aaeb3c60ba)
   - Scroll down until you see the "download now" under the Create Windows 10 installtion media and click download, then open it once done.
   - Accept the license terms
   - Select "Create installation media"
   - Use recommended PC settings including windows 10 and 64 bit
   - Chose ISO file when selecting media
   - Select where you would like to place the file and proceed with the download
  <p>
   <img src="https://sigmawire.net/i/03/I7iqx2.png" height="30%" width="30%"/>
  </p>        
 <p>
<img src="https://sigmawire.net/i/03/hpECNX.png" height="30%" width="30%" alt="VirtualBox set up wizard"/>
</p>

- <b> Step 4 configuring the window ISO image on virtual box</b>
  -  Once the ISO is installed, open up the VirtualBox manager and select "new" and configure the settings as follows.
  -  For name, name it Windows10
  -  Select the ISO imagie that was intalled in step 3
  -  Ensure the type is windows and version is windows 10 64bit
     <p>
<img src="https://sigmawire.net/i/03/dobiRv.png" height="30%" width="30%" alt="VirtualBox set up wizard"/>
</p>

 -  Moving on to the hardware page, it is recommended if you do not have a lot of ram to spare to leave it at 4Gb of ram. Otherwise you may extend it to at least 8
 -  As for the cores, you may leave it at one but you may increase it if you would like quicker installation although one will surfice. 
 
 <p>
<img src="https://sigmawire.net/i/03/cNQdVS.png" height="30%" width="30%" alt="VirtualBox set up wizard"/>
</p>

 - Finally for the harddisk page ensure the virtual disk is selected with 50Gb which is more than enough for the capabilities of this virtual OS

 <p>
<img src="https://sigmawire.net/i/03/zBJmfZ.png" height="30%" width="30%" alt="VirtualBox set up wizard"/>
</p>

- The virtual windows OS should appear in the manager now as shown below. You are now ready to boot up the virtual OS and configure the settings as another other OS being started for the first time. 

<p>
<img src="https://sigmawire.net/i/03/G19KR6.png" height="30%" width="30%" alt="VirtualBox set up wizard"/>
</p>

 - Note: If the virtual OS has an issue finding the product key when booting up, more often than not the boot order needs to be adjusted 
 - Proceed to settings of the Windows10 virtual OS in the manager, scroll to system, and then unselect floppy disk
 - Then proceed to storage and remove any "unattended files" from the floppy disk
 
