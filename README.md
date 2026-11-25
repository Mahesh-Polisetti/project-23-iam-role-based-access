# Project 23 - IAM Role-Based Access

## Objective
Configure an IAM role for an EC2 instance to access Amazon S3 without storing AWS access keys on the instance.

## AWS Services
- Amazon EC2
- AWS IAM
- Amazon S3
- AWS Systems Manager (SSM)

## Implementation
1. Created an IAM role for EC2.
2. Attached S3 access permissions.
3. Created and attached an instance profile.
4. Associated the instance profile with EC2.
5. Configured Systems Manager Session Manager access.
6. Verified the assumed IAM role using AWS STS.
7. Verified S3 access using AWS CLI.
## Verification Commands
##```bash
##aws sts get-caller-identity
##aws s3 ls
