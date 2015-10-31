# dotfiles

> Modern OSX based dotfile provisioned by ansible.

<img width="720" src="https://cloud.githubusercontent.com/assets/301291/10748612/1655d6c0-7c30-11e5-950e-4968f8825ff0.jpg" alt="Demo">


## Why

Welcome to Dotfiles !

If you don't like or don't have experience with shell script, using ansible (via yml) is a good way to understand what's happening in your entire configuration.

This `dotfiles` is a simple configuration tool for Mac OSX.

## Prerequisites

* Be sure to have the XCode Command-Line tools installed: `xcode-select --install`
* Easy_install pip, and then pip install Ansible: `sudo easy_install pip; sudo pip install ansible` (or `sudo pip install --upgrade ansible` if Ansible has already been installed via pip and needs upgrading to 1.8+)

## Fork and personal infos

* While that's happening [Fork this repo](https://github.com/pragmaticivan/dotfiles/fork) and then clone your fork anywhere you want on your machine: `git clone https://github.com/<yourname>/dotfiles.git ~/ansible-dotfiles; cd ~/ansible-dotfiles`

* Take a quick look at `playbook.yml` customizing to your liking.

## Installation

Install dotfiles with `ansible-playbook playbook.yml`

## Compatibility

This project is just tested with OSX.

Now you're ready to further tweak the configuration we gave you. Have fun ! (You may want to read the [Ansible documentation](http://docs.ansible.com/index.html) in this case ...)

## Roadmap

- [x] Install Powerline
- [x] Set Lambda-mod ZSH Theme
- [x] Set Dracula as a iterm and vim Theme
- [x] Set default git editor
- [x] Git commit message (dotfile)
- [x] Gitconfig
- [ ] Paths for OSX default configs
- [ ] Add shortcut function for ~/Code folder
- [ ] Update dotfile copy and use template instead
- [ ] Template for Computer Name
- [ ] Integrate with vimfiles

## Bugs

I want this to work for everyone who uses OSX; that means when you clone it down it should work for you even though you choose to use rbenv, for example. I do use this as my `dotfiles`, so there's a good chance I may break something if I forget to make a check for a dependency.

If you're brand-new to the project and run into any blockers, please open an issue on this repository and I'd love to get it fixed for you!

## Contributing

Feel free to contribute.

## Thanks
I used some excellent `dotfiles` and tweaked it to fit my taste. Thanks everyone!
