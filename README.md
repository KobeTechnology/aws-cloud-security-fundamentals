
# AWS Cloud Security Fundamentals Project

## Overview
This project demonstrates foundational cloud security skills using Amazon Web Services (AWS).
A secure cloud environment was designed and deployed using IAM, network segmentation, and audit logging to follow security best practices.

## Architecture
- Virtual Private Cloud (VPC) with public and private subnets
- Public EC2 web server with restricted administrative access
- Security Groups enforcing least-privilege network rules
- IAM users with MFA and role-based permissions
- CloudTrail enabled for audit logging

## Security Controls Implemented
- Multi-Factor Authentication (MFA) on root and IAM users
- Least-privilege IAM policies
- Restricted SSH access (IP-based)
- Public HTTP access only where required
- Centralized logging using AWS CloudTrail

## Misconfigurations Identified and Remediated
- Public SSH access was identified as a security risk and restricted
- Over-permissioned IAM access was corrected to least privilege

## Tools & Technologies
- AWS EC2
- AWS IAM
- AWS VPC
- AWS CloudTrail
- Amazon Linux
- Security Groups

## What I Learned
This project strengthened my understanding of cloud security fundamentals, including identity management, network segmentation, logging, and secure cloud design principles.
