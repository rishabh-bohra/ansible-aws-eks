# ansible-aws-eks
ansible-file to create aws eks cluster 

This repository contain roles for creating ansible eks cluster and all its prerequisites like 

- sshkey 

- iam-role 

- vpc 

- subnet 

- internet gateway

- route table 

- security group

Prerequesites for this repository are

- Python 2.6+

- pip

- boto

- boto3

- aws-cli

- ansible-version 2.7+

To edit any variable for this repository use "variable" file its the master variable file for this Project


To run this repository use command 

 ```bash
 ansible-playbook launch.yml
```
