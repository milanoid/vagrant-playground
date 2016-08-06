# vagrant-playground
### prepare workspace
```mkdir d:\VagrantBox\MyFirstMachine && cd VagrantBox\MyFirstMachine```
### vagrant box init creates basic Vagrantfile
```vagrant init “opentable/win-8.1-enterprise-amd64-nocm”```
### Windows box needs plugin
```vagrant plugin install vagrant-windows```
### at first-time it takes a while as it downloads Vagrant box from the cloud
```vagran up```
