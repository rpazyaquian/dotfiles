DOTFILES
========

An OSX based dotfile provisioned by ansible.

## Introduction

Welcome to Dotfiles !

Dotfiles is a simple configuration tool for OS X.

## To DO

- [x] Install Powerline
- [x] Set Lambda-mod ZSH Theme
- [x] Set Dracula as a iterm and vim Theme
- [x] Set default git editor
- [ ] Paths for OSX default configs
- [ ] Ask for Git Name and Email for gitconfig
- [ ] Git commit message (dotfile)
- [ ] Add shortcut function for ~/Code folder
- [ ] Update dotfile copy and use template instead
- [ ] Template for Computer Name
- [ ] Integrate with vimfiles


## Get started

1. Be sure to have the XCode Command-Line tools installed: `xcode-select --install`
2. Easy_install pip, and then pip install Ansible: `sudo easy_install pip; sudo pip install ansible` (or `sudo pip install --upgrade ansible` if Ansible has already been installed via pip and needs upgrading to 1.8+)
3. While that's happening [Fork this repo](https://github.com/pragmaticivan/dotfiles/fork) and then clone your fork anywhere you want on your machine: `git clone https://github.com/<yourname>/dotfiles.git ~/ansible-dotfiles; cd ~/ansible-dotfiles`
4. Take a quick look at `playbook.yml` customizing to your liking.
5. Start osxc with `ansible-playbook playbook.yml`

At the end, you'll only need to repeat step 5.

Now you're ready to further tweak the configuration we gave you. Have fun ! (You may want to read the [Ansible documentation](http://docs.ansible.com/index.html) in this case ...)
