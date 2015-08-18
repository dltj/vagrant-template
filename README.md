# Basic Vagrant/Ansible installation

## Introduction

## Usage

When running Ansible playbooks out of the ansible_playbooks directory, be sure to include the VirtualBox machine private key in the command line, as such:  `ansible-playbook -i .vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory provision_server.yml`

## Contributing

## Help

## Installation

### Requirements

* Ansible, version 1.8 or greater

#### Optional
* `vagrant plugin install vagrant-hostmanager` - Use [smdahlen/vagrant-hostmanager](https://github.com/smdahlen/vagrant-hostmanager) to manage the VirtualBox host's /etc/hosts file.
* `vagrant plugin install vagrant-triggers` - Use [emyl/vagrant-triggers](https://github.com/emyl/vagrant-triggers) to run commands on the host in conjunction with Vagrant commands

### Installation

1. Before provisioning for the first time, be sure all of the prerequisite roles from Ansible Galaxy have been installed: `ansible-galaxy install --roles-path=roles/managed --role-file ansible-role-requirements.yml`

### Configuration

## Credits

## Contact

## License
