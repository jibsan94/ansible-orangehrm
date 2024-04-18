Ansible Role: OrangeHRM
=========

This Role installs OrangeHRM on a PC. 

Requirements
------------

It needs no extra roles.

Role Variables
--------------

To make changes to the OrangeHRM go to:

    defaults/main.yml

The below variables are for securing the MariaDB installation:

    mysql_root_new_password: new_root_password
    mysql_user: orangehrm
    mysql_user_password: mysql_password
    mysql_orange_db: orangehrm_db
        
Below are the configurations of the OrangeHRM system:

    orange_web_server_path: /var/www/html
    admin_email: admin@skijah.com
    orange_domain_name: rrhh.skijah.com


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: webservers
      roles:
         - jibsan94.ansible_orangehrm

License
-------

Ansible OrangeHRM © 2024 by Jibsan Rosa is licensed under CC BY-NC-ND 4.0 

Author Information
------------------

This Role was created by [Eng. Jibsan Joel Rosa Toirac](https://www.linkedin.com/in/jibsan94).
