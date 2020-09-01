# multi-VM-Vagrant

Installing VirtualBox
``` 
sudo apt install virtualbox
``` 
Installing Vagrant
``` 
curl -O https://releases.hashicorp.com/vagrant/2.2.6/vagrant_2.2.6_x86_64.deb
sudo apt install ./vagrant_2.2.6_x86_64.deb
``` 
Check installing completed
``` 
vagrant --version
```
Add Unbuntu18 image
``` 
sudo vagrant box add generic/ubuntu1804
``` 
Write vagrant file 
``` 
nano Vagrantfile
``` 

Align virtualbox version 
``` 
vagrant plugin install vagrant-vbguest
``` 

