# Ansible OpenVAS Playbook

Installing OpenVAS 8 on Ubuntu 14.04 Server from source

Base on:
http://www.mockel.se/index.php/2015/04/openvas-8-on-ubuntu-server-14-04/
https://github.com/odyssey4me/ansible-openvas

# Install

```
# apt-get update
# apt-get install -y git ansible
$ git clone https://github.com/somathor/ansible-openvas.git
$ cd ansible-openvas
$ ansible-playbook playbook.yml -i hosts --ask-sudo-pass
```
