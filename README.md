Ansible-Role-NTP
=========

Super Easy Role to set timezone and synchronize time with NTP server.

Role Variables
--------------
```
ntp_zone: GMT0
ntp_city:
```


- Change ```ntp_zone``` and ```ntp_city``` in ```vars/``` according to your needs.
- [Optional] You may use same Parameters with global_vars file or with primary_vars file, ansible will overwrite role specified in vars file in that case.


Example Playbook
----------------
```
    - hosts: YOUR-HOST-OR-GROUP
      roles:
    	- NTP
```

Deploying
----------------
- ```ansible-playbook playbook.yml```

Tip:
----------------
- If you are working with Large Devops/Administrators Team then plese consider using UTC timezone.
- Read More - http://yellerapp.com/posts/2015-01-12-the-worst-server-setup-you-can-make.html


License
-------
MIT


Author Information
------------------
###Rahul Sharma

[Github](https://github.com/Rahulsharma0810)

[Facebook](https://www.facebook.com/rahulsharma0810)