# Ansible_Task3

### Variables in ec2 Role:
* aws_instance_type
* ami_id
* aws_instance_tags
* subnet_id
* aws_region
* security_group_id

### Vault variable in ec2 Role:
* access_key
* secret_key

### Variables in webserver Role:
* package_name
* git_repo
* location

### Variables in haproxy Role:
* front(8080 port no)
* back(80 port no)


## Examples for ansible-playbook

* FILE_NAME.yml
```bash
hosts: HOSTS_NAME
roles:
 - role: ROLE_NAME
```

## Command
* For running ansible-playbook:

```bash
ansbile-playbook PLAYBOOK.yml
```
* For running ansible-playbook using vault:
```bash
ansbile-playbook --ask-vault-pass PLAYBOOK.yml
```



# Detailed explanation 
[AnsibleTask3](https://medium.com/@rootritesh/configure-lb-haproxy-using-ansible-roles-on-aws-bb1350d0b30a)
