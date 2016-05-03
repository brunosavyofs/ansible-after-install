# ansible-after-install

## Requirements

- ansible
```
$ sudo -H pip install ansible
```
- python-pip
```
$ sudo apt-get install python-pip
```

## Profiles

This script has two different profiles. Each one contains a set of softwares that will be installed.

### Work
#### Sofwares which are installed in ```work``` profile:
- ansible-lint
- atom
- bower
- calibre
- clementine
- docker-compose
- guake
- guake-indicator
- git
- gparted
- nodejs
- npm
- paper-icon-theme
- paper-gtk-theme
- pcloud
- unity-tweak-tool
- valentina-dd
- variety
- vivaldi

#### To run script in ```work``` profile:
```bash
$ ansible-playbook work.yml
```

### Personal
#### All those installed in ```work``` profile is also installed in ```personal```, plus:

- gimp
- ubuntu-restricted-extras
- veracrypt
- vlc

#### To run script in ```personal``` profile:
```bash
$ ansible-playbook personal.yml
```
