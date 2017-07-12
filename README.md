# Ansible UFW Role

An ansible role for installing and configuring UFW on debian systems.

## Usage:
    ---
    - hosts: all
      remote_user: root
    

Launch it in your computer for configure ufw with command: >> ansible-playbook playbook_name.yml 
or in other remote machines with: >> ansible-playbook -i "XXX.XXX.XXX.XXX," -k playbook_name.yml`

Where `XXX.XXX.XXX.XXX` is the IP address of the machine (is possible to set multiple IPs).


## License:
- MIT License


## Dependencies:
- None
