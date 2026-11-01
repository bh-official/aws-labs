# AWS Solutions Architect – Hands-on Labs

My hands-on journey toward the **AWS Certified Solutions Architect – Associate** certification.
Every lab is built in a real AWS console (AWS Skill Builder / SimuLearn lab accounts) and documented with
the architecture, the exact steps, the configuration used, and what I learned.

## Lab index

| # | Lab | Services | Status |
|---|-----|----------|--------|
| 01 | [Static website hosting on Amazon S3](labs/01-s3-static-website/README.md) | S3, bucket policies, Block Public Access | ✅ Done |
| 02 | IAM users, groups, policies, roles | IAM | ⏳ Planned |
| 03 | Custom VPC with public & private subnets | VPC, IGW, route tables, NAT | ⏳ Planned |
| 04 | Web server on EC2 | EC2, security groups, EBS | ⏳ Planned |
| 05 | High availability with ALB + Auto Scaling | ELB, Auto Scaling, multi-AZ | ⏳ Planned |
| 06 | Managed databases | RDS (Multi-AZ), DynamoDB | ⏳ Planned |
| 07 | Serverless API | Lambda, API Gateway, DynamoDB | ⏳ Planned |
| 08 | Decoupled architecture | SQS, SNS, EventBridge | ⏳ Planned |
| 09 | Monitoring & security | CloudWatch, CloudTrail, KMS | ⏳ Planned |
| 10 | Infrastructure as Code & edge | CloudFormation, Route 53, CloudFront | ⏳ Planned |

## Repo layout

```
labs/
  NN-lab-name/
    README.md        # architecture, steps, config, lessons learned
    *.json           # policies / config used in the lab
    screenshots/     # console screenshots (account IDs redacted)
```

## Notes

- All labs ran in temporary, sandboxed lab accounts — no personal AWS account or billing involved.
- Account IDs and other identifiers are redacted from screenshots and configs.
