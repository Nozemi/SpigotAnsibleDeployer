# Ansible - Spigot Server Deployer
This is an Ansible playbook I wrote to build and deploy a Spigot server to a Ubuntu server.

Run `ansible-playbook -i inventory main.yml --ask-become-pass` from a Linux system with Ansible installed.

You'll have to configure your own inventory file.

You can put plugins and a world in the plugins folder, and they will be deployed to the servers in the inventory.
