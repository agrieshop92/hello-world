
# **The Tech-iest of all Blogs**

## *By: Autumn Grieshop*

#### *autumn.grieshop@student.sierracollege.edu*

### __*About me*__
Hello my name is Autumn and this is my basic biography using markdown. I'm 26 years old and I enjoy doing multiple things that vary. 
I enjoy drinking beer, riding motorcycles, canoeing, hiking, camping, building computers, taking photographs, and baking. I also enjoy playing 
with my Border Collie, Dallas, as well as my bearded dragon, Arkose. Currently my favorite shows are Better Call Saul, Workaholics, Bojack Horseman, 
Game of Thrones, and Adventure Time.

I'm currently in school for my Computer Information Science - Networking and Security degree as I really enjoy technology and learning how it functions
and how I can personally help to create a functioning network and protect it. I also am working in a job that's contract by the state, which sounds cool
when written down, however my current position is mostly just a basic help desk position answering general questions with no troubleshooting issues. 

I hope you enjoy my work.

- How does a computer get drunk? 
- It takes screenshots.

## __*.::Class 1::.*__
### Skill 1.1 - Prepare for Installation Requirements

There are 64 computers in this classroom. They all have a keyboard and mouse as peripherals, and they all include a motherboard, hard drive, and processor
as basic components that make the computer up. The computers I have counted are PC computers running Windows, and cell phones in the class, based on 
the head count of the students/teachers. A computer, by my definition, is a functioning component that computes data.

### Class Notes

Steps to install Windows 10 

* Determine hardware requirements and compatibility
* Choose between an upgrade and a clean installation
* Determine appropriate editions according to device type
* Determine and create appropriate installation media

**Versions of Windows 10**

* Home
* Pro
* Enterprise
* Mobile
* Mobile Enterprise
* Education
* IO,T
* S

**Min. Requirements**

* 1 Ghz processor
* 1 GB ram for 32bit or 2GB for 64bit
* 16GB hard drive for 32 bit OS or 20 GB for 64bit OS
* DirectX9 or Later GPU with WDDM 1.0 driver
* 800x600 display

**3 Deployment Options**

* Wipe & Load Clean install
* In-place upgrade
* Provisioning

### __Skill 1.1 Checkpoint__

1. Who is the primary user of the PC?
 -  Me, my work computer

2. What are the technical specifications of that machine, as compared to the Windows 10 min requirements?
 - 1.8 Ghz Processor AMD Pro A10-R9
 - 8GB Ram
 - 237.50GB hard drive
 - DirectX11
 - 1920 x 1080 x 60 Hertz

3. How would you go about upgrading this machine? Why did you choose this approach? Did you use any Microsoft tools to help determine your upgrade? If so, which tools?
 -  I would upgrade this machine using the In-place upgrade. I chose this approach because, since it is a work computer, a clean install would wipe all of the necessary programs needed to do the job correctly off of the PC, thus causing a longer downtime of the working computer in order to take the time to re-install all the software necessary. I did not use any tools to determine my upgrade, because when I tried to look for the Windows 10 Upgrade Assistant tool, it seemed to no longer exist. 

4. What version of Windows 10 would you install? Why? 
 -  I would install Windows Enterprise to this computer, because it's one of the versions more geared towards a workspace, and provides extra security features with Windows Business update. While Enterprise is geared towards medium or large businesses, it would be good with my computer as well as the other computers in the office, because all these computers are apart of a large, well known company, that would benefit from extra security measures. 

## __*.::Class 2 - No Class::.*__

## __*.::Class 3::.*__

### "Since We Last Met": Find an article relevant to Windows 10

Chrome recently released an new version, version 69, that fixes an exploit that would allow hackers to steal Wi-Fi credentials with "a click of a button." This attack is called Wi-Jacking. All a person has to do is send de-authentication requests to the router, which in turn, disconnects said router from the network. Then a karma attack is sent, which is basically a spoofed Wi-Fi access point that mimics a familiar AP. Then, the victim must open an HTTP page. Since pages are easy to modify, the hacker will spoof the page to resemble a Wi-Fi login access page. Since the user is mimicking the Wi-Fi AP, which causes Chrome to auto-fill the information in the hidden login fields. All it takes is one click from the victim. Now that Chrome has patched this vulnerability, it's on par with other browsers, such as Firefox and Opera and Edge. 

Source: 

[Article 1](https://www.zdnet.com/article/google-fixes-chrome-issue-that-allowed-theft-of-wifi-logins)

[Article 2](https://www.wired.com/story/krack-wi-fi-wpa2-vulnerability/)

[Article 3](https://www.thesun.co.uk/tech/7176735/chrome-hack-home-wifi-network/)

### Class Notes

_Tech Tools Live:_ Useful tools 

1. Sniping Tools
2. NETLAB+
3. OnTheHub/Microsoft Imagine

## __*.::Class 4::.*__

### __Skill 1.2 Checkpoint__

1. In what ways is the Media Creation Tool similar to the DIY USB installation?  In what ways is it different? _[Extra Credit]_
 - The MCT is similar to the USB installation in that they both can install Windows 10 to a machine. The MCT can download the required Windows 10 edition based on your selections and can copy it to the USB drive. 
 - They are different in the sense that a USB drive may have an outdated version of Windows 10 installed on it. The MCT also upgrades to Windows 10 as an in-place upgrade, while a USB can do perform a clean install.

2. Why would a user be interested in multiple partitions on a hard drive?  Use a Windows tool (GUI or CLI) to create a partition and describe the steps that you took to create multiple partitions.
 - A user might be interested in multiple partitions in order to dual boot Windows or other OS's. This can be useful in a troubleshooting situation, or useful, in my case, learning a new OS while having a familiar one to return to. Another reason is to have a drive to keep personal files on for a backup.
 - You can use either disk management `diskmgmt.msc` or disk partition `diskpart` to create multiple partitions on a hard drive. You would enter these commands into the 'Run' window. 

3. Describe each step that requires "user attention" during the clean installation of Windows 10.
 - Select language
 - Time and currency 
 - Keyboard input
 - 'Install Now'
 - Enter product key
 - Which type of installation? (Clean)
 - Where to install windows? (Create partitions and select drive to install to)
 - Select Region
 - Select correct keyboard layout
 - Create a user account name
 - Create a password
 - Add a password hint
 - Choose to use Cortana
 - Choose privacy settings
 - Choose network

4. What is one Windows Feature that you chose to add after installation?  How did you add that feature?
 - .NET Framework. It allows the user to use older applications that were created on a previous .NET version
 - You can select and de-select optional features by opening the Run window, and using `optionalfeatures.exe`. You can also do the same thing by typing `Enable-WindowsOptionalFeatures` inside of an administrative run PowerShell window.

5. On Windows 8.1, install an application that may not be Windows 10 compatible.  Why do you think this application may not be compatible?
 - If you installed a program that would not be windows 10 compatible on a Windows 8.1 machine, it may work for the 8.1 OS, but not for the 10 OS. This program would not be compatible because of how the OS' are made. They are both made differently, so a program designed to run on a lesser OS may work ,but that program may not be updated enough to run the minimum requirements that 10 would require to run properly.

6. Create a very special text file that you would like to be included in the upgrade.  What is in the file?  Where is it located?
 - The file I created is called "Myfile.txt". It is located in the F: partition of Windows that was separated on it's own using disk management. The file contains all of the programs currently installed on the computer, in the event of an unnatural shutdown or memory wipe.

7. Describe each step that requires "user attention" during the in-place upgrade of Windows 10.
 - The in-place upgrade is very similar to the 'clean' install of Windows 10. Most steps require user attention. The order goes as such: Accept the license terms, choose what kind of upgrade (USB installation or download), then choose if you want to keep your personal files and apps, personal files, or nothing, choose whether or not to use speech recognition, whether or not to use location, turn on find device or not, choose whether or not to send diagnostic information to Microsoft, to improve typing recognition or not, get tailored experiences with diagnostic data, and whether or not to let apps use advertising ID. 

## __*.::Class 5 - Absent::.*__

### __Skill 1.3 Checkpoint__

1. Create a list of hardware that a user might have that require a driver installation.
 - Monitor
 - Keyboard
 - Mouse
 - Printer
 - GPU
 - Webcam

2. Locate a device from your list (for example, printer or external storage) and install it on Windows 10 (VM in class, machine at home, maybe the host machine in class?)
 - I installed the HP Officejet 6830 printer driver.

3. Locate the version of the driver and see if it is the most current version available (in the case of the printer, check the manufacturer website).
 - It is the most current version.

4. If necessary update the device.
 - It is updated.

5. Disable the device.  Does this affect Windows performance?  What happens when you disable other devices?  Try disabling your network card - how was that experience?
 - I Disabled the HP Officejet Pro 6830 printer installed on my Windows 10 machine. It didn't not affect any Windows performance, besides the ability to print from my computer, or to scan to my computer. I disabled my network card as well and it affected my ability to get new updates, access the internet, and use internet-based apps (such as Steam).

6. Why would I disable updates over metered connections?  Capture a screenshot of the screen on which you disabled this feature.
 - I would disable updates over metered connections in order to prevent an excess amount of data usage on the internet provider bill that I may have, especially if I do not pay for, or have an unlimited data connection plan. 
 - ![Picture](https://i.imgur.com/wCBNQmy.png)

7. Perform a "rollback" of a driver update.  Note, you will need to access a different USB device if you have been working with a printer.
  - Open device manager, select the device, right click and select properties, select driver details, click on the driver tab, and select 'roll back driver'. 

8. After installing a USB microphone, a system has extremely poor performance.  How would you check to see if the performance issues are related to the USB microphone?
 - Re-enable the USB Microphone device to see if it increases or helps performance, then disable another device to see if disabling a device decreases performance. 

## __*.::Class 6::.*__

### Class Notes

### __Class Activity__

*Activity: Read [this article](https://techcrunch.com/2018/09/24/microsofts-new-windows-virtual-desktop-lets-you-run-windows-10-in-the-cloud/) and explain what the future of OS' looks like based on this article.*

This article explains that Microsoft has unveiled a new program to use. It is Windows 10...as a virtual environment on Azure. It comes with Windows 7 security updates, Windows 10 security updates, access to the store, as well as Office 365. This is a great way for non Windows 10 and even Windows 10 uses alike to get involved with Windows 10, and even get the chance to play around with the Operating System and become more familiar with it's uses and functions. 

The future of Operating Systems now seems to have a new door that has opened. Now, companies can create virtual Operating Systems that would be able to run just as smoothly and efficiently as a regular operating system would, on top of another operating system - for example, Windows 7. This is a great way to help a computer save space, instead of installing pesky Windows install files, users can just run the virtual environment instead. This is also good for large businesses, that don't have the funds to upgrade to Windows 10. Instead, they can just run the virtual environment on Azure and save on both money and time! 

*Activity: Create a partition of X size using the GUI and PowerShell/CMD*

Open Disk Management > Select Action > Select Create VHD > Name it, select the size, click create > Right click your new disk and select "Initialize Disk" > Select Ok > Right click the new partition and select ' New simple Volume' > Specify Space > Specify the letter > Specify Format options > Select Finish > Done!

__Hyper-V Types:__

 - Type 1 - The VM runs on top of the bare metal. It does not have a host OS
  - VM
  - Hypervisor
  - Bare Metal

 - Type II - the VM runs on top of the host OS
  - VM
  - Hypervisor
  - Host OS
  - Bare Metal

![HyperVTypes](https://www.computerperformance.co.uk/images/win8/hypervisor_sm.jpg)

### __Skill 1.4 Checkpoint__

*Post-Installation Jigsaw Challenge Activity*

Four different things that we do to windows once it's installed

Topics: 

1. Customize the UI (Bigger Tyler)
 - Go into the settings and selection 'Personalization." This menu is very similar to Windows 7 or 8 customization. From here you can configure the background, the colors, the lock screen, themes, and even the start bar. The start bar itself has many new options in order to customize your experience. You can also create multiple desktops, which mimics multiple screens or workstations. 

2. Configure Accessibility and Cortona (Tyler)
 - To configure these options, go to settings and select "Ease of Access." On the left you can choose various options to help you navigate windows better. Some options can assist with blind or deaf users, such as the narrartor, which reads out the words on the screen. You can also access the Ease of Access center by going into the control panel, select 'Ease of Access', and then "Ease of Access center", which gives you more detailed options to enjoy Windows easier.
  - To configure Cortana settings, you can click on Cortona in the search bar below, and click on settings in the left side of the search bar. This allows you to turn Cortana on or off, or enable/disable various settings, such as using "Hey Cortana" if you have a microphone, or settings up a keyboard shortcut (Win key + C) to listen to your commands. You can even enable to use Cortana when the device is locked, and enable/disable the permissions that you want Cortana to allow. 

3. Configure Edge and Internet Explorer (Andrew)
 - ~~To configure Edge, you can go to Local Disc C: > Windows > System Apps > MicrosoftEdge > right click the folder, and select 'delete'.~~ 
 - To configure Edge, simply open Edge, click on the 3 dots in the upper right hand corner, select settings, and then navigate through these extemely simply settings to configure Edge.
  - To configure Internet Explorer, you can either open IE, select File > Settings, and configure the settings through there, or you can enter the settings by opening the Run box (Win key + Run), and typing `inetcpl.cpl`. This enters the same settings configuration box as mentioned earlier. This allows you to access more advanced settings, such as security, privary, the content allowed, connections (such as VPN or Proxy), and other various settings.

4. Configure Power Settings and Hyper-V (Autumn)
 - To edit the power settings, type 'Power Settings' into the search bar to access the power settings menu. Alternatively, you can select power settings by going into the settings menu, selecting 'system', then selecting 'Power & Sleep' on the left hand sidebar. Once there, you can choose when the computer sleeps. You can select 'additional power settings' on the right side to access the power options menu. Here, you can select more options, such as power plans, when to turn the display off, and what the power buttons do. 
 - Hyper-V is a program used to create and run virtual machines. It is very similar to VMware Workstation Pro, but it can be faster and more efficient. However, Hyper-V does not allow you to switch between multiple OS's, but it does allow you to use Ubuntu. To use Hyper V to create a virtual machine, first you must enable Hyper-V. You can enable it through the GUI, CMD, or PowerShell. The GUI offers a quick install by going into the Windows optional features, and selecting Hyper-V, and then restarting the PC. The PowerShell and GUI commands are a bit more complicated. You can use the command `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All` to enable Hyper-V through PowerShell, or with DISM using `DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`.

## __*.::Class 7::.*__

### Class Notes

LSDO - Local Sight Domain Organizational (units)

 - S can take precedence over L 
 - O can be a group of users or devices 
 - O can often be seen as OU

Group Policy

 - Let's play around with Local Group Policy Editor...
 - Centralized control for...
  - User Settings
  - Computer Settings
  - Control and Deployments of Applications
  - Control User Experience

What does it change? 

How to force the group policy update - `gpudate /force` or logoff & restart.

### __Class Activity__

In Group policy, can you...

1. Block Microsoft Accounts?
 - Yes. You must select `Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options > Accounts: Block Microsoft Accounts,` and then change the setting to either Disabled, users can't add Microsoft accounts, or users can't add or log on with Microsoft accounts. 
2. Enforce a password length of 10 characters?
 - Perhaps. You must select `Computer Configuration > Windows Settings > Security Settings > Account Policies > Password Policy` and set the minimum length to 10. However, there does not seem to be a rule for setting the maximum length.
3. Disable secure desktop in UAC? (NOT RECCOMENDED)
 - Yes. You can go to `Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options > User Account Control: Switch to the secure desktop when prompting for elevation` and then select "Disable".  

### __Skill 1.5 Checkpoint__

"What is "UAC"? Why is it important? When did Microsoft introduce UAC? Is UAC on your Sierra host machine different than your VM? If so, how so?"

User Control Access allows software to be used by standard use, until an administrator elevates the software in order to allow it to use administrative rights. This is to help prevent malware from compromising the system. UAC includes a feature called 'secure desktop', that dims the screen behind the UAC box to allow for a more secure selection.  UAC was first introduced in Windows Vista, but it was first named Limited User Account (LUA), and then named User Account Protection(UAP), before settling on UAC. 

UAC on my Sierra host machine is different in the sense that the VM has it's own personal  UAC that is not used as much as you would use it on windows, because the VM is a virtual environment. 

## __*.::Class 8::.*__

### Class Notes

_ADK and Provisioning_

Provisioning packages through ADK is very easy. First you must download the ADK tool. After you've selected where to download it, you can select what options of the ADK tool you wish to download.  After downloading, you can create a package, which is basically a 'screenshot' of your desktop that you can then use to upload the configurations that you've saved to the package. 

![Imgur](https://i.imgur.com/yqnJXUS.png)

_Differences between old school Control Panel and Windows 10 control panel._

A lot of differences and similarities can be found between the old school control panel and the new Windows 10 control panel. Some options within the new control panel actually open up options on the old control panel, such as Adapter Options, Advanced Sharing Options, and the Network and Sharing center. Some features are new to the new control panel, such as the Windows Firewall, and the network options. But there are interesting features on the old control panel as well, such as setting up a network connection, a feature that is harder to find on the new control panel. However, the old control panel links to the new one as well. For example, if you open the troubleshooting menu, it opens up with the new control panel interface. Also, using the old control panel allows you to make more modifications, versus the new interface that limits your options. 

![Network](https://i.imgur.com/wapgwR4.png)

_IP addresses_

IP addresses are used to determine which device is which, and which website is which. You can configure your Ipv4 address to route all traffic through a certain DNS server, such as 8.8.8.8, which is Google, or 1.1.1.1, which is private. You can accomplish this by going to Control Panel > Network & Internet settings > Network connections > right clicking a network connection > selecting properties > selecting Ipv4 > clicking properties > and entering in the DNS you wish to use. You can also use this properties box to assign a particular IP address and default gateway to the machine you are working on. 

![Ipv4](https://i.imgur.com/4uqs1m5.png)
_Troubleshooting_

Windows offers many troubleshooting wizards that can often help with problems that are caused by unknown issues. You can access the most used troubleshooting wizards by going to 'Settings > Updates & Security > Troubleshooting. Here you can see many different problems that can be resolved through windows. 

![Troubleshooting](https://i.imgur.com/oSF7gkk.png)

_Wifi_
Windows 10 allows multiple new options to configure and manage the Wi-fi networks. The best way to access this menu is to go to 'Settings > Network & Internet > Wifi. This menu will only show up as long as you are connected to a wireless network, otherwise it will show 'Ethernet.' 

![Wifi](https://cdn.arstechnica.net/wp-content/uploads/2015/07/windows-10-wifi-sharing-640x505.png)

### __Class Activity__

_"What is a 'software bug'? Describe the 'bug' that is delaying the release of the 1809 update for Windows 10?"_

 - A software bug is an error, flaw, failure or fault in a computer program or system that causes it to produce an incorrect or unexpected result, or to behave in unintended ways.
 - The 'bug' that is delaying the release of the 1809 update is the simple fact that it is permanently deleting user data, such as documents, pictures, music, and videos. It also is not allowing Edge and other apps to not connect to the internet. On some computers, the update is blocked, due to Intel in combabilities. This is a very serious flaw that Microsoft did not even catch, even though it was warned by Windows Insiders months ago, before rolling out the update to some users. They have since post-posted the update until they can fix this serious issue. 
 - [Source](https://www.theverge.com/2018/10/6/17944966/microsoft-windows-10-october-2018-update-documents-deleted-issues-windows-update-paused) 

### __Skill 2.1 Checkpoint__

Create a "Top 5" list of Windows 10 networking best practices, tips, tricks and troubleshooting strategies.

1. One good tip to prevent Microsoft from pre-downloading updates as they're released is to **limit the background data usage**. This feature is generally used by users that do not have an unlimited internet usage plan. To access this feature, you go to 'Settings > Network & Internet > Data Usage > and then set the Background data limit to 'Always'. [Source](https://www.windowscentral.com/how-monitor-and-control-data-usage-windows-10-april-2018-update)
2. You can also **prevent background apps** from eating up a lot of data and save you some space and time. You can edit these by going to Settings > Privacy > Background apps, and then choosing to disable apps that you don't use, in order to prevent excess usage. [Source](https://www.groovypost.com/howto/manage-windows-10-data-usage/)
3. Checking your **Windows Update settings** is one of the best tips that can be used to help your computer not automatically download unwanted updates at random times and hours of the day, interrupting your work. If you simply go to 'Settings ? Update & Security > And view the many options listed here, you can choose how to configure your update settings to your liking, including choosing how updates are downloaded, if at all, how they're installed, and even the active hours so updates will not install during your most active times of the day. [Source](https://www.lifewire.com/how-to-change-windows-update-settings-2625778)
4. **Disk Cleanup** is a great way to free up space, re-allocate your disk space, and make sure that your Windows 10 is running on the hard drive as fast as it can. Disk cleanup will remove unnecessary files, such as folders left behind from removed apps, temp files, and dead paths. Disk cleanup will also allow you to defrag the hard drive, which is useful in freeing up the most space possible at the time of running the program.  [Source](https://support.microsoft.com/en-us/help/4026616/windows-10-disk-cleanup)
5.  An easy way to keep windows starting up quickly is to **disable apps that also start on startup.** Instead of wasting time waiting for unnecessary apps to start up when Windows does, you can disable those apps from starting, so that it saves time and computer memory when starting, allowing for, not only a faster start up time, but allows less space to be used.  [Source](https://support.microsoft.com/en-us/help/4026268/windows-10-change-startup-apps)

## __*.::Class 9::.*__

### Class Notes

- FAT
  - Lightweight
  - Designed for floppy disks
  - Designed on 8 bit file systems
  - Doesn't use file permissions
  - Contains two copies of FAT table
- NTFS
  - Created in 1993
  - More security based on ACLs and Encryption (EFS)
  - Optimized for 4kb clusters but supports a max of 4MB
  - Support for BitLocker and large volumes(16EB)
  - Faster write speed
  - Uses ADS (Alternate data streams)
  - Can be used on Linux and MAC, but MAC is read-only
  - Limited to 16,000 folders in a single directory
  - Uses LZNT1 algortithim, which means that it cannot compress anything greater then 4kb)
- Striped arrays of disks
  - Data is divided into stripes
  - Smaller stripes means faster array
  - Can use both striping and mirroring
  - Is faster
- Mirrored arrays of disks
  - Duplicate data 
  - Creates redundancy
  - Basically a backup
- RAIDS in general
  - Raid 0 - 10 (10 is Raid 1+0)
  - Raid 10 is best and most tested
  - More for small companies
  - Specifically tailor what you need it to be
  - Not a replacement for a backup
  - Good for not Windows
- Storage Spaces
  - More user friendly and optimized
  - Does not limit you to the type of media you use
  - Software-based
  - A lot cheaper, can save money

### __Class Activity__

_"What is BitLocker? How is it configured? I have a USB drive that is configured with BitLocker. Will it work on all Windows 10 machines? How about a MacBook or a Chromebook?"_

BitLocker encrypts the hard drive to protect the Operating System from offline attacks. BitLocker drives can be encrypted with 128 bit or 256 bit encryption, this is plenty strong to protect your data in the event the computer is lost or stolen.  BitLocker protects your hard drive from offline attack. BitLocker also protects your data if a malicious user boots from an alternate Operating System.  With either attack method, BitLocker encrypts the hard drive so that when someone has physical access to the drive, the drive is unreadable.  

A BitLocker USB can theoretically work on all Windows 10 Machines if they have a TPM chip enabled. Otherwise, only encryption works, but not BitLocker itself. It is, however, backwards compatible. BitLocker will work on a Mac, as long as M3 BitLocker Loader is installed. BitLocker is a Microsoft Product, so it's not compatible with a Chromebook. It shouldn't be compatible with a MacBook, but someone created a third party program that makes it compatible.

### __Skill 2.2 Checkpoint__

**Scenario 1: Creating a Large Volume**

**You have a new desktop running Windows 10. However, you try to copy your file repository and find out that you do not have enough disk space. You have 400 GB of free disk space on your C drive and you have 3 smaller 500 GB drives. What can you do?**

You can use the smaller 500GB drives to copy the file repository onto, this helping save your C drive space. You could also move some less important files to one of those GB drives, and keep the backups on the drives as well to make sure that your space is saved. 

Alternatively, you can use a Spanned or a Striped volume to merge the space between hard drives. A spanned volume allows you to combine two or more hard drives of different sizes to create one large volume. On Spanned, drives are utilize sequentially, meaning data won't be written to the second hard drive until the first hard drive is full.

On the other hand, if you use a Striped volume, you can also combine two or more hard drives to create one large volume. However, if you want to use the entire available space, you'll need to use hard drives of the same size. On Striped, data is written across all participating drives, offering better performance than the Spanned option.

**Scenario 2: Configuring a Storage Space/Storage Pool**

**You create a new storage pool for the following disks on your Windows 10 computer:**

- **Serial ATA (SATA): 1 TB**
- **Serial Attached SCSI (SAS): 1 TB**
- **SATA and SAS are two different types of drives with different connectors/interfaces.**
**What is the maximum size you can allocate for your new storage space?**

The minimum space required for Windows 10 is 20GB. That is the allocated space to be used by Windows for the OS files. So if you have two separate drives installed, the total space would be 40GB used, leaving 1.96TB. There's also healthy recovery partitions to remember as well, that takes up about 600MB, which leaves you with roughly 1.9594 terabytes. However, this is all hypothetical, as a fresh Windows installation allows you to choose how much space you wish to allocate when you first set it up. 

## __*.::Class 10::.*__

### Class Notes

### __Class Activity__

### __Skill 2.3 Checkpoint__

