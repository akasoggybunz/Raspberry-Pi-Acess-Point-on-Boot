# Raspberry Pi Acess Point on Boot (AP Pi)
An open source script for booting a Raspberry Pi as an Access Point (First Boot Only), this will then allow the pi to accept Networks. 

# Goal
Basically I want to automate this tutorial https://learn.sparkfun.com/tutorials/headless-raspberry-pi-setup?_ga=2.135901425.1537017692.1544828618-1909400911.1544202760 For end users not having to plug the pi into an ethernet, ssh, or change the config file with wifi credentials. 

The user story for this project is to let a user select network settings and give credentials to a raspberry pi using their cellphone. Basically if you have a raspberry pi project that you give to end user's, and that project requires network. This script's purpose is to make the configuration of the network as easy as possible for the end user, via headless.

# Note:
I am not even sure this will work. I have created this repository to try and attempt this. My intitial thought is to get this working with a fresh boot of rasbian. I know there are methods of getting network credentials to a rasp-pi, just want to allow a user to do it this way.



# Resources for Dev:
- https://raspberrypi.stackexchange.com/questions/26979/headless-wifi-configuration-ap-mode
- https://github.com/sabhiram/raspberry-wifi-conf
- https://github.com/balena-io/wifi-connect   This project is really close to what I am looking for, but requires SSH.  
- https://www.raspberrypi.org/forums/viewtopic.php?t=138721 Raspi-config.sh uses First-boot_activity method. This could be the method to achieve this headless. 
- https://elinux.org/RPi_raspi-config#First-boot_activity First boot
