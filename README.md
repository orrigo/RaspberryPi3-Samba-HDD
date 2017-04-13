# RaspberryPi3-Samba-HDD
Install on RaspberryPi3 Samba and HDD

First of all, make sure that Git is installed:

sudo apt-get update
sudo apt-get install -y git dialog

* Run: sudo git clone https://github.com/Dorha85/RaspberryPi3-Samba-HDD.git

* Run: cd RaspberryPi3-Samba-HDD && sudo chmod +x install.sh && sudo ./install.sh

* Confirm that you are happy for changes to be made.

This should automatically set everything up and leave you ready to go

Notes and configuration

To delete installed folder: sudo rm -r RaspberryPi3-Samba-HDD

To change default WiFi channel: sudo nano /etc/hostapd/hostapd.conf accordingly

To change wifi password: sudo nano /etc/hostapd/hostapd.conf

This setup has been tested on a fresh install of raspbian.

If set up on an existing install then any current config files will be backed up with the extension ".old" in the relevant folders prior to installation (this allows returning to original network settings if required)
