# shutupalexa (Shut Up Alexa!)
A simple MacOS script that disables "NOW CONNECTED TO $$$$$$$!" from Amazon Echo devices

# Intro (Still Angry)
I was freaking tired of hearing "NOW CONNECTED to @#$#$ MacBook" from my Alexa Echo.
Searched for a possible solution for years, but (OF COURSE) Amazon dev didn't fix this simple stuff.
...
I found an article(Still finding the original): Alexa will check the Bluetooth connection every 10 mins.
One user made a Linux script transferring sin waves every 9 minutes, so Alexa devices are still connected.
But the code was for Linux, and I rewrote the concept for the MacOS.

# How to Use
- Download the com.local.playtone.plist
- Copy the file to ~/Library/LaunchAgents
- Run sudo launchctl load ~/Library/LaunchAgents/com.local.playtone.plist (for autorun)
