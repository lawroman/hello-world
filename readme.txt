MultiBeast 5.2.1 Released 2012-12-12

NOTE:	MultiBeast 5.2.1: Mountain Lion Edition is ONLY for OS X 10.8.x.

Visible Changes:
	- Added Customization -> Drivers -> System Definitions -> iMac -> iMac 13,1

Internal Changes:
	- Fixed bug in standalone Theme installation location.
	- Fixed Mac mini 6,1 serial number.
	- Updated FakeSMC and Plugins to kozlek's branch v4.3.5.

MultiBeast 5.2.0 Released 2012-12-04

NOTE:	MultiBeast 5.2.0: Mountain Lion Edition is ONLY for OS X 10.8.x.

Visible Changes:
	- Reordered choices in Bootloaders -> Drivers -> Disk
	- Reordered choices in Bootloaders -> Drivers -> System
	- Reordered choices in Customization
	- Removed Bootloaders -> Drivers -> Network -> maolj's AtherosL1cEthernet 
	- Added Bootloaders -> Drivers -> Network -> Atheros - Shailua's ALXEthernet v1.0.2
	- Renamed Bootloaders -> Drivers -> Network -> Lnx2Mac's RealtekRTL81xx Ethernet v0.0.90 to Realtek - Lnx2Mac's RealtekRTL81xx v0.0.90
	- Renamed Bootloaders -> Drivers -> Network -> Realtek Gigabit Ethernet 2.0.6 for 10.7 to Realtek - AppleRTL8169Ethernet 2.0.6 for 10.7
	- Renamed Bootloaders -> Drivers -> Network -> hnak's AppleIntelE1000e Ethernet to Intel - hnak's AppleIntelE1000e v2.1.7
	- Added Bootloaders -> Drivers -> Graphics -> Intel Graphics Patch for Mixed Configurations
	- Added Bootloaders -> Drivers -> Graphics -> NVIDIA Fermi
	- Moved Bootloaders -> Drivers -> Graphics -> NVIDIA Fermi OpenCL Patch to Bootloaders -> Drivers -> Graphics -> NVIDIA Fermi and renamed to OpenCL Patch
	- Moved Bootloaders -> Drivers -> Graphics -> NVIDIA Fermi >2GB OpenCL Patch to Bootloaders -> Drivers -> Graphics -> NVIDIA Fermi and renamed to >2GB OpenCL Patch
	- Removed Bootloaders -> Drivers -> Graphics -> NVIDIA GTX 470 / 480 / 560Ti 448 Cores / 570 / 580 Support 
	- Removed Bootloaders -> Drivers -> Graphics -> NVIDIA GTX 670 / 680 / 690 10.8.0 and 10.8.1 Support
	- Changed Bootloaders -> Drivers -> System -> AppleACPIPlatform Rollback to a menu choice
	- Added  Bootloaders -> Drivers -> System -> AppleACPIPlatform Rollback -> 10.6.8 Rollback for ASUS X58 System
	- Added  Bootloaders -> Drivers -> System -> AppleACPIPlatform Rollback -> 10.8.1 Rollback
	- Changed Customization -> Drivers -> System Definitions Mac mini to a menu choice
	- Added Customization -> Drivers -> System Definitions -> Mac mini -> Mac mini 5,1
	- Added Customization -> Drivers -> System Definitions -> Mac mini -> Mac mini 6,1

Internal Changes:
	- Updated FakeSMC and Plugins to kozlek's branch v4.3.4
	- Updated patched 10.8.0 AppleIntelCPUPowerManagement.kext

MultiBeast 5.1.3 Released 2012-10-27

NOTE:	MultiBeast 5.1.3: Mountain Lion Edition is ONLY for OS X 10.8.x.

Visible Changes:
	- Changed Bootloaders -> Drivers -> Miscellaneous -> USB 3.0 - 3rd Party to a menu choice
	- Added Bootloaders -> Drivers -> Miscellaneous -> USB 3.0 - 3rd Party -> CalDigit
	- Added Bootloaders -> Drivers -> Miscellaneous -> USB 3.0 - 3rd Party -> LaCie

Internal Changes:
	- Updated FakeSMC and Plugins to kozlek's branch v4.3.2

MultiBeast 5.1.2 Released 2012-10-15

NOTE:	MultiBeast 5.1.2: Mountain Lion Edition is ONLY for OS X 10.8.x.

Internal Changes:
	- Fixed EasyBeast and UserDSDT install to delete previous version of FakeSMC.kext if found. 

MultiBeast 5.1.1 Released 2012-10-12

NOTE:	MultiBeast 5.1.1: Mountain Lion Edition is ONLY for OS X 10.8.x.

Visible Changes:
	- Added 1080p Display to Customization -> Boot Options
	
Internal Changes:
	- Fixed deleting HDAEnabler898.kext when installing or upgrading Drivers & Bootloaders -> Drivers -> Realtek ALC8xx -> Without DSDT -> ALC898
	- Fixed deleting HDAEnabler898.kext when installing Drivers & Bootloaders -> Drivers -> Realtek ALC8xx -> Without DSDT -> Optional 3 Port Audio Enabler
	- Fixed TRIM Enabler patches to update kernel cache

MultiBeast 5.1.0 Released 2012-10-12

NOTE:	MultiBeast 5.1.0: Mountain Lion Edition is ONLY for OS X 10.8.x.

Visible Changes:
	- Added NVIDIA Fermi OpenCL Patch to Drivers & Bootloaders -> Drivers -> Graphics
	- Added 10.8.x OpenCL Patch to Drivers & Bootloaders -> Drivers -> Graphics -> NVIDIA Fermi OpenCL Patch
	- Added NVIDIA Retail 304.00.00f20 OpenCL Patch to Drivers & Bootloaders -> Drivers -> Graphics -> NVIDIA Fermi OpenCL Patch
	- Renamed NVIDIA Fermi >2GB OpenCL Patch -> 10.8.0 - 10.8.1 OpenCL Patch to 10.8.x OpenCL Patch	
	- Removed Bootloaders -> Drivers -> Graphics -> NVIDIA GTX 470 / 480 / 560Ti 448 Cores / 570 / 580 Support 
	- Renamed Bootloaders -> Drivers -> Graphics -> NVIDIA GTX 670 / 680 / 690 Support to NVIDIA GTX 670 / 680 / 690 10.8.0 and 10.8.1 Support
	- Merged NVIDIA GTX 670 / 680 / 690 Support -> 10.8.0 Patched GeForceGLDriver.bundle and NVIDIA GTX 670 / 680 / 690 Support -> 10.8.0 Patched GeForceGLDriver.bundle
	- Changed Drivers & Bootloaders -> Drivers -> Disk -> TRIM Enabler to a Menu Choice
	- Added 10.8.0 TRIM Patch to Drivers & Bootloaders -> Drivers -> Disk -> TRIM Enabler
	- Added 10.8.1+ TRIM Patch to Drivers & Bootloaders -> Drivers -> Disk -> TRIM Enabler
	- Added Drivers & Bootloaders -> Drivers -> Realtek ALC8xx -> Without DSDT -> Optional 3 Port Audio Enabler
	- Removed Miscellaneous -> FakeSMC Plugins -> AMD RADEON Plugin
	- Removed Miscellaneous -> FakeSMC Plugins -> NVIDIA GeForce Plugin
	- Renamed Patched AppleIntelCPUPowerManagement -> OS X 10.8.0 to OS X 10.8.x

Internal Changes:
	- Updated toleda's patched AppleHDAs to the 10.8.2 versions
	- Enhanced Drivers & Bootloaders -> Drivers -> Realtek ALC8xx -> With DSDT to patch /Extra/DSDT.aml with layout-id 1
	- Changed Drivers & Bootloaders -> Drivers -> Realtek ALC8xx -> Without DSDT to install HDAenabler1.kext
	- Updated hnak's AppleIntelE1000e Ethernet to v2.1.7
	- Updated FakeSMC and Plugins to kozlek's branch v4.2.13
	- Fixed NVIDIA Fermi >2GB OpenCL Patch

MultiBeast 5.0.2 Released 2012-08-13

NOTE:	MultiBeast 5.0.1: Mountain Lion Edition is ONLY for OS X 10.8.x.

Visible Changes:
	- Renamed NVIDIA GTX 470/480/560Ti 448/570/580 Support to NVIDIA GTX 470 / 480 / 560Ti 448 Cores / 570 / 580 Support
	- Renamed NVIDIA GTX 670/680/690 Support to NVIDIA GTX 670 / 680 / 690 Support
	- Added missing description for Drivers & Bootloaders -> Drivers -> Graphics -> NVIDIA GTX 670 / 680 / 690 Support

Internal Changes:
	- Fixed Drivers & Bootloaders -> Drivers -> Graphics -> NVIDIA GTX 670 / 680 / 690 Support installation issue
	- Fixed Drivers & Bootloaders -> Drivers -> System -> Legacy USB Support installation issue
	- Fixed Drivers & Bootloaders -> Drivers -> Audio -> Realtek ALC8xx -> With DSDT installation issue
	- Fixed Drivers & Bootloaders -> Drivers -> Audio -> Realtek ALC8xx -> Without DSDT installation issue

MultiBeast 5.0.1 Released 2012-08-13

NOTE:	MultiBeast 5.0.1: Mountain Lion Edition is ONLY for OS X 10.8.x.

Internal Changes:
	- Fixed Drivers & Bootloaders -> Drivers -> Miscellaneous -> USB 3.0 - 3rd Party installation issue
	
MultiBeast 5.0.0 Released 2012-08-13

NOTE:	MultiBeast 5.0.0: Mountain Lion Edition is ONLY for OS X 10.8.x.

Visible Changes:
	- Renamed EasyBeast Install to EasyBeast Installation
	- Renamed UserDSDT Install to UserDSDT or DSDT-Free Installation
	- Renamed Drivers & Bootloaders -> Kexts & Enablers to Drivers & Bootloaders -> Drivers
	- Renamed IOUSBFamily Rollback to Legacy USB Support
	- Added Drivers & Bootloaders -> Drivers -> System
	- Moved Patched AppleIntelCPUPowerManagement to Drivers & Bootloaders -> Kexts & Enablers -> System
	- Moved AppleACPIPlatform Rollback to Drivers & Bootloaders -> Kexts & Enablers -> System
	- Moved AppleRTC Patch for CMOS Reset to Drivers & Bootloaders -> Kexts & Enablers -> System
	- Moved Legacy USB Support to Drivers & Bootloaders -> Drivers -> System
	- Renamed SSDT to SSDT Options
	- Moved SSDT Options from Customization -> Boot Options to Customization
	- Added GraphicsEnabler=No to Customization -> Boot Options
	- Added Verbose Boot to Customization -> Boot Options
	- Added OS X 10.8.0 to Drivers & Bootloaders -> Drivers -> System -> Patched AppleIntelCPUPowerManagement
	- Added NVIDIA Fermi >2GB OpenCL Patch to Drivers & Bootloaders -> Drivers -> Graphics
	- Added 10.8.0 OpenCL Patch to Drivers & Bootloaders -> Drivers -> Graphics -> NVIDIA Fermi >2GB OpenCL Patch
	- Added NVIDIA GTX 470/480/560Ti 448/570/580 Support to Drivers & Bootloaders -> Drivers -> Graphics
	- Added 10.8.0 OpenCL Enabler to Drivers & Bootloaders -> Drivers -> Graphics -> NVIDIA GTX 470/480/560Ti 448/570/580 Support
	- Added NVIDIA GTX 670/680/690 Support to Drivers & Bootloaders -> Drivers -> Graphics NVIDIA GTX 670/680/690 Support
	- Added 10.8.0 Patched GeForceGLDriver.bundle to Drivers & Bootloaders -> Drivers -> Graphics
	- Renamed Drivers & Bootloaders -> Drivers -> Realtek ALC8xx -> Patched AppleHDA to With DSDT
	- Renamed Drivers & Bootloaders -> Drivers -> Realtek ALC8xx -> Non-DSDT HDAEnabler to Without DSDT
	- Renamed Drivers & Bootloaders -> Drivers -> Miscellaneous -> USB 3.0 - NEC/Renesas and Etron to USB 3.0 - 3rd Party
	- Renamed Drivers & Bootloaders -> Drivers -> Disk -> 3rdParty SATA to 3rd Party SATA
	- Renamed Drivers & Bootloaders -> Drivers -> Disk -> 3rdParty eSATA to 3rd Party eSATA
	- Removed Drivers & Bootloaders -> Drivers -> Audio -> Realtek ALC8xx -> Unified Device Injector
	- Removed Drivers & Bootloaders -> Drivers -> Audio -> Realtek ALC8xx -> AppleHDA Rollback
	- Removed Drivers & Bootloaders -> Drivers -> Graphics -> ATI 48xx Support
	- Removed OS X 10.7.2 from Drivers & Bootloaders -> Drivers -> System -> Patched AppleIntelCPUPowerManagement
	- Removed OS X 10.7.3 from Drivers & Bootloaders -> Drivers -> System -> Patched AppleIntelCPUPowerManagement
	- Removed OS X 10.7.4 from Drivers & Bootloaders -> Drivers -> System -> Patched AppleIntelCPUPowerManagement
	- Removed OS X 10.7.4 Ivy Bridge from Drivers & Bootloaders -> Drivers -> System -> Patched AppleIntelCPUPowerManagement
	- Removed 64-bit Apple Boot Screen from Customization -> Boot Options
	- Removed 64-bit GraphicsEnabler=No from Customization -> Boot Options
	- Removed Customization -> Boot Options -> PCI Configuration Fix
	- Removed all 32-bit Boot Options from Customization -> Boot Options
	- Removed System Utilities
	- Removed Extension Migration Tool

Internal Changes:
	- Updated AppleRTC Patch for CMOS Reset for Mountain Lion
	- Updated FakeSMC to v4.2.0 r616
	- Update all FakeSMC Plugins to install in the Plugins directory inside of FakeSMC.kext
	- Updated hnak's AppleIntelE1000e Ethernet to v2.0.0
	- Updated Chimera to v1.11.1
	- Updated USB 3.0 - 3rd Party to CalDigital Driver
	- Changed Drivers & Bootloaders -> Drivers -> Realtek ALC8xx -> Without DSDT to also install appropriate patched AppleHDA
	- Replaced LegacyAppleRTC.kext with ElliottForceLegacyRTC.kext in EasyBeast
	- Fixed VoodooHDA 0.2.7.3 install to delete AppleHDA.kext
	- Removed npci=0x3000 from EasyBeast Installation kernel flags
	- Removed npci=0x3000 from UserDSDT or DSDT-Free Installation kernel flags

MultiBeast 4.6.1 Released 2012-06-25

NOTE:	MultiBeast 4.6.1: Lion Edition is ONLY for OS X 10.7.x

Internal Changes:
	- Fixed patched AppleIntelCPUPowerManagement postinstall script to delete NullCPUPowerManagement.kext.

MultiBeast 4.6.0 Released 2012-06-25

NOTE:	MultiBeast 4.6.0: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Added AppleACPIPlatform Rollback to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous
	- Added OS X 10.7.4 Ivy Bridge to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous -> Patched AppleIntelCPUPowerManagement
	- Renamed Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> ALC8xxHDA to Unified Device Injector
	- Added ALC8xxHDA to Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Unified Device Injector
	- Added ALC8xxHDA for Legacy ALC888 and ALC888b/887 to Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Unified Device Injector
	- Changed Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA -> ALC887/888b to a menu choice.
	- Renamed Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA -> ALC887/888b to ALC888b/887
	- Added v100202 Legacy to Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA -> ALC888b/887
	- Added v100302 Current to Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA -> ALC888b/887
	- Changed Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA -> ALC888 to a menu choice.
	- Added v100202 Legacy to Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA -> ALC888
	- Added v100302 Current to Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA -> ALC888
	- Renamed Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA -> ALC885/889a to ALC889a/885

Internal Changes:
	- Updated Chimera to v1.10.0

MultiBeast 4.5.2 Released 2012-05-29

NOTE:	MultiBeast 4.5.2: Lion Edition is ONLY for OS X 10.7.x.

Internal Changes:
	- Updated FakeSMC to include missing keys.
	- Fixed installation of AppleHDA Rollback.

MultiBeast 4.5.1 Released 2012-05-18

NOTE:	MultiBeast 4.5.1: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Removed flAked SpeedStepper in Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous
	- Added Patched AppleIntelCPUPowerManagement to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous
	- Added OS X 10.7.2 to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous -> Patched AppleIntelCPUPowerManagement
	- Added OS X 10.7.3 to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous -> Patched AppleIntelCPUPowerManagement
	- Added OS X 10.7.4 to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous -> Patched AppleIntelCPUPowerManagement
	
MultiBeast 4.5.0 Released 2012-05-17

NOTE:	MultiBeast 4.5.0: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Added Customization -> Boot Options -> SSDT
	- Added Core i5 to Customization -> Boot Options -> SSDT
	- Added Core i7 to Customization -> Boot Options -> SSDT
	- Added Core i5/i7 Overclocked to Customization -> Boot Options -> SSDT
	- Added netkas ATI 48xx Patch for 10.7.4 to Graphics -> ATI 48xx Support.

Internal Changes:
	- Updated ALC8xxHDA to v2.0.3 which adds Mute to ALC892 codec.
	- Updated toleda's patched AppleHDA.kext for ALC887/888b for an incorrect PathMapID.

MultiBeast 4.4.1 Released 2012-05-13

NOTE:	MultiBeast 4.4.1: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Renamed 10.7.2 / 10.7.3 Combo OpenCL Enabler to 10.7.2+ Combo OpenCL Enabler to reflect that it works with 10.7.2, 10.7.3 and 10.7.4.

Internal Changes:
	- Updated ALC8xxHDA to v2.0.2 which fixes an issue with ALC887/888b codecs.
	- Updated toleda's patched AppleHDA.kext for ALC887/888b with a corrected version.
	
MultiBeast 4.4.0 Released 2012-05-09

NOTE:	MultiBeast 4.4.0: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Added toleda's patched AppleHDA's to Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Patched AppleHDA
	- Added ALC898 to Drivers & Bootloaders -> Kexts & Enablers -> Audio -> Realtek ALC8xx -> Non-DSDT HDAEnabler.
	- Added HWMonitor Application to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous -> FakeSMC Plugins.

Internal Changes:
	- Updated Chimera to v1.9.2
	- Updated ALC8xxHDA to v2.0.1
	- Update FakeSMC to v4.2.0 rev609
	- Update FakeSMC Plugins to v4.2.0 rev609+
	- Updated hnak's AppleIntelE1000e Ethernet to v1.9.5. Changed install location to /System/Library/Extensions/IONetworkingFamily.kext/Contents/PlugIns.

MultiBeast 4.3.2 Released 2012-04-14

NOTE:	MultiBeast 4.3.2: Lion Edition is ONLY for OS X 10.7.x.

Internal Changes:
	- Removed IOUSBFamily Rollback from EasyBeast Installations.
	- Updated Chimera to v1.9.1
	- Fixed installation error with maolj's AtherosL1cEthernet. Changed install location to /System/Library/Extensions/IONetworkingFamily.kext/Contents/PlugIns.

MultiBeast 4.3.1 Released 2012-03-18

NOTE:	MultiBeast 4.3.1: Lion Edition is ONLY for OS X 10.7.x.

Internal Changes:
	- Removed 10.7.2 / 10.7.3 Combo OpenCL Enabler from EasyBeast and UserDSDT install as it breaks OpenCL support on NVIDIA non-Fermi (8xxx, 9xxx and 2xx) cards.

MultiBeast 4.3.0 Released 2012-03-12

NOTE:	MultiBeast 4.3.0: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Renamed NVIDIA GF100 Fermi Patches to NVIDIA 4xx/5xx Support
	- Renamed OpenCL Enabler 10.7.0 / 10.7.1 to 10.7.0 / 10.7.1 netkas OpenCL Enabler
	- Removed OpenCL Enabler 10.7.2
	- Added 10.7.2 / 10.7.3 Combo OpenCL Enabler. This new enabler contains the functionality from the old OpenCL Enabler plus adds cmf's OpenGL patch and MacMan's patch to add the missing NVIDIA device IDs. 
	- Renamed ATI 48xx Patches to ATI 48xx Support
	- Moved ATI 48xx Device Injector to ATI 48xx Support -> ATI 48xx Device Injector
	- Renamed all ATI 48xx Patch for 10.7.x to 10.7.x netkas ATI 48xx Patch
	- Added netkas ATI 48xx Patch for 10.7.3 to Graphics -> ATI 48xx Support
	- Added flAked SpeedStepper to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous
	- Added 10.7.0 & 10.7.1 SpeedStepper v1.2 by flAKed to flAked SpeedStepper
	- Added 10.7.2 SpeedStepper v1.2 by flAKed to flAked SpeedStepper
	- Added 10.7.3 SpeedStepper v1.2 by flAKed to flAked SpeedStepper
	- Added maolj's AtherosL1cEthernet to Drivers & Bootloaders -> Kexts & Enablers -> Network
	- Removed OSx86 Software. The programs in this choice are now available for download at http://www.tonymacx86.com/viewforum.php?f=278.

Internal Changes:
	- Updated Chimera to v1.8.0
	- Added 10.7.2 / 10.7.3 Combo OpenCL Enabler to EasyBeast and UserDSDT installs.
	- Changed npci=0x2000 to npci=0x3000 for all kernel flags.
	- Removed backup function from any script that was backing up and patching kexts.
	- Updated IntelCPUMonitor to v1.0.1 rev505

MultiBeast 4.2.1 Released 2011-12-17

NOTE:	MultiBeast 4.2.1: Lion Edition is ONLY for OS X 10.7.x.

Internal Changes:
	- Fixed invalid serial number for iMac12,1
	- Fixed invalid serial number for iMac12,2
	- Fixed invalid serial number for MacBookPro6,1

MultiBeast 4.2.0 Released 2011-12-14

NOTE:	MultiBeast 4.2.0: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Added TRIM Enabler to Drivers & Bootloaders -> Kexts & Enablers -> Disk
	- Added AppleRTC Patch for CMOS Reset to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous

Internal Changes:
	- Updated Chimera to v1.7.0
	- Updated USB 3.0 kext to v1.0.8
	- Updated FakeSMC Plugins -> AMD RADEON Plugin
	- Updated FakeSMC Plugins -> NVIDIA Plugin	
	- Added AppleRTC Patch for CMOS Reset to EasyBeast
	- Added AppleRTC Patch for CMOS Reset to UserDSDT
	- Added AppleRTC Patch for CMOS Reset to Extension Migration Tool

MultiBeast 4.1.0 Released 2011-11-09

NOTE:	MultiBeast 4.1.0: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Updated EasyBeast description to include all org.chameleon.Boot.plist options used, all file names and all installation locations.
	- Updated UserDSDT description to include all org.chameleon.Boot.plist options used, all file names and all installation locations.
	- Updated each kext description to include the exact file names and installation location.
	- Updated descriptions for Customization -> Boot Options and all sub-choices.
	- Updated description for System Utilities and removed Rebuild Caches as it is no longer relevant in Lion.
	- Replace VoodooPS2Controller and VoodooPS2TrackPad with PS/2 Keyboard/Mice and Trackpads which is 32/64-bit.
	- Added ATI 48xx Patch for 10.7.2 from netkas to Graphics
	- Added NVIDIA GF100 Fermi Patches to Graphics
	- Moved NVIDIA Fermi OpenCL Enabler 10.7.0 / 10.7.1 under NVIDIA GF100 Fermi Patches and renamed it OpenCL Enabler 10.7.0 / 10.7.1
	- Added OpenCL Enabler 10.7.2 to Graphics -> NVIDIA GF100 Fermi Patches.

Internal Changes:
	- Updated Lnx2Mac's RTL81xx Ethernet to v0.0.90.
	- Updated Realtek Gigabit Ethernet to v2.0.6 for 10.7
	- Updated Chimera to v1.6.0
	- Updated USB 3.0 kext to v1.0.7.
	- Updated 3rdParty SATA to v0.3 which adds support for Marvell 88SE9172.
	- Updated 3rdParty eSATA to v0.3 which adds support for Marvell 88SE9172.
	- Added darkwake=0 to EasyBeast and UserDSDT /Extra/org.chameleon.Boot.plist kernel flags.
	- Added UseKernelCache=Yes to EasyBeast and UserDSDT /Extra/org.chameleon.Boot.plist.
	- Added GenerateCStates=Yes and GeneratePStates=Yes to UserDSDT /Extra/org.chameleon.Boot.plist.
	- Changed EasyBeast to boot 64-bit kernel by default.
	
MultiBeast 4.0.3 Released 2011-10-17

NOTE:	MultiBeast 4.0.3: Lion Edition is ONLY for OS X 10.7.x.

Internal Changes:
	- Fixed bug in Chimera post install script.

MultiBeast 4.0.2 Released 2011-09-14

NOTE:	MultiBeast 4.0.2: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Restored USB 3.0 to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous. 

Internal Changes:
	- Fixed EasyBeast to correctly install IOUSBFamily Rollback.

MultiBeast 4.0.1 Released 2011-09-12

NOTE:	MultiBeast 4.0.1: Lion Edition is ONLY for OS X 10.7.x.

Internal Changes:
	- Fixed Extension Migration Tool to correctly add UseKernelCache=Yes to /Extra/org.chameleon.Boot.plist.

MultiBeast 4.0.0 Released 2011-09-12

NOTE:	MultiBeast 4.0.0: Lion Edition is ONLY for OS X 10.7.x.

Visible Changes:
	- Added Extension Migration Tool which copies the contents of /Extra/Extensions to /System/Library/Extensions and deletes /Extra/Extensions and /Extra/Extension.mkext. It will also add UseKernelCache=Yes to /Extra/org.chameleon.Boot.plist
	- Replaced Chimera v1.4.1 r877 with v1.5.4 r1394. This version adds GraphicsEnabler support for additional ATI and NVIDIA cards along with adding support for Intel HD 3000 GPU in Sandy Bridge CPUs. Also includes olegpronin's Facetime fix for non-RAID volumes. You need to add SkipFTFix=Yes to /Extra/org.chameleon.Boot.plist when booting from a RAID volume.
	- Added to Customization -> Boot Options -> PCI Configuration Fix. Adds npci=0x2000 to Kernel Flags in /Extra/org.chameleon.Boot.plist 	
	- Added to Customization -> Boot Options -> Use KernelCache. Adds UseKernelCache=Yes to /Extra/org.chameleon.Boot.plist 	
	- Added VoodooHDA 0.2.7.3 with prefPane to Advanced Options -> Kexts -> Audio -> VoodooHDA
	- Added NVIDIA Fermi OpenCL Enabler to Graphics. This patches GeForceGLDriver using patch info from netkas.org
	- Added ATI 48xx Patch for 10.7.0 from netkas to Graphics
	- Added ATI 48xx Patch for 10.7.1 from netkas to Graphics
	- Added Macmini5,1 smbios
	- Replaced JMicron36x SATA with 3rdParty SATA. This new kext supports ASMEDIA, JMicron and Marvell SATA controllers.
	- Replaced JMicron36x eSATA with 3rdParty eSATA. This new kext supports ASMEDIA, JMicron and Marvell SATA controllers.
	- Replaced IOPCIFamily Fix with Customization -> Boot Options -> PCI Configuration Fix.
	- Removed USB 3.0
	- Removed ATI 48xx Patch for 10.6.3
	- Removed ATI 48xx Patch for 10.6.4
	- Removed ATI 48xx Patch for 10.6.4 Graphics Update
	- Removed ATI 48xx Patch for 10.6.5
	- Removed ATI 48xx Patch for 10.6.6
	- Removed ATI 48xx Patch for 10.6.7
	- Removed ATI 48xx Patch for 10.6.8
	- Removed Kext Helper b7
	- Removed MSR Tools

Internal Changes:
	- Updated all kext installations to install to /System/Library/Extenstions instead of /Extra/Extensions
	- Installation of Chimera will rename /Extra/com.apple.Boot.plist to /Extra/org.chameleon.Boot.plist
	- Added npci=0x2000 to all kernel flags
	- Updated EasyBeast and UserDSDT to install Chimera v1.5.4 r1394
	- Updated EasyBeast to use 3rdParty SATA instead of JMircon 36x SATA.
	- Updated Kext Utility to 2.5.0b
	- Changed all boot options choices to use org.chameleon.Boot.plist

MultiBeast 3.8.0 Released 2011-07-11

Visible Changes:
	- Added to Customization -> Boot Options -> Generate CPU States. Adds GenerateCStates=Yes and GeneratePStates=Yes to /Extra/com.apple.boot.plist.
	- Added ATI 48xx Patch for 10.6.8 from netkas
	- Added to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous -> IOPCIFamily Fix
	- Changed Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous -> FakeSMC Plugins to a menu choice.
	- Added to FakeSMC Plugins -> Motherboard Plugins which only installs the motherboard plugins.
	- Added to FakeSMC Plugins -> AMD RADEON Plugin which only installs the AMD RADEON GPU plugin.
	- Added to FakeSMC Plugins -> NVIDIA Plugin which only installs the NVIDIA GPU plugin.
	- Removed Chameleon 2.0 RC5 - Prerelease; superseded by Chimera
	- Removed NVEnabler; superseded by Chimera
	
Internal Changes:
	- Updated FakeSMC to 3.1.0 Revision 493
	- Updated FakeSMC Plugins to 3.1.0 Revision 493
	- Added IOPCIFamily Fix to EasyBeast
	- Added IOPCIFamily Fix to UserDSDT

MultiBeast 3.7.3 Released 2011-06-24

Visible Changes:
	- Removed ATI 1.6.34.13; superseded by OS X 10.6.8.
	- Removed NVIDIA 256.02.05f01 from Graphics; superseded by official NVIDIA drivers available at http://www.nvidia.com/object/quadro-macosx-256.02.25f01-driver.html
	
MultiBeast 3.7.2 Released 2011-06-02

Internal Changes:
	- Fixed IOUSBFamily Rollback installation in EasyBeast.
	- Fixed IOUSBFamily Rollback installation.
	- Fixed installation of ShowAllFiles.

MultiBeast 3.7.1 Released 2011-05-28

Internal Changes:
	- Fixed Chimera v1.4.1 r877 standalone installation to install correct version
	- Fixed Chameleon 2.0 RC5 - Prerelease installation to install correct bootloader
	- Changed FakeSMC Plugins installation to delete IntelThermal as part of the install process.

MultiBeast 3.7.0 Released 2011-05-26

Visible Changes:
	- Replaced IntelThermal with IntelCPUMonitor in FakeSMC Plugins.
	- Removed Chameleon 2.0 RC5 - ATI Experimental; superseded by Chimera.
	- Removed Chameleon 2.0 RC5 - Sandy Bridge; superseded by Chimera.
	
Internal Changes:
	- Upgraded Chimera to v1.4.1 r877
	- Upgraded Chameleon 2.0 RC5 - Prerelease to trunk r877

MultiBeast 3.6.0 Released 2011-05-09

Visible Changes:
	- Added ATI 1.6.34.13 to Graphics. This is the latest complete ATI drivers from the iMac 2011 10.6.7 update that provides Radeon HD 6000 support. Backs up current drivers to ~/Desktop/ATI-Backup/.
	- Removed ATI 1.6.32.12 from Graphics.
	- Added NVIDIA 256.02.05f01 to Graphics. This is the latest complete NVIDIA drivers from the iMac 2011 10.6.7 update that provides Fermi support and is equivalent to tonymacx86 NVIDIA Update 2.0. Backs up current drivers to ~/Desktop/NVIDIA-Backup/.
	- Added iMac12,1 and iMac12,2 to System Definitions.
	- Removed iMac11,3 from System Definitions.
	- Renamed Chameleon Instant Menu to Instant Menu as it for Chimera and Chameleon.
	- Changed the boot menu Timeout in all com.apple.Boot.plists from 1 to 2.
	
Internal Changes:
	- Upgraded Chimera to v1.3.0 r760

MultiBeast 3.5.2 Released 2011-05-01

Internal Changes:
	- Upgraded Chimera to v1.1.0 r753

MultiBeast 3.5.1 Released 2011-04-29

Visible Changes:
	- Temporarily removed Marvell Yukon Ethernet due to issues in version used
	
Internal Changes:
	- Upgraded Chameleon 2.0 RC5 - Prerelease to trunk r753

MultiBeast 3.5.0 Released 2011-04-27

Visible Changes:
	- Added Chimera v1.0.0 r750 bootloader. This is MacMan's branch of Chameleon that merges Kabyl's ATI code and some of valv's Sandy Bridge code. 
	- Changed EasyBeast and UserDSDT to use the Chimera bootloader by default
	- Updated Chameleon 2.0 RC5 - Prerelease to r750
	- Added ATI 48xx Patch for 10.6.7 from netkas
	- Added Realtek Gigabit Ethernet 2.0.6 plugin
	- Added Marvell Yukon Ethernet a patched AppleYukon2 plugin that adds support for the Marvell Yukon-88E8056 and Yukon-88E8057 ethernet controllers.

Internal Changes:
	- Changed UserDSDT script to install without a DSDT for a DSDT-Free install. Notification is in /private/var/log/install.log for whether a DSDT was installed or not.
	
MultiBeast 3.4.0 Released 2011-03-23

Visible Changes:
	- Added ATI 1.6.32.12 Drivers to Graphics. These are all of the updated ATI drivers from the Mac OS X v10.6.7 Update for early 2011 MacBook Pros. This option will backup the currently installed versions to a folder on the desktop. NOTE: ATI4500Controller.kext is no longer included.
	- Added MacBookPro8,1 smbios.plist
	- Corrected description for Voodoo PS/2 Controller to Enables non-USB keyboard/mouse and is 32-bit only.
	- Added Voodoo PS/2 Trackpad to Miscellaneous. This adds trackpad support for Laptops and requires Voodoo PS/2 Controller to also be installed. 32-bit only.

Internal Changes:
	- Changed Voodoo PS/2 Controller to install in /System/Library/Extensions
	- Changed VoodooHDA installation to delete AppleHDA as part of the install.

MultiBeast 3.3.0 Released 2011-03-03

Visible Changes:
	- Replaced ElliottForceLegacyRTC with LegacyAppleRTC in EasyBeast 	
	- Updated Chameleon 2.0 RC5 - ATI Experimental to r748
	- Fixed HDAEnabler for ALC888 as it was 32-bit only, unlike the other HDAEnabler's which were 32/64-bit.
	- Renamed all HDAEnablers to include the codec it enables. So there is now HDAEnabler888, HDAEnabler888b, HDAEnabler889, HDAEnabler889a and HDAEnabler892.
	- Added to Customization -> Boot Options -> Chameleon Instant Menu. Adds Instant Menu=Yes or replaces Timeout=n in /Extra/com.apple.boot.plist 
	
MultiBeast 3.2.0 Released 2011-02-01

Visible Changes:
	- Removed AppleRTL8169Ethernet
	- Removed RealtekR1000SL
	- Replaced Realtek Gigabit Ethernet with Lnx2Mac's RealtekRTL81xx Ethernet. NOTE: When chosen it will launch Lnx2Mac's Installer at the end of the MultiBeast install.
	- Replaced Intel 82566 Family Gigabit Ethernet with hnak's AppleIntelE1000e Ethernet. This is a port of the e1000.sourceforge.net Intel Wired Ethernet for Linux driver.
	- Added Chameleon 2.0 RC5 - Sandy Bridge. This is valv's branch of Chameleon 2.0 RC5 that adds initial support for Sandy Bridge CPUs.
	- Removed ATY_Init Uakari
	- Removed ATY_Init Vervet
	- Changed description for NVEnabler to reflect that it's only used for older NVDIDIA graphics cards.
	- Replaced LegacyAppleRTC with ElliottForceLegacyRTC in EasyBeast and Miscellaneous. 	
	
MultiBeast 3.1.0 Released 2011-01-18

Visible Changes:
	- Added ATI 48xx Patch for 10.6.6 from netkas
	- Updated Chameleon 2.0 RC5 - Prerelease to RC5 r699
	- Updated Chameleon 2.0 RC5 - ATI Experimental to r700
	- Replaced fakesmc 2.5.0 with FakeSMC 3.1.0. 
	- Added to Drivers & Bootloaders -> Kexts & Enablers -> Miscellaneous -> FakeSMC Plugins. It installs the following FakeSMC plugins in /Extra/Extensions: ACPIMonitor.kext, IntelThermal.kext and SuperIOFamily.kext. Additional plugins can be found at http://www.projectosx.com/forum/index.php?showtopic=1643

Internal Changes:
	- Updated ALC8xxHDA to version 1.0.1. This version restores Green Line Out and Headphone functionality to how Legacy8xx works.
	- Added bdmesg command line tool as part of all Chameleon installs.
	
MultiBeast 3.0.3 Released 2010-12-30

Internal Changes:
	- Fixed installation of IOUSBFamily Rollback
	- Added to installation of standalone themes deleting current Theme folder

MultiBeast 3.0.2 Released 2010-12-29

Internal Changes:
	- Fixed installation of tonymacx86 theme remixed by complx
	
MultiBeast 3.0.1 Released 2010-12-29

Internal Changes:
	- Fixed all of the incorrect smbios.plist choices

MultiBeast 3.0.0 Released 2010-12-28

Visible Changes:
	- Enabled all Choices by default. Remember to NOT check the top level choice and only the specific sub-choice options. Checking the root option will most likely corrupt your installation by installing unwanted or unneeded options.
	- Restructered menus: Advanced Options is now separated into Drivers & Bootloaders and Customization
	- Updated Chameleon 2.0 RC5 - Prerelease to RC5 r668
	- Updated Chameleon 2.0 RC5 - ATI Experimental to r679
	- Updated Chameleon post install script to correctly install on a dual boot system.
	- Added tonymacx86 theme remixed by complx to Themes
	- Changed EasyBeast and UserDSDT to install tonymacx86 theme remixed by complx
	- Removed all CPU specific smbios.plist definitions.
	- Removed Chameleon 2.0 RC4 by AsereBLN 1.1.9
	- Replaced all Legacy88xHDA kexts with the new universal ALC8xxHDA kext.
	- Replace LegacyAppleRTC with ElliottForceLegacyRTC
	- Updated EasyBeast and UserDSDT to use Chameleon 2.0 RC5 r668
	- Updated EasyBeast to use ElliottForceLegacyRTC instead of LegacyAppleRTC
	- Added iMac11,2 and iMac11,3 smbios.plist
	
MultiBeast 2.6.3 Released 2010-12-17

Internal Changes:
	- Fixed Chameleon 2.0 RC5 - ATI Experimental to install the correct boot file.

MultiBeast 2.6.2 Released 2010-12-16

Internal Changes:
	- Changed all Chameleon install options to allow for downgrades.

MultiBeast 2.6.1 Released 2010-12-09

Internal Changes:
	- Rolled JMicron36xATA back to previous version.

MultiBeast 2.6.0 Released 2010-12-05

Visible Changes:
	- Updated Chameleon 2.0 RC5 - Prerelease to RC5 r651
	- Changed EasyBeast to install Chameleon 2.0 RC5 prerelease
	- Changed UserDSDT to install Chameleon 2.0 RC5 prerelease
	- Removed PC-EFI 10.6
	- Renamed Advanced Options -> Kexts -> Graphics -> PCI Root ID Fix -> For Chameleon 2.0 RC4 by AsereBLN to For Chameleon 2.0

MultiBeast 2.5.1 Released 2010-11-21

Visible Changes:
	- Added Auto-Detect CPU to Advanced Options -> smbios.plist -> iMac11,1
	- Added Auto-Detect CPU to Advanced Options -> smbios.plist -> MacPro3,1
	- Added Auto-Detect CPU to Advanced Options -> smbios.plist -> MacPro4,1
	- Added Auto-Detect CPU to Advanced Options -> smbios.plist -> MacPro5,1
	
Internal Changes:
	- Fixed all of the incorrect smbios.plist choices
	- Fixed all Mac Pro smbios.plists to have valid system-identifiers for each model serial number
	- Changed EasyBeast smbios.plist to MacPro3,1 Auto-Detect CPU
	- Changed UserDSDT smbios.plist to MacPro3,1 Auto-Detect CPU
	
MultiBeast 2.5.0 Released 2010-11-20

Visible Changes:
	- Updated Chameleon 2.0 RC5 - Prerelease to RC5 r643 for Fermi based card support 
	- Added Chameleon 2.0 RC5 - ATI Experimental in Advanced Options -> Chameleon
	- Added ATI 48xx Patch for 10.6.5 to Advanced Options -> Kexts -> Graphics -> ATI
	- Changed Advanced Options -> smbios.plist -> MacPro to a menu
 	- Moved existing MacPro4,1 smbios.plists to Advanced Options -> smbios.plist -> MacPro4,1
	- Added MacPro3,1 smbios.plists to Advanced Options -> smbios.plist -> MacPro3,1
	- Added MacPro5,1 smbios.plisst to Advanced Options -> smbios.plist -> MacPro5,1

MultiBeast 2.4.1 Released 2010-11-14

Visible Changes:
	- Replaced IOUSBFamily 10.6.2 Rollback with USB Rollback in Advanced Options -> Kexts -> Miscellaneous
	- Updated EasyBeast to use USB Rollback
	- Fixed the swapped smbios.plist for iMac Core 2 Duo and Mac Pro Quad-Core Xeon
	- Fixed Chameleon RC5 Default Theme install
	- Fixed EasyBeast to install the tonymacx86 theme

MultiBeast 2.4.0 Released 2010-11-10

Visible Changes:
	- Added i3 smbios.plist to Advanced Options -> smbios.plist -> iMac 
	- Added i3 smbios.plist to Advanced Options -> smbios.plist -> Mac Pro
	- Added USB 3.0 driver for NEC/Renesas D720200 controller in Advanced Options -> Kexts -> Miscellaneous
	- Removed VoodooHDA 0.2.70 with prefPane from Advanced Options -> Kexts -> Audio -> VoodooHDA Experimental
	- Merged VoodooHDA Official and Experimental choices in Advanced Options -> Kexts -> Audio -> as VoodooHDA
	- Clarified VoodooLabs and Project OS X branches in VoodooHDA descriptions
	- Added VoodooHDA 0.2.72 with prefPane to Advanced Options -> Kexts -> Audio -> VoodooHDA
	- Renamed JMicron36xATA to JMicron36x ATA in Advanced Options -> Kexts -> Disk -> JMicron36x (AKA GSATA)
	- Renamed JMicron36xSATA to JMicron36x SATA in Advanced Options -> Kexts -> Disk -> JMicron36x (AKA GSATA)
	- Renamed JMicron36xeSATA to JMicron36x eSATA in Advanced Options -> Kexts -> Disk -> JMicron36x (AKA GSATA)
	- Added Chameleon RC5 r594 Prerelease in Advanced Options -> Chameleon
	- Added Chameleon RC5 Default Theme in Advanced Options -> Themes
 
Internal Changes:
	- Replaced all MacPro3,1 with MacPro4,1 in Advanced Options -> smbios.plist -> Mac Pro
	- Changed in all VoodooHDA kexts VoodooHDAVerboseLevel to 0

MultiBeast 2.3.0 Released 2010-09-25

Visible Changes:
	- Modified UserDSDT to use any file ending in .aml instead of only DSDT.aml
	- Upgraded the official Realtek RTL8169 driver to the latest version, 2.0.5.
	- Added VoodooHDA 0.2.70 with prefPane to Advanced Options -> Kexts -> Audio -> VoodooHDA Experimental.
 
Internal Changes:
	- All smbios.plist choices were edited to remove all unnecessary keys and values.
	- Corrected Chameleon Theme to install the correct theme.
	- Corrected PC-EFI Theme to install the correct theme.
	- Added VoodooHDA.prefPane to Advanced Options -> Kexts -> Audio -> VoodooHDA Experimental -> VoodooHDA 0.2.61.

MultiBeast 2.2.2 Released 2010-09-14
 
Internal Changes:
	- Corrected all smbios.plist choices to install the correct smbios.plist
	
MultiBeast 2.2.1 Released 2010-09-14
 
Internal Changes:
	- Corrected all com.apple.boot.plist choices to install the correct com.apple.boot.plist
	
MultiBeast 2.2.0 Released 2010-09-12
 
Visible Changes:
	- Added ATI 48xx Patch for Snow Leopard Graphics Update 1.0
	- Renamed EasyBeast for Supported CPU to EasyBeast
	- Removed EasyBeast for Unsupported CPU
	- Removed from Advanced Options -> Optional Kernels
	- Removed ATI 5xxx Support 1.6.18.13 (8408) from Advanced Options -> Kexts -> Graphics -> ATI as it been replace by Snow Leopard Graphics Update 1.0
	- Removed ATI 4800 10.5 Rollback from Advanced Options -> Kexts -> Graphics -> ATI

Internal Changes:
	- Fixed Realtek RTL8169 Ethernet to install in correct location /System/Library/Extensions/IONetworkingFamily.kext/Contents/PlugIns 

MultiBeast 2.1.4 Released 2010-08-13
 
Visible Changes:
	- Renamed ATY_Init to ATY_Init Uakari to reflect which ATI 5xxx Frame Buffer is configured
	- Added ATY_Init Vervet which uses the Vervet Frame Buffer for 57xx cards
	- Renamed ATI 5xxx Support 1.6.18.13 to ATI 5xxx Support 1.6.18.13 (8408)
	- Removed ATI 5xxx Support 1.6.18.10 (Mac Mini Drivers)
	- Removed Verbose Options from com.apple.boot.plist
	- Added 32-bit GraphicsEnabler=No to Advanced Options -> com.apple.boot.plist
	- Added 64-bit GraphicsEnabler=No to Advanced Options -> com.apple.boot.plist

MultiBeast 2.1.3 Released 2010-08-08

Visible Changes:
	- Renamed ATI 5xxx Support to ATI 5xxx Support 1.6.18.10
	- Added ATI 5xxx Support 1.6.18.13

Internal Changes:
	- Upgraded ATY_Init to a version that includes support for ATI Radeon 5700 Series
	- Fixed ATI 5xxx Support so that it no longer installs ATY_Init
	- Added to ATI 5xxx Support 1.6.18.13 every ATI 5xxx device id from AMD Developer site

MultiBeast 2.1.2 Released 2010-08-05

Internal Changes:
	- Fixed VoodooHDA 0.2.2 to install the correct version
	- Fixed VoodooHDA 0.2.56 to install the correct version
	- Fixed VoodooHDA 0.2.61 to install the correct version

MultiBeast 2.1.1 Released 2010-07-24

Internal Changes:
	- Fixed permissions problems with HDAEnabler and VoodooHDA

MultiBeast 2.1.0 Released 2010-07-23

Visible Changes:
	- Added VoodooHDA to Advanced Options -> Kexts -> Audio
	- Added VoodooHDA Experimental to Advanced Options -> Kexts -> Audio
	- Moved VoodooHDA 0.2.1 to Advanced Options -> Kexts -> Audio -> VoodooHDA Official
	- Added VoodooHDA 0.2.2 to Advanced Options -> Kexts -> Audio -> VoodooHDA Official
	- Moved VoodooHDA 0.2.61 to Advanced Options -> Kexts -> Audio -> VoodooHDA Experimental
	- Restored VoodooHDA 0.2.56 to Advanced Options -> Kexts -> Audio -> VoodooHDA Experimental
	- Added PCI Root ID Fix to Advanced Options -> Kexts -> Graphics
	- Added Advanced Options -> Kexts -> Graphics -> Enablers
	- Moved NVEnabler from Advanced Options -> Kexts -> Graphics to Advanced Options -> Kexts -> Graphics -> Enablers
	- Moved ATY_init from Advanced Options -> Kexts -> Graphics to Advanced Options -> Kexts -> Graphics -> Enablers
	- Added Advanced Options -> Kexts -> Graphics -> ATI and moved all ATI options under it
	- Renamed ATI 48xx for 10.6.2 in Advanced Options -> Kexts -> Graphics -> ATI to ATI 4800 10.5 Rollback to better reflect what it is.
	- Renamed ATI 48xx QE Exotic Patch for 10.6.3 in Advanced Options -> Kexts -> Graphics -> ATI to ATI 48xx Patch for 10.6.3
	- Added ATI 48xx Patch for 10.6.4 in Advanced Options -> Kexts -> Graphics -> ATI
	- Added ATI 5xxx Support in Advanced Options -> Kexts -> Graphics -> ATI
	- Removed LegacyATI4800Controller in Advanced Options -> Kexts -> Graphics 
	- Added ATI 48xx Device Injector which contains every ATI 48xx device id from AMD Developer site to Advanced Options -> Kexts -> Graphics -> ATI 
	- Added Realtek Gigabit Ethernet to Advanced Options -> Kexts -> Network
	- Moved RealtekR1000SL to Advanced Options -> Kexts -> Network -> Realtek Gigabit Ethernet -> Realtek R1000SL
	- Added Realtek RTL8169 Ethernet to Advanced Options -> Kexts -> Network -> Realtek Gigabit Ethernet
	- Renamed Intel82566MM to Intel 82566 Family Gigabit Ethernet in Advanced Options -> Kexts -> Network
	- Replaced USBFamilyMOD 9.9.9 in Advanced Options -> Kexts -> Miscellaneous with IOUSBFamily 10.6.2 Rollback 
	- Removed 10.3.1 Supported Kernel from Advanced Options -> Optional Kernels as it's unnecessary with 10.6.4.
	- Added 10.4.0 Patched Kernel to Advanced Options -> Optional Kernels
	- Changed all MacPro4,1 smbios.plist's to MacPro3,1 smbios.plist
	- Renamed MacPro4,1 in Advanced Options -> smbios.plist to Mac Pro
	- Renamed iMac11,1 in Advanced Options -> smbios.plist to iMac
	- Renamed MacBookPro6,1 in Advanced Options -> smbios.plist to MacBook Pro
	
Internal Changes:
	- Changed EasyBeast Supported and Unsupported to use IOUSBFamily 10.6.2 Rollback instead of USBFamilyMOD 9.9.9
	- Updated ATY_init in Advanced Options -> Kexts -> Graphics -> Enablers to the latest version supporting ATI 5xxx.
	- Added to ATI 48xx Patch for 10.6.3 every ATI 48xx device id from AMD Developer site
	- Added to ATI 48xx Patch for 10.6.4 every ATI 48xx device id from AMD Developer site
	- Added to ATI 5xxx Support every ATI 5xxx device id from AMD Developer site


MultiBeast 2.0.5 Released 2010-07-04

Internal Changes:
	- Fixed LegacyATI4800Controller to install in /Extra/Extensions not /System/Library/Extensions
	- Fixed bug with PackageMaker forgetting downgrade option.
		
MultiBeast 2.0.4 Released 2010-06-30

Internal Changes:
	- Fixed 888b HDAEnabler to use correct layout id of 887
	- Fixed 889 HDAEnabler to use correct layout id of 889

MultiBeast 2.0.3 Released 2010-06-25

Internal Changes:
	- Fixed bug with missing scripts in HDAEnabler.
		
MultiBeast 2.0.2 Released 2010-06-19

Internal Changes:
	- Fixed bug with PackageMaker forgetting downgrade option.
	
MultiBeast 2.0.1 Released 2010-06-18

Visible Changes:	
	- Replaced USBFamilyMOD 2.0 with USBFamilyMOD 9.9.9 in Advanced Options -> Kexts -> Miscellaneous.
	- Fixed System Utilities -> Rebuild Caches to not create /System/Library/Extensions.mkext 
	- Fixed UserDSDT to automatically create /Extra/Extensions.mkext
	- Fixed UserDSDT where it wasn't installing smbios.plist, com.apple.boot.plist and CHameleon theme
	
Internal Changes:
	- Fixed bug in UserDSDT
	
MultiBeast 2.0.0 Released 2010-06-04

Visible Changes:
	- Added software license agreement.
	- Removed GigaBeast. The functionality of what GigaBeast provided can be duplicated by using UserDSDT with a DSDT for your motherboard from the DSDT Database at http://tonymacx86.blogspot.com/2009/12/dsdt-database-for-p55-motherboards.html or using EasyBeast.
	- Disabled the ability to install all choices in EasyBeast, Advanced Options and most choices within Advanced Options. The end result is these choices are now gray instead of black, forcing you to choose a sub choice or choices within.
	- Improved Chameleon RC4 compatibility with multiple Operating Systems, i.e., dual and triple booting. 
	- Changed installation of Chameleon 2.0 RC4 by AsereBLN and PC-EFI 10.6 by netkas to hide /boot. 
	- Replaced IOUSBFamily 10.6.2 with USBFamilyMOD 2.0 in Advanced Options -> Kexts -> Miscellaneous.
	- Renamed AppleHDA 10.6.2 to AppleHDA 10.6.2 Rollback in Advanced Options -> Kexts -> Audio
	- Replaced VoodooHDA 0.2.56 with VoodooHDA 0.2.61
	- Renamed Patched Kernels to Optional Kernels in Advanced Options
	- Added 10.3.1 Supported Kernel to Advanced Options -> Optional Kernels. This kernel supports additional Core i CPU's. For current list of supported CPU's check http://tonymacx86.blogspot.com/2010/05/iboot-supported-with-vanilla-kernel-for.html
	- Changed Advanced Options -> smbios.plist -> MacPro4,1 to a menu
	- Added MacPro4,1 Quad-Core Xeon smbios.plist to Advanced Options -> smbios.plist -> MacPro4,1
	- Added MacPro4,1 i5 smbios.plist to Advanced Options -> smbios.plist -> MacPro4,1
	- Added MacPro4,1 i7 smbios.plist to Advanced Options -> smbios.plist -> MacPro4,1
	- Added iMac11,1 Core 2 Duo smbios.plist to Advanced Options -> smbios.plist -> iMac11,1
	- Added MacBookPro6,1 smbios.plist to Advanced Options -> smbios.plist
	- Disabled verbose boot for EasyBeast and UserDSDT installs. To enable at boot time, type -v at the Chameleon prompt. 
	- Changed default com.apple.boot.plist in EasyBeast and UserDSDT installs to 32-bit Apple Boot Screen. Install Advanced Options -> com.apple.boot.plist -> 64-bit Verbose to restore to MultiBeast 1.1.1 behavior.
	- Changed default smbios.plist for EasyBeast and UserDSDT installs to iMac11,1 with no SMcputype. Install Advanced Options -> smbios.plist -> iMac11,1 -> Core i5 to restore to MultiBeast 1.1.1 behavior.
	
Internal Changes:
	- Improved 10.6.3 compatibility in EasyBeast Supported and Unsupported by including USBFamilyMOD 2.0 by default
	- Improved 10.6.3 compatibility in Legacy888HDA, Legacy888bHDA and Legacy889HDA by including 10.6.2 AppleHDA.kext by default
	- Moved GraphicsEnabler=Yes from Kernel Flags to a stand alone key in all standalone com.apple.Boot.plist and in EasyBeast and UserDSDT com.apple.Boot.plist

MultiBeast 1.1.1 Released 2010-05-21
	-Fixed bug with 10.6.2 AppleHDA.kext downgrade option.
	-Fixed bug with 10.6.2 IOUSBFamily downgrade option
	-Added allow downgrade to VoodooHDA 0.2.1 and Vood00 0.2.56

MultiBeast 1.1.0 Released 2010-04-30
	- Updated Gigabyte GA-P55M-UD2 DSDT
	- Updated Gigabyte GA-P55M-UD4 DSDT
	- Added Gigabyte GA-P55A-UD7 to GigaBeast
	- Corrected wrong LegacyHDA in GigaBeast for numerous boards
	- Changed LegacyHDA to the new tonymacx86 Legacy88xHDA versions. 
	- Corrected version of VoodooHDA 2.5.6 to VoodooHDA 0.2.56
	- Corrected version of VoodooHDA to VoodooHDA 0.2.1
	- Changed choice Disk Utilities to System Utilities.
	- Added tooltips on most install choices
	- Reworked descriptions and documentation
	- GigaBeast supported motherboards and BIOS:
		GA-P55-UD3-F7
		GA-P55-UD3P-F7
		GA-P55-UD3R-F6
		GA-P55-UD4-F7
		GA-P55-UD4P-F8
		GA-P55-UD5-F8
		GA-P55-UD6-F8
		GA-P55-US3L-F5
		GA-P55-USB3-F4
		GA-P55A-UD3-F6
		GA-P55A-UD3P-F8
		GA-P55A-UD3R-F7
		GA-P55A-UD4-F9
		GA-P55A-UD4P-F8
		GA-P55A-UD5-F5
		GA-P55A-UD6-F8
		GA-P55A-UD7-F4
		GA-P55M-UD2-F8
		GA-P55M-UD4-F8

MultiBeast 1.0.2 Released 2010-04-23
	-Fixed bug with 10.6.2 IOUSBFamily downgrade option
	-Edited description of VoodooHDA.kext - installs to System/Library/Extensions

MultiBeast 1.0.1 Released 2010-04-17
	-Fixed bug with 10.6.2 AppleHDA.kext downgrade option.

MultiBeast 1.0.0 Released 2010-04-12
	-Initial Release
	

	
