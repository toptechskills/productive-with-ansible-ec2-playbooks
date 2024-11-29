# Productive with Ansible - EC2 Playbooks

Playbooks to create and destroy EC2 instances for Chapter 3 of the [Productive with Ansible course](https://learn.toptechskills.com/courses/productive-with-ansible).

**`ec2_create.yml`**: creates a set of publicly-accessible ec2 instances and all supporting infrastructure (VPC, subnets, security groups, etc.)

**`ec2_destroy.yml`**: destroys all infrastructure created by `ec2_create.yml`

