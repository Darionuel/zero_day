Vagrant on windows


Download VirtualBox
Install VirtualBox
Download Vagrant
Install Vagrant
Open the command prompt
Add the Ubuntu 20.04 (Focal) image to your box list using: vagrant box add ubuntu/focal64 {Warning: this step can take time}
Create your first virtual machine:
vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" -you don’t have to execute this command line everyday, only once, to create a new virtual machine 
vagrant plugin install vagrant-vbguest -> to avoid issue with the last version of Vagrant (2.2.4 or latest)
vagrant up -> it will start your virtual machine 
vagrant ssh -> now you are inside your virtual machine. 
