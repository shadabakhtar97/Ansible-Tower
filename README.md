# Ansible-Tower
Learn Ansible Tower Deep Dive

`cat /etc/system-release`

Red Hat Enterprise Linux release 8.6 (Ootpa)


Bundled installer:
--------------------
https://releases.ansible.com/ansible-tower/setup-bundle/

`wget https://releases.ansible.com/ansible-tower/setup-bundle/ansible-tower-setup-bundle-3.6.2-1.el8.tar.gz

tar -zxvf ansible-tower-setup-bundle-3.6.2-1.el8.tar.gz`

admin_password='xxxxxxxxxx'

pg_password='xxxxxxxxxxx'

rabbitmq_password='xxxxxxxxxxx'

`sudo ./setup.sh`

Access Ansible Tower UI/Web Based:
-----------------------------------
http://(ansible-tower-vm-public-ip-address)/

Username: admin

Password: xxxxxxxxxxx

Check Script Status:
---------------------
`ps -ef|grep sh`
