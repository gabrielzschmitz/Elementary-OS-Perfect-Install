# How to Make the Perfect Elementary OS Install

In this article I will try to instruct you about how to install, update, personalize and install the essencial programs in
Elementary OS 5.1 Hera.

## Disclaimer

* When i use an [blue link like that](https://corgiorgy.com/) click with ctrl to open in a new tab and dont close this 
article.
* **Notify me** if you find any **grammatical errors**. My English is not one of the best.

# If you dont have installed the system [click here](https://github.com/gabrielzschmitz/Elementary-OS-Perfect-Install/blob/master/How-Install-the-System.md) to read how to!


# After install lets configure it:

## Update the system ##

```
sudo apt-get update && sudo apt-get upgrade && sudo apt dist-upgrade
```

## Enable PPA

```
sudo apt-get install software-properties-common
```

## Install Elementary Tweaks to personalize

```
sudo add-apt-repository ppa:philip.scott/elementary-tweaks

sudo apt-get update

sudo apt-get install elementary-tweaks
```

## Install Office Suite (Libre Office)

```
sudo apt install libreoffice
```

## Install Firefox

```
sudo apt install firefox
```

## Install Chrome

```
sudo apt install chrome
```

## Install Brave 

```
sudo apt install apt-transport-https curl

curl -s https://brave-browser-apt-release.s3.brave.com/brave-core.asc | sudo apt-key --keyring /etc/apt/trusted.gpg.d/brave-
browser-release.gpg add -

echo "deb [arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main" | sudo tee 
/etc/apt/sources.list.d/brave-browser-release.list

sudo apt update

sudo apt install brave-
```

## Install VLC

```
sudo apt install vlc
```

## Install Gimp and Inkscape

```
sudo apt install gimp

sudo apt install inkscape
```

## Install Multimidea Codecs

```
sudo apt install ubuntu-restricted-extras

sudo apt install libavcodec-extra

sudo apt install libdvd-pkg
```

## Install Java

```
sudo add-apt-repository -y ppa:webupd8team/java

sudo apt-get update

sudo apt-get install oracle-java9-installer
```

## Install Archieve Formats

```
sudo apt-get install unace rar unrar p7zip-rar p7zip sharutils uudeview mpack arj cabextract lzip lunzip
```

## Install Transmission (Torrent Application)

```
sudo apt-get install transmission
```

## Install Steam

```
sudo apt install steam
```

## Install Wine to install Windows programs

```
sudo apt install wine-stable
```

## Install Blender (3D Editor)

```
sudo apt install blender
```

## Install Kdenlive (Basic Video Editor)

```
sudo apt-get install kdenlive
```

## Install Audacity (Audio Editor)

```
sudo apt install audacity
```

## Best Apps from App Center

* Best Email Client – Thunderbird
* Best Free Office Suite – LibreOffice (previously installed)
* Best Password Manager – Dashlane(Just Add to the Browser)
* Best Partition Manager – Gparted
* Best PDF Editor – LibreOffice Draw
* Best Screen Recorder – OBS
* Best Torrent Client – Transmission
* Best FTP Client – FileZilla
* Best Note Taking App – Notejot
* Best Video Editing Software – Kdenlive (for Basic Edits, previously installed)Davinci Resolve (for Advanced Edits, 
download from them site)
* Best Download Manager – uGet
* Best Video Players – VLC
* Best Google Drive Client – VGrive
* Best Web Browser – Chromium or Google Chrome
* Best Media Server Software – Kodi
* Best Cloud Storage – OwnCloud

## Clean System

```
sudo apt-get autoclean

sudo apt-get clean

sudo apt-get autoremove
```
