# Setup Notes for Hyperledger Fabric 2.0

Base : Ubuntu 20.04LTS

`sudo apt update`

`sudo apt upgrade`

`sudo su -`

`sudo apt install git curl wget`

`sudo apt install apt-transport-https ca-certificates curl software-properties-common`

Prereqs (https://hyperledger-fabric.readthedocs.io/en/release-2.0/prereqs.html)

Docker install : (https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04)

`curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -`

`sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"`

`sudo apt update`

`sudo apt-cache policy docker-ce docker-compose`



GoLang Install : (https://www.digitalocean.com/community/tutorials/how-to-install-go-and-set-up-a-local-programming-environment-on-ubuntu-18-04)

(https://www.digitalocean.com/community/tutorials/how-to-install-go-on-ubuntu-18-04)



`curl -O https://dl.google.com/go/go1.12.1.linux-amd64.tar.gz`

`sudo tar -xvf go1.12.1.linux-amd64.tar.gz -C /usr/local`

`sudo chown -R root:root /usr/local/go`



NodeJS Install :  (https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04)



HLF2 Install (https://hyperledger-fabric.readthedocs.io/en/release-2.0/install.html)



