# Cooperation between Ansible and NAPALM

## Retreive facts data

* Get facts data
```
ansible-playbook -i hosts playbooks/get-facts-data.yml
```

## Add Config

* Commit merge the system configuration
```
ansible-playbook -i hosts playbooks/add-config.yml
```


