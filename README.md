# How To Install Photoshop-CS6 On Linux (Wine)

#### 1- Install Wine On Your Linux
##### Arch
```sh
sudo pacman -S wine winetricks
```
...

#### 2- Install Windows Depenecies With winetricks
```sh
winetricks atmlib gdiplus msxml3 msxml6 vcrun2005 vcrun2005sp1 vcrun2008 ie6 fontsmooth-rgb gecko
```

#### 3- Execute Photoshop Setup File
```sh
wine Setup.exe
```

![Install Photoshop On Linux](https://raw.githubusercontent.com/tahadostifam/photoshop-install-linux/main/photoshop-screenshot.png)
