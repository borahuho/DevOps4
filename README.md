# DevOps4
```
With this vagrant, you will install one Ubuntu 18.04 machine.
It will add some default users, groups and directory's.
This Vagrant is to practice system hardening.
This repository is intended for educational purpose only.
```

## Prerequisites
```
This setup is the next to practice with my students.
Works on Windows 10

Software needed:
* Vagrant 2.2.6 or higher
* Virtualbox 5.0 or higher
* Git bash for Windows
```
## Installation
```
Install Virtualbox: https://www.virtualbox.org/wiki/Downloads
Install Git bash for Windows: https://gitforwindows.org/
Install Vagrant for Windows: https://www.vagrantup.com/downloads.html
```
## Run this Vagrant VM
Open Git Bash in Windows
```
cd Documents
mkdir vagrant && cd vagrant
git clone https://github.com/borahuho/DevOps4
cd DevOps4
vagrant up
vagrant ssh
```
## Mission
```
Read your mission in ~/vagrant/mission
```
## Network
Vagrant VM will be set up with 2 network adapters
```
Nat : DHCP
Localhost : 192.168.10.7
```
## Vagrant commands
Make a new VM with Vagrant
```
vagrant up
```
Stop and shutdown a VM
```
vagrant halt
```
Remove a VM
```
vagrant destroy
```
ssh in to the VM
```
vagrant ssh DevOps4
```
