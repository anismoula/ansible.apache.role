# Apache Ansible Role

Install Apache for Debian/Ubuntu Linux Servers

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (/vars/main.yml) :

Apache packages to install :
- apache_packages

Apache config variables for apache virtual hosts :
- server_name
- server_admin
- server_file_name
- document_root
- directory_server_files



## Dependencies

None

## Example Playbook

    - hosts: servers
      become: yes
      roles:
        - ansible.apache.php

## License

MIT

## Author Information

This role was created in 2018 by Moula Anis, System and Network Administrator.
