# ansible-alpha
small ansible project from kodekloud
RUN ANSIBLE COMMAND
ansible -i inventory.yml serv1 -m "ping"

RUN ANSIBLE PLAYBOOK
ansible-playbook -i inventory.yml apache_play.yml
