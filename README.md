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

### Common
#### Sofwares which are installed in both work and personal profiles:
- atom
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
- unity-tweak-tool
- variety

### Personal
#### Softwares which are installed only in personal profile.

- gimp
- ubuntu-restricted-extras
- veracrypt
- vlc

#### To run script in personal profile:
```bash
$ ansible-playbook personal.yml
```

### Work
There is no software that will be installed only in work profile

#### To run script in work profile:
```bash
$ ansible-playbook work.yml
```

### All

#### To install all softwares:
```bash
$ ansible-playbook all.yml
```

## Which sofwares are installed in both work and personal profiles
