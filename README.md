# Cheslin Jacobs | AWS Cloud Portfolio (AWS re/Start)

**GitHub:** [@CJacobsCreates](https://github.com/CJacobsCreates)  
**Target role:** Cloud Support Associate / Junior Cloud Engineer, working toward **AWS Certified Cloud Practitioner (CLF-C02)**

![AWS re/Start](https://img.shields.io/badge/AWS%20re%2FStart-in%20progress-FF9900?style=flat-square)
![CLF-C02](https://img.shields.io/badge/CLF--C02-studying-232F3E?style=flat-square)
![Labs](https://img.shields.io/badge/graded%20labs-60%2B%20completed-success?style=flat-square)

---

## About

This repo collects my hands-on work from **AWS re/Start**, a full-time, job-focused cloud program run with AWS. The course is built around **60+ graded labs in live AWS lab accounts**, using the AWS Management Console, the AWS CLI, Linux over SSH, and CloudFormation. I designed VPCs, put web tiers behind load balancers with Auto Scaling, moved an application database onto Amazon RDS, deployed infrastructure as code, and set up monitoring and alerts.

Each featured lab below says what was built, how the pieces fit together, and what I would do differently in production.

---

## Featured Labs

| Lab | What it shows | Outcome |
|---|---|---|
| [Configuring an Amazon VPC](Labs/Networking/Configuring-an-Amazon-VPC.md) | Networking | Built a custom VPC with public and private subnets, an internet gateway, a NAT gateway, route tables, and a bastion pattern, then fixed a broken route in a troubleshooting lab |
| [Scale and Load Balance](Labs/Architecture/Scale-and-Load-Balance.md) | High availability | Turned a single web server into an AMI, a launch template, an Application Load Balancer, and an Auto Scaling group across two Availability Zones |
| [Migrate to Amazon RDS](Labs/Databases/Migrate-to-Amazon-RDS.md) | Databases | Moved a café web app off its local database onto a private, managed MariaDB instance on Amazon RDS |
| [CloudFormation Automation](Labs/Automation/CloudFormation-Automation.md) | Infrastructure as code | Deployed and updated stacks layer by layer, debugged a failed stack, found drift, and wrote my own template for a challenge lab |
| [Monitoring with CloudWatch](Labs/Monitoring/Monitoring-with-CloudWatch.md) | Operations | Sent web-server logs and OS metrics to CloudWatch through the CloudWatch agent, with alarms and SNS notifications |
| [Introduction to Amazon EC2](Labs/Compute/Introduction%20to%20Amazon%20EC2.md) | Compute | Launched, secured, resized, and safely terminated a web server on EC2 |

---

## AWS Services and Skills

**Compute and scaling**  
![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Auto Scaling](https://img.shields.io/badge/EC2%20Auto%20Scaling-FF9900?style=flat-square)
![Elastic Load Balancing](https://img.shields.io/badge/Elastic%20Load%20Balancing-8C4FFF?style=flat-square)
![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)

**Networking**  
![Amazon VPC](https://img.shields.io/badge/Amazon%20VPC-8C4FFF?style=flat-square)
![Route 53](https://img.shields.io/badge/Amazon%20Route%2053-8C4FFF?style=flat-square&logo=amazonroute53&logoColor=white)

**Storage and databases**  
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Amazon EBS](https://img.shields.io/badge/Amazon%20EBS-569A31?style=flat-square)
![Amazon RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)
![Amazon DynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Amazon Aurora](https://img.shields.io/badge/Amazon%20Aurora-527FFF?style=flat-square)

**Management, monitoring, and security**  
![CloudFormation](https://img.shields.io/badge/AWS%20CloudFormation-E7157B?style=flat-square)
![CloudWatch](https://img.shields.io/badge/Amazon%20CloudWatch-E7157B?style=flat-square&logo=amazoncloudwatch&logoColor=white)
![CloudTrail](https://img.shields.io/badge/AWS%20CloudTrail-E7157B?style=flat-square)
![Systems Manager](https://img.shields.io/badge/AWS%20Systems%20Manager-E7157B?style=flat-square)
![IAM](https://img.shields.io/badge/AWS%20IAM-DD344C?style=flat-square)
![Amazon SNS](https://img.shields.io/badge/Amazon%20SNS-E7157B?style=flat-square)

**Tools**  
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20(MySQL%2FMariaDB)-4479A1?style=flat-square&logo=mysql&logoColor=white)
![AWS CLI](https://img.shields.io/badge/AWS%20CLI-232F3E?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**What I can do today**
- Design a two-tier VPC (public and private subnets, IGW, NAT, route tables, security groups, NACLs) and troubleshoot why traffic doesn't flow
- Build highly available web tiers with AMIs, launch templates, an ALB, and Auto Scaling across Availability Zones
- Provision and connect to Amazon RDS, migrate data with `mysqldump`, and write SQL (DDL, DML, joins, functions)
- Write, deploy, update, and debug CloudFormation templates, including rollbacks, drift, and retained resources
- Monitor workloads with CloudWatch metrics, logs, and alarms, plus SNS, CloudTrail, and Systems Manager
- Administer Amazon Linux: users and groups, permissions, processes, services, logs, cron, and Bash scripting
- Automate small tasks with Python and boto3, such as a Lambda function triggered by S3 that publishes to SNS

---

## Completed Lab Tracks

<details>
<summary><b>Full list of graded labs (click to expand)</b></summary>

| Track | Labs completed |
|---|---|
| **Cloud foundations and compute** | Introduction to Amazon EC2; Creating Amazon EC2 Instances; EC2 Instance Exercise (challenge); Troubleshoot Create Instance; Install and Configure the AWS CLI; Using AWS Systems Manager |
| **Architecture and scaling** | Scale and Load Balance your Architecture; Using Auto Scaling in AWS (Linux); Route 53 Failover Routing |
| **Serverless** | AWS Lambda Exercise (challenge); Working with AWS Lambda |
| **Networking** | Public and Private IP Addresses; Static and Dynamic IP Addresses; Create Subnets in a VPC; Networking Resources for a VPC; IP Troubleshooting Commands; Troubleshooting a Network Issue; Build your VPC and Launch a Web Server; Configuring an Amazon VPC; Troubleshoot a VPC |
| **Storage** | Working with Amazon EBS; Managing Storage; S3 Exercise (challenge); Work with Amazon S3 |
| **Databases** | Build Your DB Server and Interact with Your DB Using an App; Build and Access an RDS Server (challenge); Migrate to Amazon RDS; Database Table Operations; Insert, Update, and Delete Data; Selecting Data; Conditional Search; Working with Functions; Organizing Data; Introduction to Amazon Aurora; Introduction to Amazon DynamoDB |
| **Monitoring and governance** | Monitoring Infrastructure; Working with AWS CloudTrail; Managing Resources with Tagging; Optimize Utilization |
| **Infrastructure as code** | Automating Deployments with AWS CloudFormation; Troubleshooting CloudFormation Deployments; CloudFormation (challenge) |
| **Security** | Introduction to IAM; Network Hardening; Systems Hardening; Data Protection; Firewall and Malware; Monitor an EC2 Instance |
| **Linux and Bash** | Intro to Amazon Linux AMI; Linux Command Line; Users and Groups; Editing Files; File System; Working with Files; File Permissions; Managing Processes; Managing Services and Monitoring; Software Management; Managing Log Files; Working with Commands; The Bash Shell; Bash Shell Scripts; Bash Scripting (challenge) |
| **Python and DevOps** | Python Exercise (challenge); Explore the Value of Automation; Compare Automation and Orchestration; Evaluate a DevOps Tool (AWS CodeDeploy) |
| **AI/ML** | Amazon SageMaker: Training a Machine Learning Model (XGBoost) |

</details>

---

## Repository Structure

```
AWS-Restart/
├── README.md                     # You are here
├── Labs/
│   ├── Compute/                  # EC2 fundamentals
│   ├── Networking/               # VPC design and troubleshooting
│   ├── Architecture/             # Load balancing and Auto Scaling
│   ├── Databases/                # Amazon RDS migration
│   ├── Automation/               # CloudFormation
│   └── Monitoring/               # CloudWatch, SNS
└── Certification-and-Badges/     # Certification progress and badges
```

Every featured lab page includes real console screenshots from my lab runs. They come from temporary AWS re/Start lab accounts, with account IDs, ARNs, IP addresses and passwords blacked out or cropped.

---

## Certification and Badges

Certification progress is tracked in [Certification-and-Badges](Certification-and-Badges/README.md).

- **AWS Certified Cloud Practitioner (CLF-C02):** in preparation
- **AWS SimuLearn:** Database and Security modules (in progress)

---

## Let's Connect

I'm looking for entry-level cloud roles where I can support customers and keep building on AWS. If you're hiring, I'd be glad to talk through any of these labs.
