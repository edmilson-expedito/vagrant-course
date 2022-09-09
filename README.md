Install VirtualBox in https://www.virtualbox.org/wiki/Downloads
Install Vagrant in https://www.vagrantup.com/downloads.html

Make you workspace with a folder
- On this folter execute the simple steps

1- Init Vagrant
    vagrant init hashicorp/precise64

2- Start the virtual machine
    vagrant up

3- Connect using SSH
    vagrant ssh

4- Reload config
    vagrant reload

5- Stop de virtual machine
    vagrant halt

6- Exclude virtual machine
    vagrant destroy ( using "-f" to force exclude without questions)