# debug_collect

Generates debug information on switches and downloads it to ansible control node local directory.

Requirements:
ansible.netcommon (i.e. ansible-galaxy collection install ansible.netcommon)
python3-paramiko / python3-netmiko (i.e. sudo apt install python3-paramiko && sudo apt install python3-netmiko)

ansible_vault and/or ssh key authentiocation can be used to not expose ansible_password.
