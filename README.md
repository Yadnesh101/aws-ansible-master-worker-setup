# AWS Ansible Master-Worker Setup

This project automates the creation of a master-worker architecture on AWS using Ansible.

## Features
- Launch EC2 instances using Ansible.
- Configure one instance as the master node.
- Configure the other instances as worker nodes.
- Password-less SSH setup for Ansible communication.

## Requirements
- AWS CLI and Ansible installed.
- IAM role with EC2 permissions.
- A valid key pair for SSH.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/aws-ansible-master-worker-setup.git
