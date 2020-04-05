# **Linux Notebook**

 

**To Mount a Disk:**

```
sudo mount -t ntfs /dev/sdb1 /media/usb1/
```

 

**To view free space of connected disk:**

```
df –h
```

 

**To backup large folders:**

```
rsync --ignore-existing -raz --progress /media/usb/Media/Pictures/ /media/usb1/Media/Pictures/
```

 

**Disable HDD Sleep –** 

```
hdparm -B255 /dev/sdX
```

 

**Mount all –** 

```
sudo mount -a
```

 

**Mount drive to folder –** 

```
sudo mount -t ntfs /dev/sdb1 /media/usb
```

 

**List Disk –** 

```
sudo fdisk -l
```

 

**Copy Folder in verbose mode -** 

```
cp -a -v ./. /media/nas/Media/Pictures/
```

 

 

**Count no. of files in dir. –** 

```
ls -1 | wc -l 
```

 

 

 

 

**References**

 

Rsync Command - https://www.linuxtechi.com/rsync-command-examples-linux/

 

Save terminal output to file - https://askubuntu.com/questions/420981/how-do-i-save-terminal-output-to-a-file

 

https://www.tecmint.com/watch-or-monitor-linux-log-files-in-real-time/

 

VMWare network adapter issue https://askubuntu.com/questions/793214/unable-to-access-internet-on-vmware

 

 