# Ansible Roles for Ubuntu and Fedora

## What you will find here

This is my collection of roles for Ubuntu and Fedora. Most of them are for the server versions, but I will also be adding roles intended for use with workstations.

## Server Management Roles

The following roles can be used for managing Ubuntu and Fedora Servers. They have been tested on Ubuntu 22.04+ LTS and Fedora 41 (Server + IoT).

* ansible_ssl_cloudflare : Sets up an SSL certificate via `certbot`, using `inventory_hostname` as the FQDN. Simply add your API key to a vault and run it in a playbook against the target host.