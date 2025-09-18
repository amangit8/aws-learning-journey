# aws-learning-journey
Tracking my AWS cloud practitioner study progress

## Day 1
- created AWS account
- started watching FreeCodeCamp AWS course
- set up github

## Day 2
- Learned about AWS Global Infrastructure and Basics of EC2

## Day 3 – AWS Metered Billing & Innovation Waves

## Metered Billing
- AWS charges on a **pay-as-you-go** model (like electricity or water).
- No upfront fixed costs, only pay for what you use.
- **Main billing factors:**
  - Compute time (e.g., EC2 instance hours)
  - Storage (e.g., GBs in S3)
  - Data transfer (outbound traffic)
- **Free Tier examples:**
  - EC2 t2.micro: 750 hours/month (12 months)
  - S3: 5GB free storage
  - Lambda: 1M requests free per month

## Innovation Waves
- Cloud computing drives rapid **innovation cycles**.
- Businesses can experiment and scale fast without huge upfront investment.
- Companies save time + money, reinvest faster, and stay competitive.

## Day 4 – AWS Shared Responsibility Model

## What AWS is responsible for (Security *of* the Cloud)
- Physical data centers
- Networking, hardware, and global infrastructure
- Managed services (like patching the host OS, hypervisors)

## What the Customer is responsible for (Security *in* the Cloud)
- Configuring resources correctly
- Managing data, applications, and operating systems
- Setting up permissions (IAM users, roles, policies)
- Encrypting data when required

## Examples
- AWS secures the physical server → I must secure my EC2 instance (OS updates, firewall rules).
- AWS provides S3 storage → I must set correct bucket permissions (public/private).
- AWS manages hardware security → I manage IAM users and access keys.

## Key Insight
- **Misconfigurations are the biggest risk.**  
  Example: Companies have exposed data because they left an S3 bucket public.  
  AWS didn’t fail — the user didn’t configure it properly.
