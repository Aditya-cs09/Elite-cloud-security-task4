# Cloud Security Implementation on AWS

## Overview
This project demonstrates the implementation of basic cloud security practices on AWS, including IAM access control, secure S3 configuration, and data encryption.

## Objective
- Implement Identity and Access Management (IAM) policies
- Secure S3 storage by restricting public access
- Enable encryption for data protection

## Services Used
- AWS IAM
- AWS S3

## Implementation Steps
1. Created an IAM user with limited access
2. Attached AmazonS3ReadOnlyAccess policy to enforce read-only permissions
3. Created an S3 bucket for secure storage
4. Blocked all public access to the bucket
5. Enabled versioning for data recovery and protection
6. Enabled Server-Side Encryption (SSE-S3) for data at rest

## Security Features Implemented
- IAM Access Control: Restricted user permissions using predefined policies
- Public Access Block: Prevented unauthorized access to S3 bucket
- Data Encryption: Enabled SSE-S3 to encrypt stored data
- Versioning: Protected against accidental deletion or modification

## Results
- Secure S3 storage environment successfully configured
- Access restricted based on IAM roles and policies
- Data stored in encrypted format using AWS-managed keys
- Improved overall cloud security posture

## Screenshots
- IAM User and Policy Configuration
- S3 Bucket Permissions
- Public Access Block Settings
- Encryption Configuration

## Learnings
- Understood IAM policy-based access control
- Learned how to secure cloud storage using S3 best practices
- Gained knowledge of data encryption mechanisms in AWS
- Explored practical implementation of cloud security fundamentals
