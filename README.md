# Automation Server Ansible and Docker on VirtualBox with Vagrant

## Prerequisites
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)

## Setup
- Clone this repository
- Run `vagrant up` in the root of this repository
- Wait for the setup to finish
- Run `cd ansible && ansible-playbook ansibleConf.yml` to setup the automation server
- Run `cd ansible && ansible-playbook neovim.yml` to setup the neovim server


## Thankyou