# Ansible  Tower Demokit
Run this playbook to quickly spin up a demo environment on top of an Ansible workshop deployment. Includes the below Job Templates:
- Configuration Management
- Fact Scan
- Gather Debug Info
- Grant Sudo
- Hardening
- Patching
- Security Patching

## How To Use
1. Change `ansible_host`, `ansible_user`, `ansible_password` in inventory file
2. Run `ansible-playbook -i inventory playbook.yml`
3. Login to Ansible Tower
4. Run `SERVER / Configuration Management` before other jobs to configure nodes

## Requirements
- ansible
- tower-cli
- sshpass

To install sshpass on mac use:
brew install https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb