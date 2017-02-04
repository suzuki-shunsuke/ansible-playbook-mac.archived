# Ansible Playbook for Mac

* wget
* curl
* nodebrew
* silver searcher
* tree
* vim
* neobundle.vim
* vim config
* zsh
* zip
* zplug
* zsh config
* tmux
* tmux config
* tpm
* docker engine
* docker compose
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
$ ansible-playbook --ask-become-pass setup.yml
```

## TODO

* 日本語対応
* Mac用のzsh, tmuxの設定
