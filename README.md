# Ansible  Tower Demokit
Run this playbook to quickly spin up a demo environment on top of an Ansible workshop deployment.

## How To Use
1. Change `ansible_host`, `ansible_user`, `ansible_password` in inventory file
2. Run `ansible-playbook -i inventory playbook.yml`

## Requirements
- ansible
- tower-cli
- sshpass

To install sshpass on mac use:
brew install https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb