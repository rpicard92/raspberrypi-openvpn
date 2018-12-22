# RaspberryPi_VPN

## What: 
   - An Ansible meta-automation solution for automatically creating and OPEN-VPN Solution on a Raspberry Pi.

## When:
   - Last Updated: 2018-06-07
   - First Started: 2018

## Why:
   - Virtual-Private-Networks (VPNs) are wonderful solutions for accessing a home cloud on the road or just browsing securely. 

## Who: 
   - Developed for anyone who wants to have a low cost home VPN solution.

## How:
- 1. Install ansible
    - a. sudo apt-get update
    - b. sudo apt-get install software-properties-common
    - c. sudo apt-add-repository ppa:ansible/ansible
    - d. sudo apt-get update
    - e. sudo apt-get install ansible
- 2. Put the "hosts" file in the /etc/ansible directory
- 3. Use the command ssh-keygen to create an ssh key
- 4. Option 1: Run these commands sudo -i, cd ~/.ssh, sftp user@XXX.XXX.XXX, put id_rsa.pub
- 5. Option 2: Run this command: ssh-copy-id user@XXX.XXX.XXX
- 6. Run the ansible script with: ansible-playbook main.yml
