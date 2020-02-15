# Ubuntu Setup for Python using Virtual Box

## Dependencies:
* VirtualBox 6.1.2 at https://www.virtualbox.org/wiki/Downloads
* VirtualBox Guest Additions at http://download.virtualbox.org/virtualbox/6.1.2/
* Ubuntu Linux 18.04.4 LTS https://ubuntu.com/download/desktop
* Python 3.x

## Procedures
1. Download VirtualBox
2. Download VirtualBox Guest Additions
3. Download Ubuntu Linux
4. Install VirtualBox
5. Install Ubuntu Linux
6. Install VirtualBox Guest Additions
** Right click the mounted CD image and open a terminal
** Type `sudo sh ./VBoxLinuxAdditions.run`
7. Install Python 3.x

## Troubleshooting
#### You may need to install gcc build tools:
Open a terminal and type `sudo apt-get install build-essential gcc make perl dkms`

#### Check if Python 3 is installed.
Open a terminal and type `python3 --version`
