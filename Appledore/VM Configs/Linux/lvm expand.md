`sudo lvm`

`lvextend -l +100%FREE /dev/ubuntu-vg/ubuntu-lv`
`exit`

`sudo resize2fs /dev/ubuntu-vg/ubuntu-lv`