## Vagrant

```bash
brew cask install virtualbox
brew cask install https://raw.githubusercontent.com/Homebrew/homebrew-cask/7e703e0466a463fe26ab4e253e28baa9c20d5f36/Casks/virtualbox.rb
brew cask install vagrant

vagrant up --provider=virtualbox
vagrant up
vagrant reload
vagrant ssh
vagrant destroy -f
vagrant ssh-config

vagrant ssh node1
vagrant ssh node2

ssh vagrant@192.168.33.10 -p 22 -i .vagrant/machines/node1/virtualbox/private_key
ssh vagrant@192.168.33.20 -p 22 -i .vagrant/machines/node2/virtualbox/private_key
```

## Resource

- https://medium.com/@AnnaJS15/getting-started-with-virtualbox-and-vagrant-8d98aa271d2a
- https://symfonycasts.com/screencast/ansible/vagrant-ansible
- https://manski.net/2016/09/vagrant-multi-machine-tutorial