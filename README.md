## Description
Ansible playbook for installing and configuring both wireguard server and peers.
### Pre-configuration phase:
    - Update packages
    - Firewall rules
    - Wireguard installation
    - Wireguard key generation
    - Network facts
### Server configuration:
    - Setting up the wg0 interface in the server and adding peers
### Client configuration:
    - Setting up the wg0 interface in the client

## Usage
 - Change the the credentials in the hosts inventory file (ansible_user and ansible_host) with SSH credentials.
 - Run the deploy-wireguard file with the ansible-playbook command.
