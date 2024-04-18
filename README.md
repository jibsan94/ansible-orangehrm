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

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/jibsan94/ansible-orangehrm">Ansible OrangeHRM</a> by <span property="cc:attributionName">Jibsan Rosa</span> is licensed under <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-ND 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nd.svg?ref=chooser-v1" alt=""></a></p>

Author Information
------------------

This Role was created by [Eng. Jibsan Joel Rosa Toirac](https://www.linkedin.com/in/jibsan94).