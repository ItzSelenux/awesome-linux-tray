# Awesome Linux Tray

This list showcases programs that act like bar plugins. However, since they are simple tray applications, they are quite universal.

## Why?

For users of KDE, Gnome, or even Xfce, this may seem unnecessary because these environments usually allow the installation of panel plugins. However, those plugins only work on their respective panels. For users of more obscure DEs/WMs like IceWM, i3WM, Hyprland, Wayfire, etc., or other panels like Tint2, Waybar, NWG Panel, etc., the closest equivalent to a "plugin" is to program a manual script or use a program that runs in the tray.

## Rules
- The programs need to focus their functionality on the tray, with at most a main window
- The programs have to use fairly modern libraries (e.g., GTK2, Python2, or Qt4 are excluded)
- The programs need to have a last commit of three years or less

# List

## Hardware Indicators

### Battery
![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/valr/cbatticon"> Cbatticon</a> : A lightweight and fast battery icon that sits in your system tray

### Keyboard
![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/ItzSelenux/gxcapindicator"> GXCapIndicator</a> : Simple and universal Cap/Num lock key indicator for x11 tray

![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/zen-tools/gxkb"> gxkb</a> : X11 keyboard indicator and switcher

### Volume
![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/christophgysin/pasystray"> PaSysTray</a> : PulseAudio system tray

![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/Maato/volumeicon"> VolumeIcon</a> : A lightweight volume control that sits in your systray

### PCI/USB Devices:

![Vala](https://img.shields.io/badge/-6d5f92?style=flat-square&logo=vala&logoColor=white)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/Junker/MicTray
">Mictray</a> : Control the microphone state and volume from system tray.

![C++](https://img.shields.io/badge/-5e97d0?style=flat-square&logo=c%2B%2B&logoColor=fff)
![Qt5](https://img.shields.io/badge/Qt5-41CD52?style=flat-square&logo=qt&logoColor=fff)
<a href="https://github.com/Shatur/optimus-manager-qt">Optimus Manager Qt	</a> : Configure and switch GPUs on Optimus laptops using the tray menu.

## Software Indicators

### Networking

![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/jgke/connman-gtk"> ConnMan GTK</a> : ConnMan GTK GUI (unmaintained)

![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://gitlab.gnome.org/GNOME/network-manager-applet">Network Manager Applet</a> : Tray applet and an advanced network connection editor

![C++](https://img.shields.io/badge/-5e97d0?style=flat-square&logo=c%2B%2B&logoColor=fff)
![Qt5](https://img.shields.io/badge/Qt5-41CD52?style=flat-square&logo=qt&logoColor=fff)
<a href="https://github.com/palinek/nm-tray">nm-tray</a> : NetworkManager tray icon -> simple front end

## Miscellaneous

### Manage an external program

![C++](https://img.shields.io/badge/-5e97d0?style=flat-square&logo=c%2B%2B&logoColor=fff)
![Qt5](https://img.shields.io/badge/Qt5-41CD52?style=flat-square&logo=qt&logoColor=fff)
<a href="https://github.com/gyunaev/birdtray"> Birdtray</a>
: System tray notification for new mail for Thunderbird

![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/tsmetana/spotify-tray"> Spotify Tray</a>
: Adds a tray icon to the Spotify Linux client application

### Panel/Bar utils
![C++](https://img.shields.io/badge/-5e97d0?style=flat-square&logo=c%2B%2B&logoColor=fff)
![Qt5](https://img.shields.io/badge/Qt5-41CD52?style=flat-square&logo=qt&logoColor=fff)
<a href="https://github.com/user-none/KDocker"> Kdocker</a>
: Docks other application software into the system tray

![Haskell](https://img.shields.io/badge/-5b4e7e?style=flat-square&logo=haskell&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/mbt/alltray"> gtk-sni-tray</a>
: Provides a StatusNotifierHost widget written using the gtk+3 bindings for haskell (recommended for taffybar)

### Panel/Bar Widgets
![Perl](https://img.shields.io/badge/-39457E?style=flat-square&logo=perl&logoColor=white)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/mbt/alltray"> Menutray</a>
: A simple GTK+ application menu tray.

![Python](https://img.shields.io/badge/-4584b6?style=flat-square&logo=python&logoColor=fff)
![Qt5](https://img.shields.io/badge/Qt5-41CD52?style=flat-square&logo=qt&logoColor=fff)
<a href="https://github.com/dglent/meteo-qt"> Meteo Qt</a>
: Display weather information in desktop panels, desktop notifications and its own window

![C++](https://img.shields.io/badge/-5e97d0?style=flat-square&logo=c%2B%2B&logoColor=fff)
![Qt6](https://img.shields.io/badge/Qt6-41CD52?style=flat-square&logo=qt&logoColor=fff)
<a href="https://invent.kde.org/utilities/kteatime">
KTeaTime	</a>
: A handy timer for steeping tea

## Programming libraries to create tray programs

![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff) <a href="https://github.com/AyatanaIndicators/ayatana-indicator-application"> Ayatana AppIndicator</a>
: Modern continuation of Canonical AppIndicator

![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff) <a href="https://docs.gtk.org/gtk3/class.StatusIcon.html">
Gtk StatusIcon</a>
: GTK Base status icon implementation

![C++](https://img.shields.io/badge/-5e97d0?style=flat-square&logo=c%2B%2B&logoColor=fff)<a href="https://doc.qt.io/qt-6/qsystemtrayicon.html">
QSystemTrayIcon</a>
: Qt Base tray implementation


![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff) <a href="https://github.com/kolbusa/stalonetray">
StaloneTray</a>
: Minimal tray implementation for x11

![C++](https://img.shields.io/badge/-5e97d0?style=flat-square&logo=c%2B%2B&logoColor=fff) <a href="https://wiki.wxwidgets.org/WxTaskBarIcon">
wxTaskBarIcon</a>
: WxWidgets Base status icon implementation
