# Haskell and BNFC under Ubuntu in Windows

**Works on Windows 10 Home and Windows 10 Education**   
*(Windows 10 Education is provided by Chapman for free for students)*

1. Install Ubuntu onto your PC from the Microsoft Store following [this link](https://www.microsoft.com/en-us/p/ubuntu/9nblggh4msv6?activetab=pivot:overviewtab).

2. After installing Ubuntu onto your PC, the Ubuntu window will prompt you to enter a username and password. 
If successful, the Ubuntu window will prompt a *"Installation successful!"* message and your Linux command line will be displayed.

3. On your Linux command line, type `sudo apt update` and after type in your password. 
The update command is used to resynchronize the package index files from their sources on Ubuntu Linux through the internet.

4. On your Linux command line, type `sudo apt upgrade` and after type in your password. This
The upgrade command is used to install the newest versions of all packages currently installed on the Ubuntu system.   
*Note: Update and upgrade often to get the latest versions of your packages installed to your Ubuntu.*

5. Navigate through the Window System on Ubuntu.
After the update and upgrade, 
   1. On your Linux command line type `cd ..` 
         
            michelle@DESKTOP-CMCCIPC:~$ cd ..
           
   2. Type `cd ..` again 

            michelle@DESKTOP-CMCCIPC:/home$ cd ..
           
   3. Type `ls` 

            michelle@DESKTOP-CMCCIPC:/$ ls 
            bin   dev  home  lib    lib64   media  opt   root  sbin  srv  tmp  var
            boot  etc  init  lib32  libx32  mnt    proc  run   snap  sys  usr

   4. Type `cd mnt` 

           michelle@DESKTOP-CMCCIPC:/$ cd mnt
          
   5. Type `ls` (This will display your C: drive in your Window System) 

           michelle@DESKTOP-CMCCIPC:/mnt$ ls 
           c
        
   6. Type `cd c` 

           michelle@DESKTOP-CMCCIPC:/mnt$ cd c
           
   7. Type `ls`

           michelle@DESKTOP-CMCCIPC:/mnt/c$ ls 
           '$Recycle.Bin'             PerfLogs                     Xilinx
            Apps                     'Program Files'               cygwin64
            Autodesk                 'Program Files (x86)'         hiberfil.sys
            Config.Msi                ProgramData                  mfg.sdr
            Dell                      Recovery                     pagefile.sys
           'Documents and Settings'  'System Volume Information'   swapfile.sys
            Intel                     Users                        tools
            IntelOptaneData           Windows                      windows-version.txt

   8. Type `cd Users`

            michelle@DESKTOP-CMCCIPC:/mnt/c$ cd Users
            
   9. Type `ls` (This is displaying your folders in your Window System)

            'All Users'   Default  'Default User'   Michelle    Public   desktop.ini

   10. From here, navigate to your Programming Languages folder

6. In your Programming Languages folder, 
   1. Type `sudo apt install haskell-platform` and after type in your password
   2. Type `sudo apt install haskell-stack` and after type in your password 
   Note: Ubuntu package for Ubuntu 16.10 and up, the Stack version might lag so type `stack upgrade` after you finish install it.

7. To download BNFC 
In your Programming Languages folder,
     1. Type `stack install BNFC` or `cabal install BNFC`
     2. Type `sudo apt install make`
 
     
Cited Resources: <br>
https://www.cyberciti.biz/faq/how-do-i-update-ubuntu-linux-softwares/  
https://www.haskell.org/platform/#linux-ubuntu  
https://docs.haskellstack.org/en/stable/install_and_upgrade/   
