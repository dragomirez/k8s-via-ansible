# k8s-via-ansible
Kubernetes installation with Ansible on CentOO7

Change ip addresses in "hosts" and "env_variables" files! 
 
1. To create a master run:
ansible-playbook -i hosts setup_master_node.yml 

2. Then create workers with: 
ansible-playbook -i hosts setup_worker_nodes.yml

3. If you go wrong delete everything with:  
ansible-playbook -i hosts clear_k8s_setup.yml

Then check your configuration and start again.


