# debian11-kvm
Install and config kvm on Debian11 (for my lab server)

Only run when setup new physical server

# Run:
ansible-playbook main.yaml -i inventory -D -e 'ansible_python_interpreter=/usr/bin/python3'
