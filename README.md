Infile (project/inventory/hosts):
	Add ip address/FQDN to the group appserver
	Add pubkey/ansible_password for ssh connections

Infile (install_pyenv.yml):
	Change host to "appserver"

Run: ansible-playbook install_pyenv.yml
