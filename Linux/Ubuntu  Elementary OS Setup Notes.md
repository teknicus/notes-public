# Ubuntu / Elementary OS Setup Notes

###### Note: This is for my personal setup which runs on VMWare Workstation 15.

- ##### Remove Unwanted Packages


Open the AppCenter and remove packages that are not required



- ##### Update the System


```
sudo apt update
```

```
sudo apt upgrade
```



- ##### Install restricted extras and essential utilities


```
sudo apt-get install software-properties-common
```

```
sudo apt install ubuntu-restricted-extras
```

```
sudo apt install libavcodec-extra
```

```
sudo apt install libdvd-pkg
```



- ##### Enable Gnome Extensions


```
sudo apt install gnome-tweaks
```



- ##### Install VLC


```
sudo apt install vlc
```



- ##### Compression Formats


```
sudo apt install rar unrar cabextract lzip lunzip arj unace p7zip-rar p7zip
```



- ##### Install GDebi - Click to install .deb packages


```
sudo apt install gdebi
```



- ##### Install Brave Browser

###### Ref : https://brave-browser.readthedocs.io/en/latest/installing-brave.html#linux

Commands as on 08-04-2020 - 

```
sudo apt install apt-transport-https curl
```

```
curl -s https://brave-browser-apt-release.s3.brave.com/brave-core.asc | sudo apt-key --keyring /etc/apt/trusted.gpg.d/brave-browser-release.gpg add -
```

```
echo "deb [arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main" | sudo tee /etc/apt/sources.list.d/brave-browser-release.list
```

```
sudo apt update
```

```
sudo apt install brave-browser
```



- ##### Install Typora

```
wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -
```

```
sudo add-apt-repository 'deb https://typora.io/linux ./'
```

```
sudo apt-get update
```

```
sudo apt-get install typora
```



- ##### Install Teams


Download the .deb package from : https://products.office.com/en-us/microsoft-teams/download-app#desktopAppDownloadregion

Install it with apt : 

```
sudo apt install ./<package>.deb
```



- ##### Install VS Code : 

Download the .deb package from https://code.visualstudio.com/docs/setup/linux

```
sudo apt install ./<package>.deb
```



- ##### Install Java 8

```
sudo apt install openjdk-8-jdk
```



- ##### Install NVM, NPM and NodeJS

Ref: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04

1) Node Version Manager

```
curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh -o install_nvm.sh
```

```
bash install_nvm.sh
```



2) NodeJS

```sh
nvm ls-remote //list versions
```

```
nvm install 8.11.1 //select the version you want to use
```









- ##### Gnome Customizations
  - Change GDM theme : https://www.youtube.com/watch?v=YCFnYehZhCY
  - Install Gnome-tweaks, themes, icon set : https://www.omgubuntu.co.uk/2017/03/make-ubuntu-look-like-mac-5-steps
  - Install Plank, Set theme, add to startup : https://www.deviantart.com/p0umon/art/Gnosemite-theme-for-Plank-628809799
  -  Permanently Hide default dock : https://www.linuxuprising.com/2018/08/how-to-remove-or-disable-ubuntu-dock.html

- Useful Tools - Stacer, RAMbox, Kdenlive, gimp, gsconnect









- ##### Cleanup

```
sudo apt-get autoclean
```

```
sudo apt-get clean
```

```
sudo apt-get autoremove
```





References

https://itsfoss.com/things-to-do-after-installing-elementary-os-5-juno/

https://linoxide.com/linux-how-to/24-things-installing-elementary-os-loki/

https://www.ubuntupit.com/best-things-to-do-after-installing-elementary-os/