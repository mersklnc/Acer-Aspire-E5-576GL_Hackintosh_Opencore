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
 However, for device-specific EFI prepare for the first installation please check on [this link](https://drive.google.com/drive/folders/1Yc85o-RGToApPGObPnnBh7Y2_WoY-PsA?usp=sharing). You will just need to replace the EFI folder on USB installer with the one provided with the link.
 Please note that installation may last longer than expected, especially in comparison to the Catalina installation, so be patient and calm.
 
 # After Installation
 
 After you successfully install and have access to the main window of Big Sur without any issue, you will realise that the system is fairly sluggish and slow and many of the features will not work or run. Yet, no matter what, you accomplished the first task.
 To speed up your system, all you need to do is just to grab this [EFI File](https://drive.google.com/drive/folders/1zMyd-qRiA1cofu_oP2OJ-UT7fG1nbH-E?usp=sharing) and replace it with that of the system. For that, mount your EFI partition via EFI Mounter or OpenCore configurator. After mounting you will notice there is no folder within if you have installed macOS on the whole partition which is strictly recommended. Copy the downloaded EFI folder and paste it in the mentioned partition. Then, reboot the system and voila! You will have a system smooth as butter.
 Please remember to change SMBIOS to be able to use the Apple Services such as iCloud, iMessage, FaceTime, etc. There are lots of tutorials instructing how to do it, you may check [this link](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#generate-a-new-serial) for instance.
 
 # Credits
 - Every single contributor in Hackintoshing
 - [OSX Info](https://osxinfo.net) in Turkish
 - [OpenCore](https://github.com/acidanthera/OpenCorePkg)
 - [Dortania Guides](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html)

test