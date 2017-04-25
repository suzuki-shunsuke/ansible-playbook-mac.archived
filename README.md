# Ansible Playbook for Mac

* wget
* curl
* nodebrew
* silver searcher
* tree
* neovim
* neovim config
* zsh
* zip
* zplug
* zsh config
* tmux
* tmux config
* tpm
* git
* gitconfig
* git lfs
* pyenv
* pyenv install dependencies
* rbenv
* rbenv/ruby-build
* rbenv install dependencies
* go
* gvm
* gvm install dependencies
* hub
* direnv
* ghq
* fzf
* colorrc
* homebrew cask
* vagrant
* packer
* terraform
* pwgen

The following items have been removed because I migrated from vim to neovim.

* vim
* neobundle.vim
* vim config

## Requirements

* ansible
* Homebrew

```
$ pip install ansible
```

## Install Ansible roles dependencies

```
$ ansible-galaxy install -r roles.yml
```

## Run

```
$ ansible-playbook -i localhost --ask-become-pass setup.yml
```

## TODO

* localize into japanese
* tmux configuration for mac

## Install Docker Engine and Docker Compose

* https://docs.docker.com/docker-for-mac/install/
* https://docs.docker.com/compose/install/
