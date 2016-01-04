Role Name
========

Initialize Django Project.

Requirements
------------

Python2, virtualenv

Role Variables
--------------

vassals_dir: /etc/uwsgi/vassals  
supervisor_conf_dir: /etc/supervisor/conf.d  
project_name: {{project_name}}  



Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: django-servers
      remote_user: root
      roles:
         - { role: django_project, project_name: 'your_project_name' }

License
-------

MIT
