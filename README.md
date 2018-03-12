# ansible-docker
## host file /etc/ansible/hosts
  `localhost ansible_connection=local ansible_ssh_user=[password] ansible_ssh_pass=[password]`
## run command with dynamic host 
   `$ansible-playbook playbook-start.yml --extra-vars "host=localhost"`
