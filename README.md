# DebDroid DE Installer
An Easy to use DE Installer for DebDroid. \
This is more of a Wrapper scripts. but gives a shortcuts and installs it to termux 

Issues are disabled here so make an issue on the main DebDroid repository instead

# Installation
You will need: 
* `curl` package
* `debdroid` (kinda duh)

Download an Install the installer scripts:
* [XFCE](https://raw.githubusercontent.com/WMCB-Tech/debdroid-de-installer/main/installer/setup-debdroid-xfce)
* [LXDE](https://raw.githubusercontent.com/WMCB-Tech/debdroid-de-installer/main/installer/setup-debdroid-lxde)
* [MATE](https://raw.githubusercontent.com/WMCB-Tech/debdroid-de-installer/main/installer/setup-debdroid-mate)
* [LXQT](https://raw.githubusercontent.com/WMCB-Tech/debdroid-de-installer/main/installer/setup-debdroid-lxqt)

Once you downloaded it. don't forget to chmod it: \
`chmod +x setup-debdroid-x`

And execute it.

# Starting
After Installation. you can type some commands:
* XFCE - `startxfce`
* MATE - `mate-session`
* LXDE - `startlxde`
* LXQT - `startlxqt`

# Uninstalling
To uninstall it. simply remove the wrapper scripts and you're done

# Common Problems
If you encountered this error:
```
Another Instance of VNC Server running at port 5951. Please Close it
```

Simply close it by typing: \
`killall Xvnc`
