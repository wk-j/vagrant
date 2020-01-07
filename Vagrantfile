# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/trusty64"
    config.vm.box_version = "20190514.0.0"
    config.vm.synced_folder "shared/", "/home/vagrant/shared"
    config.vm.provision "shell", inline: <<-SHELL
        apt-get update
        apt-get install -y git
        apt-get install -y emacs
        apt-get install -y python3-pip
        apt-get install -y pylint3
        apt-get install -y golang
        apt upgrade -y
    SHELL
end