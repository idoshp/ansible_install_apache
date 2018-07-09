#### Description

- Ansible playbook to create apache node.


#### prerequisites

- Ansible Installed.
- Store the .pem key file of the target server in the Ansible server where you execute the playbook.
- Create inventory.ini file with the following:
-   [node1]
-   (public dns) ansible_ssh_user=(target user)

#### Installation

- execute the playbook: ansible-playbook -i inventory.ini apache_playbook.yml --private-key (path to key file)
