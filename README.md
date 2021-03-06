# Silo
Simple server resource panel in PHP. Monitor load, disk and memory usage with custom alert limits set within Silo. Receive email and SMS alerts when you go over these set limits.

## Features
* Clean and responsive
* Show disk, memory and load usage
* Auto updating front-end
* Email and SMS alerts
* Configure all settings on the web interface
* Create daily logfiles
* No database needed

## Requirements
* PHP 5.5+
* VPS/Dedicated server recommended. Not made for shared hosting environments.
* Git (recommended)

## Installation
1. Browse to your desired install directory
1. Execute git clone https://github.com/ialexpw/Silo.git
1. Ensure the /resources/data directory is writable
1. Set up a cronjob to /resources/cron.php every 5 minutes
1. Log in to the web interface with the default password "password"
1. Good to go!

## Updating Silo
Silo has a built-in updater from the web interface. From the "Control" tab you can choose to update with your SSH credentials. If you would like to do this directly from the command line instead, you just have to execute a git pull from where you installed Silo.

## Demo
You can see the frontend by going to https://silo.one - to see the configuration screens, refer to the screenshots.

## Screenshots
![Drives](https://silo.one/i/Drives.png "Configure Drives")
![Contacts](https://silo.one/i/Contacts.png "Configure Contacts")
![Limits](https://silo.one/i/Limits.png "Configure Limits")
![Password](https://silo.one/i/Password.png "Change Password")
![SSH Control](https://silo.one/i/Control.png "SSH Control")
![Site Settings](https://silo.one/i/Site.png "Configure Settings")

## Licence
MIT License - Please view the LICENSE file.
