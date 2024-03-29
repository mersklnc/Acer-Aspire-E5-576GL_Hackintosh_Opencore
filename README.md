# Acer-E5-576G-Hackintosh (OpenCore-macOS Big Sur)

Hackintoshing the Laptop

>System Specs:

 - Intel Core i5-8250U (KabyLake)
 - 15.6" HD (1366 x 768)
 - 16GB DDR3L-SDRAM
 - 1000GB HDD + 1000GB SSD
 - Intel UHD Graphics 620 + NVIDIA GeForce MX150 (2GB, GDDR5)
 - Realtek ALC255 (layout-id:30)
 - Intel Wireless 3165
 
 # Installation
 
 For installation, firstly you have to create a USB installer, you can refer to the [OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/extras/big-sur/#a-supported-smbios).
 However, for device-specific EFI prepared for the first installation kindly download and extract the files coming up with the [v0.6.4 release](https://drive.google.com/file/d/1BkRCodyKfyCH9JvMAAgKYGHIntRwFm2I/view?usp=sharing) on your computer and replace the EFI folder on the USB installer with the downloaded one in the 'USB - EFI' folder. For the [v0.7.3 release](https://drive.google.com/file/d/1_O3vONCQTmt7qzF1b-pjUHyl-CHhm2rj/view?usp=sharing) you don't need to do that as the EFI folder this release can be used both for the USB installer and also as the system EFI folder.
 Please note that installation may last longer than expected, especially in comparison to the Catalina installation, so be patient and calm.
 
 # After Installation [(v0.6.4)](https://drive.google.com/file/d/1BkRCodyKfyCH9JvMAAgKYGHIntRwFm2I/view?usp=sharing)
 
 After you successfully install and have access to the main window of Big Sur without any issue, you will realise that the system is fairly sluggish and slow and many of the features will not work or run or else be unavailable. Yet, no matter what, you will have accomplished the first task.
 To speed up your system, all you need to do is just to grab the EFI in the 'System - EFI' folder and replace it with that of the system. For this step, mount your EFI partition via EFI Mounter or OpenCore configurator. After mounting you will notice there is no folder within if you have installed macOS across the whole partition which is strictly recommended. Copy the downloaded EFI folder and paste it in the mentioned partition. Then, reboot the system and voila! You will have a system smooth as butter.
 Please remember to change SMBIOS to be able to use the Apple Services such as iCloud, iMessage, FaceTime, etc. There are lots of tutorials instructing how to do it, you may check [this link](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#generate-a-new-serial) for instance.
 
 # After Installation [(v0.7.3)](https://drive.google.com/file/d/1_O3vONCQTmt7qzF1b-pjUHyl-CHhm2rj/view?usp=sharing)
 There are only few things to configure and the first one is alter the SMBIOS. For the best compatibility it is advised to use iMacPro18,1 in the plist.config file.
 
 # Credits
 - Every single contributor in Hackintoshing
 - [OSX Info](https://osxinfo.net) in Turkish
 - [OpenCore](https://github.com/acidanthera/OpenCorePkg)
 - [Dortania Guides](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html)

test
