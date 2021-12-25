# Pihole Ansible
ansible-galaxy install -r requirements.yml

ansible-playbook main.yml -i hosts.ini -e @vault.yml
