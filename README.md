## 

A fork of Boatswain that attempts to fix major issues 

[<img width='240' alt='Download on Flathub' src='https://flathub.org/assets/badges/flathub-badge-en.png' />](https://flathub.org/apps/details/com.feaneron.Boatswain)

## Fixed Issues
- Updated the gnome runtime to 44
- Completely removed the Launcher plugin which was broken with boatswains migration to flatpak
- added the users home dir access to the flatpak for simpler addition of soundboard files and custom icons


## Requirements
- Udev v252


## Testing without devices

Boatswain-plus is built to allow emulating an arbitrary number of devices. This might be helpful
to troubleshoot for a friend. To force Boatswain to use launch it as follows:

```
$ env BOATSWAIN_EMULATE_DEVICES=1 flatpak run 
```

You can have multiple fake devices by setting the `BOATSWAIN_N_DEVICES` variable
to a number.
