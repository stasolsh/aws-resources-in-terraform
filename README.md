![Terraform](https://img.shields.io/badge/Terraform-IaC-purple)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![DevOps](https://img.shields.io/badge/DevOps-Friendly-blue)

# AWS Infrastructure as Code with Terraform

> Practical Terraform examples for provisioning and managing AWS infrastructure components used in modern cloud-native systems.

This repository contains hands-on Infrastructure-as-Code examples for networking, compute, storage, monitoring, messaging, security, and scalable cloud architectures using Terraform and AWS.

## Why This Repository Exists

Modern backend and cloud-native systems rely heavily on Infrastructure as Code.

This repository was created to:
- practice Terraform and AWS infrastructure design
- understand cloud architecture building blocks
- explore infrastructure automation
- demonstrate reusable infrastructure patterns
- strengthen DevOps and platform engineering skills

| Resource | Description |
|---|---|
| [VPC & Networking](vpc.tf) | Configure isolated networking environments, subnets, routing, and gateways |
| [EC2](ec2.tf) | Provision virtual machines and compute resources |
| [RDS](rds.tf) | Deploy managed relational databases |
| [S3](s3.tf) | Configure scalable object storage |
| [SQS](sqs.tf) | Create message queues for asynchronous communication |
| [SNS](sns.tf) | Configure pub/sub messaging and notifications |
| [Lambda](lambda.tf) | Deploy serverless compute functions |
| [IAM](iam.tf) | Manage roles, policies, and permissions |
| [DynamoDB](dynamodb.tf) | Provision NoSQL databases |
| [CloudFront](cloudfront.tf) | Configure CDN and edge content delivery |
| [Load Balancer](loadbalancer.tf) | Configure traffic distribution across services |
| [CloudWatch](cloudwatch.tf) | Set up monitoring, metrics, and logging |
| [ECR](ecrrepository.tf) | Manage Docker container repositories |
| [Route53](route53.tf) | Configure DNS routing and domains |
| [SSM](ssm.tf) | Store configuration and secrets securely |
| [Auto Scaling](autoscaling.tf) | Configure automatic scaling policies to dynamically adjust compute capacity based on workload |
| [CloudFront](cloudfront.tf) | Configure CDN distribution, caching, and edge content delivery for global performance optimization |

## Example Cloud Architecture

```text
Internet
↓
CloudFront
↓
Load Balancer
↓
EC2 / Lambda
↓
RDS / DynamoDB
↓
S3 / SQS / SNS

## Getting Started

### Initialize Terraform
```

```bash
terraform init
terraform validate
terraform plan
terraform apply
```


