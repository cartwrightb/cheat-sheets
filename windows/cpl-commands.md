Get-ChildItem -Path C:\Windows\system32\* -Include *.cpl | Sort-Object -Property Extension | Select-Object -Property Name | Format-Wide -Column 1

Applet Name	File Name	Details
Add or Remove Programs	appwiz.cpl	This opens the Uninstall a Program applet. Used to uninstall installed programs, or add or remove features from Windows.
Date and Time	timedate.cpl	Opens the Date and Time applet. Allows you to set a date and time, change the time zone, add additional clocks, and sync with internet time.
Device Manager	hdwwiz.cpl	The Device Manager lists all installed hardware. Used to install and remove devices, manage drivers, and more.
Display	desk.cpl	Display provides you with options to configure display-related settings, such as the color profile, scaling, resolution, etc.
Firewall	firewall.cpl	Opens the Windows Firewall. Turn it on or off, and open the advanced settings to block or allow connections.
Infrared	irprops.cpl	Lets you manage infrared devices if supported on the device.
Internet Options	inetcpl.cpl	Opens the classic Internet Options window. Manage internet settings that Internet Explorer, Microsoft Edge, and other browsers may use.
Game Controllers	joy.cpl	Manage game controllers connected to the computer.
Mouse	main.cpl	The mouse controls enable you to change mouse icons, button behavior, wheel scrolling, mouse sensitivity, and more.
Network Connections	ncpa.cpl	Lists all known network connections and their status. Can be used to manage the different network cards on your device.
Power	powercfg.cpl	Opens the Power Options. Set a power plan, and customize it.
Region	intl.cpl	The Region control panel applets lets you change date and time formats, your location, and the locale.
Sound	mmsys.cpl	The Sound properties list all playback and recording devices, options to configure them, manage sound levels, and other communication devices.
System Properties	sysdm.cpl	System Properties lets you manage remote connections, computer’s name and domain, and links to other critical Control Panel files.
Tablet PC	tabletpc.cpl	Allows you to manage certain settings while running in tablet PC mode.
Location Information	telephon.cpl	Set your country, area code, carrier code, and dial numbers for telephony and modem services.
Security and Maintenance	wscui.cpl	Manage Security and Maintenance related features such as User Account Controls, firewall, Windows Security components, and much more.
Bluetooth Authentication Agent	bthprops.cpl	This file is responsible for authenticating Bluetooth connections with the device.
Windows 8: Opens Devices Settings app
Windows 7: Opens the Bluetooth Devices list under Devices and Printers.
Windows Vista: Opens the Control Panel applet called Bluetooth Devices.
Default Control Panel applets in Windows (11)

Applet Name	Canonical Name
Action Center	Control /Name Microsoft.ActionCenter
Administrative Tools	Control /Name Microsoft.AdministrativeTools
AutoPlay	Control /Name Microsoft.AutoPlay
Biometric Devices	Control /Name Microsoft.BiometricDevices
BitLocker Drive Encryption	Control /Name Microsoft.BitLockerDriveEncryption
Color Management	Control /Name Microsoft.ColorManagement
Credential Manager	Control /Name Microsoft.CredentialManager
Date and Time	Control /Name Microsoft.DateAndTime
Default Programs	Control /Name Microsoft.DefaultPrograms
Device Manager	Control /Name Microsoft.DeviceManager
Devices and Printers	Control /Name Microsoft.DevicesAndPrinters
Display	Control /Name Microsoft.Display
Ease of Access Center	Control /Name Microsoft.EaseOfAccessCenter
Family Safety	Control /Name Microsoft.ParentalControls
File History	Control /Name Microsoft.FileHistory
Folder Options	Control /Name Microsoft.FolderOptions
Fonts	Control /Name Microsoft.Fonts
HomeGroup	Control /Name Microsoft.HomeGroup
Indexing Options	Control /Name Microsoft.IndexingOptions
Infrared	Control /Name Microsoft.Infrared
Internet Options	Control /Name Microsoft.InternetOptions
iSCSI Initiator	Control /Name Microsoft.iSCSIInitiator
iSNS Server	Control /Name Microsoft.iSNSServer
Keyboard	Control /Name Microsoft.Keyboard
Language	Control /Name Microsoft.Language
Location Settings	Control /Name Microsoft.LocationSettings
Mouse	Control /Name Microsoft.Mouse
MPIOConfiguration	Control /Name Microsoft.MPIOConfiguration
Network and Sharing Center	Control /Name Microsoft.NetworkAndSharingCenter
Notification Area Icons	Control /Name Microsoft.NotificationAreaIcons
Pen and Touch	Control /Name Microsoft.PenAndTouch
Personalization	Control /Name Microsoft.Personalization
Phone and Modem	Control /Name Microsoft.PhoneAndModem
Power Options	Control /Name Microsoft.PowerOptions
Programs and Features	Control /Name Microsoft.ProgramsAndFeatures
Recovery	Control /Name Microsoft.Recovery
Region	Control /Name Microsoft.RegionAndLanguage
RemoteApp and Desktop Connections	Control /Name Microsoft.RemoteAppAndDesktopConnections
Sound	Control /Name Microsoft.Sound
Speech Recognition	Control /Name Microsoft.SpeechRecognition
Storage Spaces	Control /Name Microsoft.StorageSpaces
Sync Center	Control /Name Microsoft.SyncCenter
System	Control /Name Microsoft.System
Tablet PC Settings	Control /Name Microsoft.TabletPCSettings
Taskbar and Navigation	Control /Name Microsoft.Taskbar
Troubleshooting	Control /Name Microsoft.Troubleshooting
TSAppInstall	Control /Name Microsoft.TSAppInstall
User Accounts	Control /Name Microsoft.UserAccounts
Windows Anytime Upgrade	Control /Name Microsoft.WindowsAnytimeUpgrade
Windows Defender	Control /Name Microsoft.WindowsDefender
Windows Firewall	Control /Name Microsoft.WindowsFirewall
Windows Mobility Center	Control /Name Microsoft.MobilityCenter
Windows To Go	Control /Name Microsoft.PortableWorkspaceCreator
Windows Update	Control /Name Microsoft.WindowsUpdate
Work Folders	Control /Name Microsoft.WorkFolders
Default Control Panel applets in Windows with canonical names

Applet Name	File Name
Add a Device wizard	DevicePairingWizard
Add Hardware wizard	hdwwiz
Windows To Go	pwcreator
Work Folders	WorkFolders
Performance Options (Visual Effects)	SystemPropertiesPerformance
Performance Options (Data Execution Prevention)	SystemPropertiesDataExecutionPrevention
Presentation Settings	PresentationSettings
System Properties (Computer Name)	SystemPropertiesComputerName
System Properties (Hardware)	SystemPropertiesHardware
System Properties (Advanced)	SystemPropertiesAdvanced
System Properties (System Protection)	SystemPropertiesProtection
System Properties (Remote)	SystemPropertiesRemote
Windows Features	OptionalFeatures
OR
rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,2
Control Panel applets with standalone .exe files
Control Panel Applets with RunDLL32 Accessibility

Applet Name	RunDLL Cmdlet
Add a Printer Wizard	rundll32.exe shell32.dll,SHHelpShortcuts_RunDLL AddPrinter
Additional Clocks	rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,1
Date and Time (Additional Clocks)	rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,1
Desktop Icon Settings	rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,0
File Explorer Options (View tab)	rundll32.exe shell32.dll,Options_RunDLL 7
File Explorer Options (Search tab)	rundll32.exe shell32.dll,Options_RunDLL 2
Internet Properties (Security tab)	rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,1
Internet Properties (Privacy tab)	rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,2
Internet Properties (Content tab)	rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,3
Internet Properties (Connections tab)	rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,4
Internet Properties (Programs tab)	rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,5
Internet Properties (Advanced tab)	rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,6
Mouse Properties (Pointers tab 1)	rundll32.exe shell32.dll,Control_RunDLL main.cpl,,1
Mouse Properties (Pointer Options tab 2)	rundll32.exe shell32.dll,Control_RunDLL main.cpl,,2
Mouse Properties (Wheel tab 3)	rundll32.exe shell32.dll,Control_RunDLL main.cpl,,3
Mouse Properties (Hardware tab 4)	rundll32.exe shell32.dll,Control_RunDLL main.cpl,,4
Screen Saver Settings	rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,1
Set Program Access and Computer Defaults	rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,3
Sound (Recording tab)	rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,1
Sound (Sounds tab)	rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,2
Sound (Communications tab)	rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,3
Control Panel applets saved in DLLs
Third-Party Control Panel Applets