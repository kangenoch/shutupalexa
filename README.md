# shutupalexa (Shut Up Alexa!)
A simple MacOS script that disables "NOW CONNECTED TO $$$$$$$!" from Amazon Echo devices

# Intro
I was freaking tired of hearing "NOW CONNECTED to @#$#$ MacBook" from my Alexa Echo.
Searching for the possible solution for years, but (OF COURSE) Amazon dev didn't fix this simple stuff.
And I found an article(Still finding the original article): Alexa will check the Bluetooth connection every 10 mins.
One user made a Linux script transferring sin waves every 9mins, so Alexa devices are still get connected.
But the code for Linux, and I rewrote the concept for the MacOS.

# How to Use
- Download the com.local.playtone.plist
- Copy the file to ~/Library/LaunchAgents
- Run sudo launchctl load ~/Library/LaunchAgents/com.local.playtone.plist
