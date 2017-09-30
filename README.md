# Ansible Playbook for Mac

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

## See Also

* https://github.com/suzuki-shunsuke/mac-boot

## TODO

* tmux configuration for mac

## Install Docker Engine and Docker Compose

* https://docs.docker.com/docker-for-mac/install/
* https://docs.docker.com/compose/install/
