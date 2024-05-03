# Ansible Playbook for AWS EC2 Instance Setup

This repository contains example of Ansible playbooks that contains simple ansible playbook, deploy ec2 instance with nginx, and deploy multiple dockerize app

## Prerequisite
1. Config AWS credentials to as local awscli
    ```bash
    aws configure
    ```
2. Install ansible, python, pip, and boto/boto3 module



## How to Run

1. Enter to the root directory of ansible playbook
2. edit some parameter if needed on `main.yaml` or its roles
2. Run the playbook with the following command:

```bash
ansible-playbook -i hosts main.yaml
```
