# Installing photoshop-cs6 on linux using wine

### 1- Install wine on your linux distro
#### Arch
```sh
sudo pacman -S wine winetricks
```
...

#### 2- Installing depenecies with winetricks
```sh
winetricks atmlib gdiplus msxml3 msxml6 vcrun2005 vcrun2005sp1 vcrun2008 ie6 fontsmooth-rgb gecko
```

#### 3- Run Setup File
```sh
wine Setup.exe
```

![Installing Photoshop On Linux](https://raw.githubusercontent.com/tahadostifam/photoshop-install-linux/main/photoshop-screenshot.png)
