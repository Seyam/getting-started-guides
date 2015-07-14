# Set up Flash Tool Lite for Linux

This document explains the installation procedure Flash Tool Lite for Linux. The tool is used to flash the firmware on Intel® Edison boards, but will expand to other IoT products in the future.

**Installation**

The Linux installation set up is only for 64 bit operating system. The versions supported are Ubuntu 12.04 LTS 64 bit and above.

1. Install dependent packages for the tool.

   * Ubuntu 12.04LTS:
   ``` 
   sudo apt-get install gdebi ia32-libs
   ``` 
   * Ubuntu 13.04 64bits and later:
   ``` 
   sudo apt-get install gdebi libncurses5:i386 libstdc++6:i386
   ``` 
2. Copy the phoneflashtoollite_5.2.4.0_linux_x86_64.deb from your USB drive in downloads -> Linux folder to your home directory.
3. Complete the installation either through terminal or Ubunutu software center.
   * From Ubuntu Terminal:
   ``` 
   sudo gdebi <name_of_flash_tool_lite.deb>
   ```
     
   * From Software Center:
  
   The **Ubuntu Software Center** will handle the installation, double-click on the .deb file and then click **Install Package** and enter the password. The IPL license must be accepted.
  
**Next Steps**

  * [Update firmware using the tool »](/flash_firmware/update_firmware.md)
