Pi5-Mainsail

Simple Guide to setting up Mainsail OS on a Raspberry Pi 5 using RPI and Kiauh via SSH
1. Flash SD with Raspberry Pi OS Lite
a. Install and open official Raspberry Pi Imager

    Raspberry Pi Imager

b. Select:

    Device: Raspberry Pi 5
    OS: Raspberry Pi OS (other) > Raspberry Pi OS Lite (64-bit)
    Storage: [YOUR_SD_CARD_NAME]

c. Customize settings and flash firmware

    Click "Next" on RPI Imager
    Click "Edit Settings"
    Enable "Set hostname" and change hostname as desired
    Set Username and password
    If using WiFi: Enable and set SSID and Password for your network, then select correct country
    Enable and set locale settings
    Navigate to "Services" tab and enable SSH with password authentication (or pub-key authentication)
    Click "Save" at the bottom
    Click "yes" to apply OS customization settings
    Click "yes" to erase all data on SD if prompted
    Wait for OS to write and verify
    Safely remove SD and install on Pi 5
