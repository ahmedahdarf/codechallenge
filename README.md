# codechallenge
In this project  i was using ubuntu vm in which i install docker,docker-compose and ansible
The main idea is to run a 3 containers (haproxy, nginx, php app) and prevent DDOS attack

#### create a user name ahmed 
## prerequisites

#### you have to install 
1.  docker
2.  ansible

## Execution
 ### you have to change the ip adresse ad user  in the hosts file 
#### run the folling command
 
##### ansible-playbook  -i hosts code_challenge_playbook.yml
this command will start an ansible playbook that contain a task to run a docker-compoose 
