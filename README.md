# Pihole Ansible
ansible-galaxy install -r requirements.yml

ansible-playbook main.yml -i hosts.yml -e @vault.yml --ask-vault-pass
