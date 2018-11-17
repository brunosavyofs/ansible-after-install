# ansible-after-install

[![Build Status](https://travis-ci.org/brunosavyofs/ansible-after-install.svg?branch=master)](https://travis-ci.org/brunosavyofs/ansible-after-install)

## Requirements

- Apt-get

``` shell
sudo apt-get install build-essential libssl-dev libffi-dev python-dev python-pip
```

- Pip

``` shell
sudo -H pip install ansible
```

## Profiles

This script has two different profiles. Each one contains a set of softwares that will be installed.

### Work

#### Sofwares which are installed in ```work``` profile:

- ansible-lint
- bower
- docker-compose
- guake
- guake-indicator
- git
- gparted
- nodejs
- npm
- paper-icon-theme
- pcloud
- unity-tweak-tool

#### To run script in ```work``` profile:

``` bash
ansible-playbook work.yml
```

### Personal

#### All those installed in ```work``` profile is also installed in ```personal```, plus:

- gimp
- ubuntu-restricted-extras
- veracrypt
- vlc

#### To run script in ```personal``` profile:

``` bash
ansible-playbook personal.yml
```
