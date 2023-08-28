#DevOps Ansible Assignement
 
## prerequisite: 

sudo apt-get install ansible

pip install pywinrm

ensure that WinRM is configured properly 

Enable-PSRemoting -Force


## How to run the anisble playbook

ansible-playbook -i /etc/anisble/hosts windows_info.yml
