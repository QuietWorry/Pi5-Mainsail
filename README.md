# Pi5-Mainsail
Simple Guide to setting up Mainsail OS on a Raspberry Pi 5 using RPI and Kiauh via SSH

1. Flash SD with Raspbery Pi OS Lite
  1.1 Install and open officail Raspberry Pi Imager (https://www.raspberrypi.com/software/)
  1.2 Select:
   - Device > Raspberry Pi 5
   - OS > Raspberry Pi OS (other)
   - Raspberry Pi OS Lite (64-bit)
  1.3 Customize settings and flash firmware
   - Click "Next" on RPI
   - Click "Edit Settings"
   - Enable "Set hostname" and change hostname as desired
   - Set Username and password
   - If using WiFi: Enable and set SSID and Password for your network, then select correct country
   - Enable and set locale settings
   - Navigate to "Services" tab and enable SSH with password authentication (or pub-key authentication)
   - Click "Save" at the bottom
   - Click "yes" to apply OS customisation settings
   - Click "yes" to erase all data on SD if prompted
   - Wait for OS to write and verify
   - Safely remove SD and install on Pi 5
2. 
