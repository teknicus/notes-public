# Ubuntu / Elementary OS Setup Notes

###### Note: This is for my personal setup which runs on VMWare Workstation 15.

##### 1) Remove Unwanted Packages

Open the AppCenter and remove packages that are not required



##### 2) Update the System

```
sudo apt update
```

```
sudo apt upgrade
```



##### 3) Install restricted extras and essential utilities

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



##### 4) Enable Gnome Extensions

```
sudo apt install gnome-tweaks
```



##### 5) Install VLC

```
sudo apt install vlc
```



##### 6) Compression Formats

```
sudo apt install rar unrar cabextract lzip lunzip arj unace p7zip-rar p7zip
```



##### 7) Install GDebi - Click to install .deb packages

```
sudo apt install gdebi
```



##### 8) Install Brave Browser

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



##### 9) Install Typora

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



##### 10) Install Teams

Download the .deb package from : https://products.office.com/en-us/microsoft-teams/download-app#desktopAppDownloadregion

Install it with apt : 

```
sudo apt install ./<package>.deb
```







































) Cleanup

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