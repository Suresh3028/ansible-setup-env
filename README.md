# from repository root
ansible-playbook -i inventory.ini setup-environment.yml --tags "common,java,maven,repo,build"


# If using remote server with key
ansible-playbook -i inventory.ini setup-environment.yml