# ansible-debian-master

Full working debian workstation

Prerequisities:
- ansible user needs to be created on individual hosts that this playbook will be run on (permission elevated) - file added to /etc/sudoer.d <10-ansibleuser>
- ssh & python needs to be installed on hosts before running this playbook.
- ssh keys to be added to hosts - ssh-copy-id <hostname>
- host machine needs to be added to ansible hosts file

Note!
- PyCharm install is not complete. Requires install script <./pycharm.sh> to be executed in /opt/pycharm-community-      2018.3.4/bin
