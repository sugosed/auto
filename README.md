# Install Ajenti Control Panel on Ubuntu 22.04|20.04

# Update System

sudo apt update && sudo apt dist-upgrade -y

If the upgrade is completed reboot the system before initiating installation of Ajenti.

[ -e /var/run/reboot-required ] && sudo reboot

# Install Ajenti Control Panel

curl -o ajenti_install.sh https://raw.githubusercontent.com/ajenti/ajenti/master/scripts/install.sh

# Run the installer script with sudo command.

sudo bash ./ajenti_install.sh

# Open Ajenti Web Console on browser

Open your server IP address or hostname on port 8000 from your browser – https://ServerIP_Hostname:8000

# For restart

sudo systemctl restart ajenti

# THANK YOU. 
