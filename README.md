# 4640-w7-lab

1. Tuan Thanh Nguyen - A01335362
2. Sina Abbasnia - A01377364

- Generate key command: `ssh-keygen -t rsa -b 4096 -C "IT Provision Lab7" -f ~/.ssh/aws`. The command generate key by rsa algo, size of 4096 bits, with some comment -C and name is aws

- Ansible playbook command: `ansible-playbook playbook.yml -i inventory/hosts.yml`. This will run an Ansible playbook to automate tasks on remote servers with specific hosts and playbook file.

![image](https://github.com/user-attachments/assets/6e46cb55-8688-4361-994f-1fb9d16b6d0b)
