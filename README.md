# AWS CLI SCRIPTS

A collection of useful AWS CLI shell scripts for managing cloud resources, automating tasks, and simplifying day-to-day DevOps operations. Includes scripts for S3, EC2, IAM, ELB, VPC, and more.

## 00 - create_vpc.sh

This script automates the creation of a complete VPC setup in AWS, including subnets, internet gateway, and route tables.  
It checks for existing resources before creating new ones, ensuring idempotent and error-handled infrastructure provisioning.

## 01 - Route 53 - Create Public DNS record for EC2

route53_create_public_dns.sh file

This script automates Route 53 DNS management by creating a hosted zone (if not existing), fetching an EC2 instance’s public IP, and creating an A record to map a subdomain to that instance.
