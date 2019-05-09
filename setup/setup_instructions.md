### INSTALL INSTRUCTIONS FOR HASS.IO ###

# Pre-req
#       - Create Duck DNS account and setup domain (https://www.duckdns.org)
#       - Configure git repo (populate with default config or init via ssh if required first)
#       - Google drive account to store backups


# Set password on logon 
# Change hostname

# Take Initial Snapshot

# Install Duck DNS
#       - Configure accept_terms to true
#       - configure domains & token based on DuckDNS account in pre-req
#       - Start

# Install Samba Share
#       - Change username & password
#       - Start

# Install Git pull
#       - Change git branch
#       - Configure git repository
#       - Configure auto restart
#       - Configure repeat
#       - Add deployment key
#       - Start to pull config (this will wipe your config!)
#       - Copy secrets file
#       - Restart and reconfigure user account 

# Install InfluxDB
#       - Enable show in sidebar
#       - Start

# Install Glances
#       - Enable show in sidebar
#       - Change username & password
#       - Log into InfluxDB and create database
#       - Configure InfluxDB settings
#       - Start

# Install SSH & Web Terminal
#       - Enable show in sidebar
#       - Change username & password
#       - Start

# Install Grafana
#       - Start
#       - Configure as required

# Google backup
#       - Add additional repo to add-on store (https://github.com/samccauley/hassio-repository)
#       - Install "Backup Hassio to Google Drive" add-on
#       - Create folder in google drive, navigate to folder and pull the folder ID
#       - Configure the add-on with folder ID and relevent information
#       - Start add-on
#       - Browse to add-on URL based on the port configured on the app (http://xxx:8055/gb)
#       - Sign into Google Account to authorise
#       - Copy authentication code and authorise in the app
#       - Remove exposed network port in add-on and restart add-on



