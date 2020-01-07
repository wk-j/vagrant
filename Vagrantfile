# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/trusty64"
    config.vm.box_version = "20190514.0.0"
    config.vm.synced_folder "shared/", "/home/vagrant/shared"
    config.vm.network "private_network", ip: "192.168.33.10"
    config.vm.provision "shell", inline: <<-SHELL
        apt-get update
        apt-get install -y git
    SHELL
end