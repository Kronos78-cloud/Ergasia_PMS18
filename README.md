# PMS18
# Hello_World

Make sure you have [Ansible installed] on your control node, which can be your local machine or a remote server dedicated to running Ansible.
You'll need one Ubuntu 18.04 server to serve as node / host.

1. Clone this repository
2. Set up your inventory file - you can use `inventory-example` as base
3. Adjust values on your `group_vars/all.yml` file
4. Run the `server-setup.yml` playbook to set up the LEMP server
5. Run the `laravel-deploy.yml` playbook to deploy the demo Laravel application
6. Access your server's IP address or hostname to test the setup

