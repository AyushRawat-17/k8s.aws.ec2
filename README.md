# Kubernetes AWS EC2  

This role used for Provisioning of  Security Group and  EC2 instance on AWS Cloud for Kubernetes Master and Kubernetes Worker Nodes of AMI **Amazon Linux 2** in Region **ap-south-1**  with Instance type **t2.micro**. It launches 1 Master Node and Worker Nodes according to the specfied requirement.

## Requirements

- boto and boto3 python Library.
- AWS CLI must be configured in the OS with some profile.
- Precreated private key also required. 

## Role Variables
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


## Example Playbook

- hosts: localhost
  gather_facts: no
  roles:
    - role: k8s.aws.ec2

## License
BSD
## Author Information
  **Author Name:**   Ayush Rawat
  **Contacts:** 11as1913001@gmail.com

