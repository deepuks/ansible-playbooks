# ansible-playbooks
Ansible playbooks for my daily use

# Running showduplicates.yml
$ ansible-playbook showduplicates.yml --extra-vars "package=<package_name> variable_hosts=<inventory_host_group/IP>"

# Running docker.yml to launch a RHEL 7.3 image on a host
$ ansible-playbook docker-new.yaml
