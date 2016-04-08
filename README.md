ansible-playbook --extra-vars "user=frob wait_for_port=false" -K initial.yml --ask-vault-pass
ansible-playbook --extra-vars "user=frob wait_for_port=false" provision.yml
