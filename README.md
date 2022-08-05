# Ansible1
Three roles are created 
1. pre
2. mongodb
3. nodejs

Then perform for role pre
cd /etc/anisible/


root@EPINHYDW0540:/etc/ansible/roles# sudo ansible-galaxy init samplerolename
- Role samplerolename was created successfully
root@EPINHYDW0540:/etc/ansible/roles# ls
baseline  baseline1  samplerolename
root@EPINHYDW0540:/etc/ansible/roles# cd samplerolename
root@EPINHYDW0540:/etc/ansible/roles/samplerolename# ls
README.md  defaults  files  handlers  meta  tasks  templates  tests  vars
root@EPINHYDW0540:/etc/ansible/roles/samplerolename# cd ..
root@EPINHYDW0540:/etc/ansible/roles# sudo ansible-galaxy init pre
- Role pre was created successfully
root@EPINHYDW0540:/etc/ansible/roles# sudo ansible-galaxy init mongodb
- Role mongodb was created successfully
root@EPINHYDW0540:/etc/ansible/roles# sudo ansible-galaxy init nodejs
- Role nodejs was created successfully
root@EPINHYDW0540:/etc/ansible/roles# cd pre
root@EPINHYDW0540:/etc/ansible/roles/pre# cd tasks
root@EPINHYDW0540:/etc/ansible/roles/pre/tasks# sudo vi main.yml
root@EPINHYDW0540:/etc/ansible/roles/pre/tasks# cd ..
root@EPINHYDW0540:/etc/ansible/roles/pre# cd ..
root@EPINHYDW0540:/etc/ansible/roles# cd mongodb
root@EPINHYDW0540:/etc/ansible/roles/mongodb# cd tasks
root@EPINHYDW0540:/etc/ansible/roles/mongodb/tasks# sudo vi main.yml
root@EPINHYDW0540:/etc/ansible/roles/mongodb/tasks# cd ..
root@EPINHYDW0540:/etc/ansible/roles/mongodb# cd ..
root@EPINHYDW0540:/etc/ansible/roles# cd nodejs
root@EPINHYDW0540:/etc/ansible/roles/nodejs# cd tasks
root@EPINHYDW0540:/etc/ansible/roles/nodejs/tasks# sudo vi main.yml
root@EPINHYDW0540:/etc/ansible/roles/nodejs/tasks# cd ..
root@EPINHYDW0540:/etc/ansible/roles/nodejs# cd ..
root@EPINHYDW0540:/etc/ansible/roles# cd ..
root@EPINHYDW0540:/etc/ansible# sudo vi meanstack.yml


