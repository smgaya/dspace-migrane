# Ansible playbook for DSpace deployment

The aim of this repo is to automate dspace deployment, configuration and cutomization in one go. It is more specific to what we want it to be for R&D institution in Tanzania. 

## Assumptions
A few assumptions are made:

- You have installed ansible on your local machine
- The target server is running a clean Ubuntu 12.04 LTS
- Your DSpace code is hosted in a public git repository (ie github)
- The target server will use Apache httpd in front of Tomcat (reverse proxy)
- The target server will use Oracle JDK 1.7 instead of OpenJDK

## Pre-requisite

This are pre installation packages.

- thi 

## Installation 

This is what is installed.



## Configuration 

This is what is going to be configured ..



## Customization 

This is customised based on the university.

## Usage
Edit the `hosts` and `host_vars` appropriately, and then test to see if ansible can reach your host:

    ansible -i hosts dspace -m ping

Then try to run the playbook:

    ansible-playbook -i hosts dspace.yml -K


## To do
There is still some work to do:

- make everything a variable for jinja templating!
- troubleshoot / fix ant step
- add more plays for iptables and other server hardening stuff

## License

The contents of this repository are [Unlicensed](http://unlicense.org/UNLICENSE).
# dspace-migrane
