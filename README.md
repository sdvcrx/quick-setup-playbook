## Quick setup playbooks ##

[![Build Status](https://travis-ci.org/sdvcrx/quick-setup-playbook.svg?branch=master)](https://travis-ci.org/sdvcrx/quick-setup-playbook)

> Setup a server in minutes!

### Installation ###

```
sudo pacman -S ansible      # ArchLinux

pip install ansible         # Or python pip

ansible-galaxy install -p galaxy.roles -r ./requirements.yml
```

### Usage ###

Install Nginx for a single host:

    ansible-playbook -l "web1" nginx.yml

