# WPAcrack
WPA Wi-Fi cracker

# Description 
This script tries to crack a WPA2 Wi-Fi system. It works by monitoring the traffic in the air and capturing the handshake of the WPA2.
Then it tries a dictionary attack offline.
The attack is based on this [blog](https://null-byte.wonderhowto.com/how-to/hack-wi-fi-cracking-wpa2-psk-passwords-using-aircrack-ng-0148366/).

# Usage
./WPAcrack wireless_interface wireless_network dictionary
wireless_interface - the local network interface through which the monitoring will occur
wireless_network - the target network to crack
dictionary - the dictionary of passwords to try

# Disclaimer
This project has been posted purely for educational purposes. Please don't use it with any malicious intents.
