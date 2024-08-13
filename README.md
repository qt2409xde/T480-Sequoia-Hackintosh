# T480-Sequoia-Hackintosh
This is my EFI which used to properly boot and run macOS Sequoia

# 🛠 Specs:

| Category         | Component                            |
| -----------------| ------------------------------------ |
| CPU              | Intel Core i5-8350U                  |
| GPU              | Intel UHD Graphics 620               |
| SSD              | PNY CS1031 M.2 NVMe Gen3x4 SSD       |
| Memory           | 16GB DDR4 2400Mhz                    |
| WiFi & Bluetooth | Intel Wireless-AC 8265               |

# ✔ These are the things you need
- An Internet connection
- A 16GB or larger USB Drive

# 💻 Prepare BIOS
The BIOS settings must be the same as these before installing macOS
In Security menu, set the following settings:

-  `Security > Security Chip`: must be **Disabled**
-  `Memory Protection > Execution Prevention`: must be **Enabled**
-  `Virtualization > Intel Virtualization Technology`: must be **Enabled**
-  `Virtualization > Intel VT-d Feature`: must be **Enabled**
-  `Anti-Theft > Computrace -> Current Setting`: must be **Disabled**
-  `Secure Boot > Secure Boot`: must be **Disabled**
-  `Intel SGX -> Intel SGX Control`: must be **Disabled**
-  `Device Guard`: must be **Disabled**

In Startup menu, set the following options:

-  `UEFI/Legacy Boot`: **UEFI Only**
-  `CSM Support`: **No**

In Thunderbolt menu, set the following options:

-  `Thunderbolt BIOS Assist Mode`: **UEFI Only**
-  `Wake by Thunderbolt(TM) 3`: **No**
-  `Security Level`: **No**
-  `Support in Pre Boot Environment > Thunderbolt(TM) device`: **No**
