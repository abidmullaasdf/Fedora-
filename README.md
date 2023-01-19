
<p align="center">My Channel</br><b>
| <a href="https://discord.gg/GCehyym">Discord</a> | <a href="https://youtube.com/channel/UC3sLb7eZCu72iv3G1yUhUHQ">YouTube</a> |</b></p>

---
## Fedora on Termux Android

---
Announcement :

For Android 12 problems in [Termux v0.119.1](https://apkcombo.com/id/termux/com.termux) it has been fixed.

---
• Install Apps on Android
- [x] [Termux](https://apkcombo.com/id/termux/com.termux)
- [x] [Vnc Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android)

## Installation

Copy and paste this command to Termux :
> pkg update && pkg upgrade

1. Install Fedora

* [Fedora 38.0 (Container)](https://youtu.be/pKn6qZr1Y90)</br>
(Arm64/Amd64)
```
pkg install wget -y && wget https://raw.githubusercontent.com/wahasa/Project/main/Linux/Fedora/fedora38.0.0.sh && chmod +x fedora38.0.0.sh && ./fedora38.0.0.sh
```

* [Fedora 37.0 (Container)](https://youtu.be/P6ca5xCksXo)</br>
(Arm64/Amd64)
```
pkg install wget -y && wget https://raw.githubusercontent.com/wahasa/Project/main/Linux/Fedora/fedora37.0.0.sh && chmod +x fedora37.0.0.sh && ./fedora37.0.0.sh
```

* [Fedora 36.1.5 (Container)](https://youtu.be/DkKFfDYuEq4)</br>
(Armhf/Arm64/Amd64)
```
pkg install wget -y && wget https://raw.githubusercontent.com/wahasa/Project/main/Linux/Fedora/fedora36.1.5.sh && chmod +x fedora36.1.5.sh && ./fedora36.1.5.sh
```

2. Start Fedora
```
fedora
```

3. Stop Fedora
```
exit
```

---
Basic commands Fedora
> dnf update : Update list package.</br>
> dnf upgrade : Upgrade package.</br>
> dnf search (pkg) : Search package.</br>
> dnf install (pkg) : Install package.</br>
> dnf autoremove (pkg) : Delete package.</br>
> dnf -h : Help all commands.
---
## Desktop Environment

on Fedora, run this command :
> apt update && apt upgrade

* [Install Desktop Xfce](https://youtu.be/ON_lcUEs5VY)
```
dnf install wget -y && wget https://raw.githubusercontent.com/wahasa/fedora/main/de-xfce.sh && chmod +x de-xfce.sh && ./de-xfce.sh
```

* [Install Desktop Xlde](https://youtu.be/YGEv8ZMGXMk)
```
dnf install wget -y && wget https://raw.githubusercontent.com/wahasa/fedora/main/de-lxde.sh && chmod +x de-lxde.sh && ./de-lxde.sh
```

* [Install Desktop Xlqt]()
```
dnf install wget -y && wget https://raw.githubusercontent.com/wahasa/fedora/main/de-lxqt.sh && chmod +x de-lxqt.sh && ./de-lxqt.sh
```

* [Install Desktop Xlqt]()
```
dnf install wget -y && wget https://raw.githubusercontent.com/wahasa/fedora/main/de-kde.sh && chmod +x de-kde.sh && ./de-kde.sh
```
---
Note :
- [x] Sound fix
- [x] Browser fix [Click here,.]

Visit problems now in : [Issues](https://github.com/wahasa/fedora/issues)

---
## VNC Viewer

1. Start VNC Server

on Fedora, run this command to start :
```
vnc-start
```

2. Open Vnc Viewer

Add (+) VNC Client to connect, fill with :

Address
```
localhost:1
```

Name
```
Fedora Desktop
```

To disconnect VNC Client, click (X) on the right.

3. Stop VNC Server

on Fedora, run this command to stop :
```
vnc-stop
```

</br>

---
<p align="center">Good Luck</p>

---
