# dwm-desktop
My configuration files for dwm on desktop.

There are configuration files for dwm and dwmblocks. There is also a binding for slock, but it's up to you to download the config file from them, as every user enters their user and group on their system for that. Most of the default dwm bindings are kept the same, other than quitting dwm (**alt + shift + q**). The MOD key is **alt**, as my Packard Bell keyboard does not have a Windows key.

Additionally, there are bindings for other functions not included with dwm by default for both standard XKeys and X86Keys. X86Keys being your non-standard icon keys for volume, brightness, etc.

Here are the additional bindings:
 - dmenu = **alt + return**
 - qterminal = **alt + /**
 - quit program = **alt + q**
 - quit dwm = **alt + shift + q** (be very careful not to confuse this with *quit program*
 - lock screen (dependent on slock) = **alt + shift + l**
 - volume up = **alt + shift + F12** *or* **AudioRaiseVolume** on its own
 - volume down = **alt + shift + F11** *or* **AudioLowerVolume** on its own
 - print screen = **alt + shift + F10** *or* **Print Screen** on its own

## Dependencies
You will need to install the following packages (or change config.def.h to use a different font & terminal):
alacritty
ttf-liberation
