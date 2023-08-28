#DevOps Ansible Assignement
 
## prerequisite: 

sudo apt-get install ansible

pip install pywinrm

ensure that WinRM is configured properly 

Enable-PSRemoting -Force


## How to run the anisble playbook

ansible-playbook -i /etc/anisble/hosts windows_info.yml

**NOTE : **

This having some issues on testing .. winRM version mistach realted error. hpwever i will check and try to fix it . 
<img width="401" alt="image" src="https://github.com/rpasup/DevOps_Assignment_Ansible/assets/17158135/b40f7561-d8f4-458a-93bc-039e84b1a0fd">

