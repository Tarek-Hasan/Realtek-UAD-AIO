## Realtek UAD Driver AIO Pack
This package is meant to be all in one installer of Realtek Universal Audio Driver (UAD) for all OEM with all software components. It's just a repack of UAD driver provided on Microsoft Update Catalog to be manually installable.


### Compatibility
This Realtek UAD Driver AIO Pack should install and function properly on all systems with Realtek audio controller released in 2018 or later. For Realtek Legacy HDA FF00 drivers, use this mod - [Realtek Generic UAD](https://github.com/pal1000/Realtek-UAD-generic). If not sure about your audio IC generation, try to install this driver package first. This installer will let you know if a device is not supported.

[Note: If Realtek Generic UAD used with devices relying on special audio enhancements; functionality and feature set available may be limited.]


### Installation
- First disconnect the device from internet.

- Uninstall previous driver using one of the following methods.

  1. DDU (Display Driver Uninstaller) Method:
     - Run [DDU](https://www.guru3d.com/files-details/display-driver-uninstaller-download.html)
     - Follow its instructions.

  2. Manual Method (For advanced users):
     - If there is a Realtek Audio Driver entry in Settings->Apps, uninstall it and reboot.
     - Be sure to remove any and all residues from previous Realtek audio drivers. Run [Driver Store Explorer](https://github.com/lostindark/DriverStoreExplorer/releases), then remove any drivers whose *Provider* is "Realtek", "Dolby", "DTS", "Creative", "A-Volute" etc. in the "Sound, Video and Game Controllers", "Extensions", "Software Components" and "Audio Processing Objects" device categories.
     - Reboot your system.

- [Download](releases/latest) and install "Realtek UAD Driver AIO Pack".
- Reboot your system. An Audio Control app will automatically install via Microsoft Store.


### Project motivation
Microsoft's notorious update system doesn't update driver outside of first install. Even than usually offer one or two years old driver. Newer driver updates may be listed in optional update. Also, installing newer driver through Windows update installs them on older driver without removing. This package is an effort to provide people a clean driver install.


### Component Sources

- The [MSI Realtek audio package](https://download.msi.com/dvr_exe/mb/realtek_audio_R.zip) that this pack is based on contains the official Realtek UAD installer.
- Search on Microsoft Update Catalog for latest codec components.
  - [All OEM driver](https://www.catalog.update.microsoft.com/Search.aspx?q=Realtek%20Media%202023)
  - [Realtek AudioProcessingObject](https://www.catalog.update.microsoft.com/Search.aspx?q=Realtek%20AudioProcessingObject)
  - [Realtek SoftwareComponent](https://www.catalog.update.microsoft.com/Search.aspx?q=Realtek%20SoftwareComponent%202023)
  - DTS Core [APO](https://www.catalog.update.microsoft.com/Search.aspx?q=DTS%20AudioProcessingObject)/[SWC](https://www.catalog.update.microsoft.com/Search.aspx?q=DTS%20SoftwareComponent)
  - Creative [APO](https://www.catalog.update.microsoft.com/Search.aspx?q=Creative%20AudioProcessingObject)/[SWC](https://www.catalog.update.microsoft.com/Search.aspx?q=Creative%20SoftwareComponent)
  - Nahimic [APO](https://www.catalog.update.microsoft.com/Search.aspx?q=A-Volute%20AudioProcessingObject)/[SWC](https://www.catalog.update.microsoft.com/Search.aspx?q=A-Volute%20SoftwareComponent)
- Following third-party software components are not included in the package. You can download and install them, if you think you need them.
  - [Intel SST](https://www.catalog.update.microsoft.com/Search.aspx?q=intel%20media%202023)
  - Waves MaxxAudio, Cirrus logic, Fortemedia, Elevoc


### Credits
This project gathered info and used help from [pal1000](https://github.com/pal1000), [Station-Drivers](https://ftp.station-drivers.com/index.php/en-us/forum/realtek-hda-uad-drivers-firmwares-utilities/24-realtek-hda-uad-component-drivers), [MDL](https://forums.mydigitallife.net/threads/update-realtek-high-definition-audio.72236/) and Tenforums etc.
