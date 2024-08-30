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

## Multimedia
### Music
![C++](https://img.shields.io/badge/-5e97d0?style=flat-square&logo=c%2B%2B&logoColor=fff)
![GTK3](https://img.shields.io/badge/WxWidgets-337ab7?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAAAuCAYAAACYlx/0AAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAdnJLH8AAAAgY0hSTQAAeiYAAICEAAD6AAAAgOgAAHUwAADqYAAAOpgAABdwnLpRPAAABM9JREFUaIHtmT2IJEUUx3/VXTMLwjQ77YGBq2hiJAgHB0bndyqYGRzoBcIhIqwYCIZioMGBindgcsaKCmd2aCDGIgjGnqGiTrNbuyxOd5XBbs3V1lZ118zUHor7h2Vn3qt69d6r99U9cIYz/K8hTkOoUuoC8BbwBHCvzzfGpIjZN8Z8D3xcVdXXeTW8g+wOUEpdAa4JIURZlsE1fQ5weV3X2e/Xq6p6Na+mh8jqAKXU08C3ZVkyGo0QQkSNDdF9mjGGruto2xbg9aqqPsqpL+R3wHdCiIsbGxsIcUe0a1iK4T5tPp+jtf5DCHHfZDLROXUucgna29sbARdt2LsOgEODQjecQiuKAmPMOa31Y7n0tZAZZT1gjAka7mNZmpUphDiXQ1EXOR0QTSdryKrOcPZnL9rZHODnecyI2PdlaDmRMwKAsCPWLYKniewOgPVCPbYuVF9yIKsDUm9tyPD/dA3ou+m+243xhRAIIZBSAryolDofkx/Bn8CtyWRyO8Q89RSIGefSY4YbY9D62NzzcuiMFF12dnZuAK9VVbXv8nNGgFim0scMh0PjtdYURcFoNKIoiuhYPURzxunLwEO7u7vPTCaTxYJsk6CF1jqY036oDz0QCSEYj8eUZZlsfExuWZY2hZ4yxrzi8nojQCn1KDAhYcjpum7LVmk3bIfmA19WURRorRmPx4v8zzFTlGVpny4vAZ9YetABSqnLwDvA/TFFfVjF3XZlDbb0GGI1YGjdMvODdW7bthdc+gkHKKWuAttFUSClTJ7tjTEcHBwED48h5VF53cEpIGvD5R9zgFLqWWBbSsloNAoKcW/XpXnVeukbDylroyllRkg9w4cfAdtOz10p//qK3TrKriOrT77vgMeL4rAxLOt5W7Bs+/ILYa55P9Vwf/6IdRLpbZoO5XyfIVJK5vP54l1eKF36jEg9p48WKrh97fdEEQxNbqk3KKWk67oT3aAPvoyjtz8LXqoTA1Nj0pwQbINDyveF4Xg8XkSBr1CKPJuCMaVjFxGbPYaQNAqHoiLEXwiVEinlQiljDPP5HGPMu0KIr/r2Ai8Aby8z+Q3p18cLpkAoZ9YZRW2BFEL8urm5+UNUS6BpmvMx2f5n3wEhDEWDXwR7F8fWDYXpKtVea43WGv/HFStrlelysAvEFg5FQUoIrgqb3+7/dYas5C4wtHHZ3FvXOUPhvuqQFU2BFE+m3kTOgSd1Xer+YATY3IsZu8pNrAL31lPaYeL5x3pzbxfwBd4lw3+z8uxYnXLO0PmO7j+79N4UcP9iQ806LSiCb4wxs67rpkII2rZdzPGplT3Ed/Z/4fKTXokNVf8h3jKO2Nzc3AfeMObwXZ79eTw05g453zX+aP8vwFV3XVIbzMFL4VtMp9NPZ7NZpbV+X2u9kfJSJuG8n4Dn67pWLtF3wG1jzMOhQ9btvUef91IUB5hOpx/OZrObwEvGmEeAe1J08dABfwG3gC/ruj6Rx8dc2zTNdeCKlJKyLBfP9bGpK7UgHcmYA1t1Xf+eqv3dgF8D3gP22ral67pjz/Yu+gpSxHiAD/5txkPgdXfTNE8CN4HJKs/zPu+I/zlwqa7rv1dV9LQQtLBpmi1jzJvAc8CDDHSLiBN2gR+BG3Vdf7amnmc4wxlOB/8A+uVS19dRL5EAAAAASUVORK5CYII=&logoColor=fff)
<a href="https://github.com/ebruck/radiotray-ng">Radiotray-NG</a> : An Internet radio player for Linux

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
<a href="https://github.com/trizen/menutray"> Menutray</a>
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

### Fun
![C](https://img.shields.io/badge/-044f99?style=flat-square&logo=c&logoColor=fff)
![GTK3](https://img.shields.io/badge/GTK3-527999?style=flat-square&logo=gtk&logoColor=fff)
<a href="https://github.com/chux0519/runcat-tray"> runcat-tray</a>
: A runcat port for Linux using libappindicator (Another useless cat here..)

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
