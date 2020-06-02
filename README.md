# Jailm8

Formerly Bootm8

An even better iso that lets users jb with checkra1n

This project started off when I decided to make my own version of checkn1x, which also supported project sandcastle

So that got me thinking, I could do this myself, I dont need someone else doing the hard work

Plus quarantine got me bored

How to use:

1. Download rufus or any other live usb maker

2. Write the latest iso to a usb,this usb can be reused afterwards

3. Boot onto the usb from your computers BIOS

4. You should eventually get to checkra1n


Now this step changes depending on what you are trying to do:

-To run checkra1n normally continue

-To run project sandcastle:

Go into "options"

In the boot arguements box type "-p"

Continue with the jailbreak process

Now your device should boot into whats called PongoOS

Now quit checkra1n

Again this step splits depending on what you wish to do"

-To boot Android, type:

"android"


-To boot Linux, (guess):

"linux"


To use irecovery commands, type "irecovery -h" to print the list of commands

To get your phone out of recovery mode, type "irecovery -n"


I am open to any additions, as this is no longer just a checkra1n bootable iso, it is now a tool for more, and I want to add even more functionality to it, so if you have any ideas or suggestions just add an issue, I really want to make a muilti-purpose tool for both amateurs and developers (I don't see why but ¯\_(ツ)_/¯)


List of extras:

Project sandcastle Android

Project sandcastle linux

Irecovery

chimera1n (still in very early beta, coming soon, if it works out)



If you are curious about the chimera1n scripts, I have split coolstar's script into 2 parts, chimera1n and chimera1n.sh, so that it works without the host os, in this case jailm8, needing a WiFi connection, in the last release, I also added an ssh option, which should let you ssh into your device with a usb cable. The actual changes I made to the script were that it would ssh to the device and download the files and run the commands on device, which would bootstrap it with chimera1n. It also uses wget instead of curl, and uses ssh instead of iproxy

Sorry for the bad formatting, I am not used to using GitHub like this, but hopefully it is easy to understand

NOTE: etcher will not work when writing the iso

Thanks to the checkra1n team for checkra1n

Thanks to asineth0 for inspiration and teaching me(without knowing) about squashfs and linux terminal commands
