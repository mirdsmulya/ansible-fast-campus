# Ansible Playbook for AWS EC2 Instance Setup

This repository contains example of Ansible playbooks that contains simple ansible playbook, deploy ec2 instance with nginx, and deploy multiple dockerize app

## Prerequisite
1. export AWS credentials to as local env variable
    ```bash
    export AWS_ACCESS_KEY_ID={key}
    export AWS_SECRET_ACCESS_KEY={key}
    ```
2. Install python, pip, and boto3 module



## How to Run

1. Enter to the root directory of ansible playbook
2. edit some parameter if needed on `main.yaml` or its roles
2. Run the playbook with the following command:

```bash
ansible-playbook -i hosts main.yaml
```
