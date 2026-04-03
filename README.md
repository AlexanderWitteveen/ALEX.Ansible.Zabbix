# Ansible Collection - alex.zabbix collection
Documentation for the collection.

# Install
ansible-galaxy collection install git+https://github.com/AlexanderWitteveen/ALEX.Ansible.Zabbix.git

# Use playbook
vars="{\"args_dhcpipaddress\":\"hostip\"}"  
export ANSIBLE_CONFIG=/etc/ansible/ansible.cfg  
ansible-playbook alex.zabbix.helloworld -vv --extra-vars "$vars"
