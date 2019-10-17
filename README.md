# ansible
ansible conf file location = /root/ansible/ansible.cfg
all files are in /root/ansible/ansible.cfg

to run:-
ansible-playbook use.yml -i hosts #here i am giving path to the hosts file , inventory location is not in ansible.cfg bidefault

output:
it will generate myhosts file with output:
HOST= 1.2.3.4
HOST= 2.3.4.4
HOST= 5.6.7.8
HOST= 8.5.4.3
HOST= 7.4.3.3
