# How to Make the Perfect Elementary OS Install

In this article I will try to instruct you about how to install, update, personalize, install the essential programs and programs recommendations in Elementary OS 5.1 Hera.

### Disclaimer

* When i use an [blue link like that](https://corgiorgy.com/) click with ctrl to open in a new tab and don’t close this article.
* **Notify me** if you find any **grammatical errors**. My English is not one of the best yet.

## How to install the system

* **Just [click here](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-the-System.md) to read and to access videos about it.**

## After Install Lets Configure It:

* Just copy and paste line by line to the Elementary terminal
* Disclaimer: "&&" its logical operator that execute the other command only if the previous was successfully executed and ";" to execute the next command regardless of the success of the previous command. So I have used that to make the copy and paste faster, but I you display all the commands separately too.

### Update the System

* Commands used to:

```
sudo apt-get update
sudo apt-get upgrade
sudo apt dist-upgrade
```

* Easy copy and paste:

```
sudo apt-get update && sudo apt-get upgrade && sudo apt dist-upgrade sudo apt update && sudo apt upgrade
```

### Enable PPA

```
sudo apt-get install software-properties-common
```

### Update Git

```
sudo apt-get install git
```

### Install Snapcraft

```
sudo apt update
sudo apt install snapd
```

* Easy copy and paste:

```
sudo apt update ; sudo apt install snapd
```

### Get your Favorite Browser

**For** a guide to how install all [**click here**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md) or directly click in your favorite:

* [**Chrome**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#chrome): the most used browser around the world;
* [**Firefox**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#firefox): to people that don't want to give money to Google;
* [**Brave**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#brave): a very respectful of privacy browser based in Chromium;
* [**Opera**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#opera): other Chromium based browser with a lot of factory features;
* [**Ephemeral**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#ephemeral): the always-incognito browser of Elementary OS developers team.

## If you are using a dual boot

* Install Grub Customizer :

```
sudo add-apt-repository ppa:danielrichter2007/grub-customizer
sudo apt-get update
sudo apt-get install grub-customizer
```

* Easy copy and paste:

```
sudo add-apt-repository ppa:danielrichter2007/grub-customizer && sudo apt-get update ; sudo apt-get install grub-customizer
```

Best theme:

Just [click here](https://www.gnome-look.org/p/1009236/) to download


### Clean-up the System

* Commands:

```
sudo apt-get purge midori-granite
sudo apt-get purge noise
sudo apt-get purge software-center
sudo apt-get purge scratch-text-editor
sudo apt-get purge modemmanager
sudo apt-get autoremove
sudo apt-get autoclean
```

* Easy copy and Paste:

```
sudo apt-get purge midori-granite ; sudo apt-get purge noise ; sudo apt-get purge software-center ; sudo apt-get purge scratch-text-editor ; sudo apt-get purge modemmanager ; sudo apt-get autoremove ; sudo apt-get autoclean
```

### Install File Compression Libs

```
sudo apt-get install unace unrar zip unzip xz-utils p7zip-full p7zip-rar sharutils rar uudeview mpack arj cabextract file-roller
```

### Install Elementary Tweaks to personalize

* Commands:

```
sudo add-apt-repository ppa:philip.scott/elementary-tweaks
sudo apt-get update
sudo apt-get install elementary-tweaks
```

* Easy copy and Paste:

```
sudo add-apt-repository ppa:philip.scott/elementary-tweaks && sudo apt-get update ; sudo apt-get install elementary-tweaks
```

# Install Useful Programs (Only what you need)

### Install an Office Suite

* Microsoft Office is not available for Linux so the best alternative to install is Libre Office an open source project that have the same functionalities of Microsoft product, but for free,  you just need to adaptable.

![](pictures/libre-office.png)

* You can install by terminal with this command:

```
sudo apt install libreoffice
```

#### Install VLC

![](pictures/vlc.png)

```
sudo apt install vlc
```

For how to make VLC look like mine and get a list of the best themes [click here](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/Best-VLC-Themes-and-How-Install-it.md)

#### Install GIMP

* For GIMP just download it from [**GIMP**](https://www.gimp.org/downloads/) site by clicking in "Install GIMP flatpak";
* After the download open the .flatpakref;
* Wait to the informations be loaded;
* Check the "I understood" box and click install;
* After that just wait the program be downloaded and installed.

##### To make GIMP more like Photoshop

* If you're more used to Photoshop or if you think that is prettier I recommend you to install PhotoGIMP a brazilian GIMP modification to make the GIMP experience more like Photoshop.
* You can install it using [snap](https://snapcraft.io/photogimp):

<img src="pictures/photo-GIMP.png" width="819">

```
sudo snap install photogimp
```

#### Install Inkscape

* For Inkscape you'll need to add they PPA an then just use apt-get install:

```
sudo add-apt-repository ppa:inkscape.dev/stable
sudo apt-get update
sudo apt-get install inkscape
```

* Easy copy and Paste:

```
sudo add-apt-repository ppa:inkscape.dev/stable && sudo apt-get update ; sudo apt-get install inkscape
```

#### Install Multimedia Codecs

* Commands:

```
sudo apt install ubuntu-restricted-extras
sudo apt install libavcodec-extra
sudo apt install libdvd-pkg
```

* Easy copy and Paste:

```
sudo apt install ubuntu-restricted-extras ; sudo apt install libavcodec-extra ; sudo apt install libdvd-pkg
```

#### Install Java

* Commands:

```
sudo add-apt-repository -y ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java9-installer
```

* Easy copy and Paste:

```
sudo add-apt-repository -y ppa:webupd8team/java && sudo apt-get update ; sudo apt-get install oracle-java9-installer
```

#### Install Transmission (Torrent Application)

```
sudo apt-get install transmission
```

#### Install Steam

```
sudo apt install steam
```

#### Install Wine to install Windows programs

```
sudo apt install wine-stable
```

#### Install Blender (3D Editor)

```
sudo apt install blender
```

#### Install Kdenlive (Basic Video Editor)

```
sudo apt-get install kdenlive
```

#### Install Audacity (Audio Editor)

```
sudo apt install audacity
```

#### Install Soundnode (Souncloud Desktop Client)

* Commands:

```
curl -s https://packagecloud.io/install/repositories/JonasGroeger/soundnode/script.deb.sh | sudo os=ubuntu dist=xenial bash
sudo apt-get update
sudo apt-get install soundnode

```

* Easy copy and paste:

```
curl -s https://packagecloud.io/install/repositories/JonasGroeger/soundnode/script.deb.sh | sudo os=ubuntu dist=xenial bash && sudo apt-get update ; sudo apt-get install soundnode
```

### Best Apps from App Center

* Best Email Client – Thunderbird
* Best Free Office Suite – Libre Office (previously installed)
* Best Password Manager – Dashlane (Just Add to the Browser)
* Best Partition Manager – Gparted
* Best PDF Editor – Libre Office Draw
* Best Screen Recorder – OBS
* Best Torrent Client – Transmission
* Best FTP Client – FileZilla
* Best Note Taking App – Notes-up
* Best Video Editing Software – Kdenlive (for **basic** edits, previously installed)Davinci Resolve (for Advanced Edits, download from them site [here](https://www.blackmagicdesign.com/products/davinciresolve/))
* Best Download Manager – uGet
* Best Video Players – VLC
* Best Google Drive Client – VGrive
* Best Media Server Software – Kodi
* Best Cloud Storage – OwnCloud

### Clean System

```
sudo apt-get autoclean

sudo apt-get clean

sudo apt-get autoremove
```
