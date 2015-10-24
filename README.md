DOTFILES
========

An OSX based dotfile provisioned by ansible.

## Introduction

Welcome to Dotfiles !

Dotfiles is a simple configuration tool for OS X.

## To DO

- [ ] Integrate with vimfiles
- [ ] Paths for OSX default configs.

## Get started

> **Additional Note:** If you're installing system-wide `sudo ansible-galaxy install -r requirements.yml` otherwise edit `ansible.cfg` and comment out `roles_path:./roles` to install the roles in your osxc.starter fork before running **Step 5**.

1. Be sure to have the XCode Command-Line tools installed: `xcode-select --install`
2. Easy_install pip, and then pip install Ansible: `sudo easy_install pip; sudo pip install ansible` (or `sudo pip install --upgrade ansible` if Ansible has already been installed via pip and needs upgrading to 1.8+)
3. While that's happening [Fork this repo](https://github.com/pragmaticivan/dotfiles/fork) and then clone your fork anywhere you want on your machine: `git clone https://github.com/<yourname>/dotfiles.git ~/src/osxc; cd ~/src/osxc`
4. Take a quick look at `configuration.yml` and `install.yml` customizing to your liking.
5. Start osxc with `ansible-galaxy install -r requirements.yml && ansible-playbook desktop.yml`

At the end, you'll only need to repeat step 5.

Now you're ready to further tweak the configuration we gave you. Have fun ! (You may want to read the [Ansible documentation](http://docs.ansible.com/index.html) in this case ...)
