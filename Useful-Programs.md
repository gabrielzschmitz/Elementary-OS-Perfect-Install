# Useful Programs

## Summary

* [Thunderbird]
* [Libre Office](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-an-office-suite)
* [GIMP](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-gimp)
* [Dashlane]
* [Audacity](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-audacity-audio-editor)
* [Inkscape](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-inkscape)
* [Gparted]
* [OBS]
* [Blender](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-blender-3d-editor)
* [Wine](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-wine-to-install-windows-programs)
* [Transmission](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-transmission)
* [Steam](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-steam)
* [Notes-up]
* [Kdenlive (for **basic** edits)](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-kdenlive-basic-video-editor)
* [Davinci Resolve (for Advanced Edits)](https://www.blackmagicdesign.com/products/davinciresolve/))
* [uGet]
* [VLC](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/README.md#install-vlc)
* [VGrive]

### Install an Office Suite

* **Microsoft Office** is **not available for Linux** so the best alternative to install is **Libre Office** an **open-source** project that have the **same functionalities** of **Microsoft** product, but for **free**,  you just **need** to **adaptable**.

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/libre-office.png)

* You can **install** by terminal **with this command**:

```
sudo apt install libreoffice
```

### Install VLC

* **VLC** is the **best video player** for basically all the **operational system** and to **Linux** is **not different**.

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/vlc.png)

```
sudo apt install vlc
```

* For **how to** make **VLC look like mine** and get a **list of** the **best themes** [click here](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/Best-VLC-Themes-and-How-Install-it.md)

### Install GIMP

* For **GIMP** just **download it** from [**GIMP**](https://www.gimp.org/downloads/) site by clicking in **"Install GIMP flatpak"**;
* **After** **the download open** the **.flatpakref**;
* **Wait** to the **informations** be loaded;
* **Check** the **"I understood"** box and **click install**;
* **After that** just **wait** the program **be downloaded and installed**.

#### To make GIMP more like Photoshop

* If you're **more used** to **Photoshop** or if you think that is prettier I recommend you to **install PhotoGIMP** a **Brazilian GIMP modification** to **make** the **GIMP** experience more **like Photoshop**.
* You can **install it** using [snap](https://snapcraft.io/photogimp):

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/photo-GIMP.png)

```
sudo snap install photogimp
```

### Install Inkscape

* As **like GIMP**, **Inkscape is** a **Linux free** and **open-source** **vector** graphics **editor** **alternative to Illustrator**. For **Inkscape** you'll **need** to **add** they **PPA** and **then** just use **apt-get install**:

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/inkscape.png)

```
sudo add-apt-repository ppa:inkscape.dev/stable
sudo apt-get update
sudo apt-get install inkscape
```

* Easy **copy and paste**:

```
sudo add-apt-repository ppa:inkscape.dev/stable && sudo apt-get update ; sudo apt-get install inkscape
```

### Install Transmission

* **Transmission** is the **best free Torrent client** for **Linux**, so **if you need** to download or upload torrent just **install it**.

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/transmission.png)

```
sudo apt-get install transmission
```

### Install Steam

* **Steam** is a **video game digital distribution service** by **Valve**, but **everyone knows** so thats the **command** to **install it**:

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/steam.png)

```
sudo apt install steam
```

### Install Wine to install Windows programs

* **Wine is not an Emulator(Wine)** is a **free and open-source** compatibility layer that aims to **allow** computer **programs** developed for **Microsoft Windows** to **run on  Linux, macOS, & BSD**.

```
sudo apt install wine-stable
```

### Install Blender (3D Editor)

* **Blender** is a **free 3D modelling and animation suite** and is one of the **best 3d editor** for **Linux** and even to **macOS and Windows**.

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/blender.png)

```
sudo apt install blender
```

### Install Kdenlive (Basic Video Editor)

* **Kdenlive** is a **free and open-source basic video editing software**, which has **enough features** for most of **nonprofessional edits**.

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/kdenlive.png)

```
sudo apt-get install kdenlive
```

* For **dark theme** use the **command below** to install Kdenlive Runtime and **then** on the **toolbar** goes **Settings->Theme->Breeze Dark** and **Settings->Style->Breeze**.

```
sudo apt install kde-runtime
```

### Install Audacity (Audio Editor)

* **Audacity** is the **best digital audio editor and recording software** in the market, Besides that, to improve is **free and open-source**.

![](/home/gabrielzschmitz/Documents/Elementary-OS-Perfect-Install/pictures/audacity.png)

```
sudo apt install audacity
```

