## Vagrant

```bash
brew cask install virtualbox
brew cask install https://raw.githubusercontent.com/Homebrew/homebrew-cask/7e703e0466a463fe26ab4e253e28baa9c20d5f36/Casks/virtualbox.rb
brew cask install vagrant

vagrant up --provider=virtualbox
vagrant reload
vagrant ssh
vagrant provision
vagrant destroy -f

ssh vagrant@192.168.0.33.10
```

## Resource

- https://medium.com/@AnnaJS15/getting-started-with-virtualbox-and-vagrant-8d98aa271d2a
- https://symfonycasts.com/screencast/ansible/vagrant-ansible