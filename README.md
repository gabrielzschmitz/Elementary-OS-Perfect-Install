# How to Make the Perfect Elementary OS Install

In this article I will try to instruct you about how to install, update, personalize, install the essencial programs and programs recommendations in Elementary OS 5.1 Hera.

### Disclaimer

* When i use an [blue link like that](https://corgiorgy.com/) click with ctrl to open in a new tab and dont close this article.
* **Notify me** if you find any **grammatical errors**. My English is not one of the best yet.

## How to install the system

* **Just [click here](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-the-System.md) to read and to acess videos about it.**

## After Install Lets Configure It:

* Just copy and paste line by line to the Elementary terminal
* Disclaimer: && its logical operator that execute the other command only if the previous was successfully executed and ; to execute the next command regardless of the success of the previous command. So I have used that to make the copy and paste faster, but I you display all the commands separately too.

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

* For all [click here](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md);
* [**Chrome**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#chrome): the most used browser around the world;
* [**Firefox**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#firefox): to people that dont want to give money to Google;
* [**Brave**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#brave): a very respectful of privacy browser based in Chromium;
* [**Opera**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#opera): other Chromium based browser with alot of factory features;
* [**Ephemeral**](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-your-Favorite-Browser.md#ephemeral): the always private browser of Elementary OS developers team.

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

## Install Useful Programs (Only what you need)

### Install an Office Suite

* Microsoft Office is not avaible for linux so install Libre Office an open source project that have the same functionalities of Microsoft product, but for free, only some adaptation is needed
* You can install by terminal with this command:

```
sudo apt install libreoffice
```

#### Install VLC

```
sudo apt install vlc
```

#### Install Gimp and Inkscape

```
sudo apt install gimp
sudo apt install inkscape
```

#### Install Multimidea Codecs

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
* Best Free Office Suite – LibreOffice (previously installed)
* Best Password Manager – Dashlane(Just Add to the Browser)
* Best Partition Manager – Gparted
* Best PDF Editor – LibreOffice Draw
* Best Screen Recorder – OBS
* Best Torrent Client – Transmission
* Best FTP Client – FileZilla
* Best Note Taking App – Notes-up
* Best Video Editing Software – Kdenlive (for **basic** edits, previously installed)Davinci Resolve (for Advanced Edits, download from them site [here](https://www.blackmagicdesign.com/products/davinciresolve/))
* Best Download Manager – uGet
* Best Video Players – VLC
* Best Google Drive Client – VGrive
* Best Web Browser – Chromium or Google Chrome
* Best Media Server Software – Kodi
* Best Cloud Storage – OwnCloud

### Clean System

```
sudo apt-get autoclean

sudo apt-get clean

sudo apt-get autoremove
```
