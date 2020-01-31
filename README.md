# awesome-aws [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome things related to the AWS, AWS CDK, and AWS Training and Certification.

> DISCLAIMER: this is a personal project and not affiliated with Amazon or AWS.

## Contents

- [awesome-aws ![Awesome](https://awesome.re)](#awesome-aws-img-srchttpsawesomere-altawesome)
  - [Contents](#contents)
  - [Training](#training)
    - [Security](#security)
    - [Object Storage](#object-storage)
    - [Compute and Block Storage](#compute-and-block-storage)
    - [Load Balancing, CloudWatch and AutoScaling](#load-balancing-cloudwatch-and-autoscaling)
    - [Backup and Archival](#backup-and-archival)
    - [Networking, VPC and Route53](#networking-vpc-and-route53)
    - [Relational Databases](#relational-databases)
    - [Non-Relational Databases](#non-relational-databases)
    - [Queueing and Notification](#queueing-and-notification)
    - [CDN/Edge Services](#cdnedge-services)
    - [Object Storage and Hosting Static Websites](#object-storage-and-hosting-static-websites)
    - [Solutions for Databases, Disaster Recovery and Web Application Hosting](#solutions-for-databases-disaster-recovery-and-web-application-hosting)
    - [Architecting for High Availability and Scalability](#architecting-for-high-availability-and-scalability)
    - [Elastic Beanstalk](#elastic-beanstalk)
    - [DevTools](#devtools)
    - [CodeDeploy](#codedeploy)
    - [OpsWorks](#opsworks)
    - [EC2 Container Service and Registry](#ec2-container-service-and-registry)
    - [Lambda, API Gateway, and Serverless Computing](#lambda-api-gateway-and-serverless-computing)
    - [General Principles for Big Data / Analytics](#general-principles-for-big-data--analytics)
    - [Amazon Redshift](#amazon-redshift)
    - [Elastic Map/Reduce (EMR)](#elastic-mapreduce-emr)
    - [Amazon Kinesis](#amazon-kinesis)
    - [Amazon Elasticsearch Service](#amazon-elasticsearch-service)
    - [DynamoDB for Big Data](#dynamodb-for-big-data)
    - [Introduction to Mobile and IoT](#introduction-to-mobile-and-iot)
    - [Solutions and Architectures for Mobile, IoT, and Big Data](#solutions-and-architectures-for-mobile-iot-and-big-data)
    - [Additional Resources](#additional-resources)
  - [Contribute](#contribute)
  - [License](#license)

## Training

This section aims to call out free training materials available across the web.

### Security

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | Understanding AWS Security | 1 hour | <https://www.youtube.com/watch?v=rei30obkaBc> |
| :tv: | Journey Through the Cloud - Security Best Practices | 1 hour | <https://www.youtube.com/watch?v=rXPyGDWKHIo> |
| :closed_book: | Read the AWS Overview of Security Processes Whitepaper | 2 hours | <https://d0.awsstatic.com/whitepapers/aws-security-whitepaper.pdf> |
| :tv: | re:Invent 2013 Access Control for the Cloud:  AWS Identity and Access Management (IAM) | 1 hour | <https://www.youtube.com/watch?v=4OpZmBp9S0k> |
| :tv: | re:Invent 2015 IAM Best Practices to Live By | 1 hour | <https://www.youtube.com/watch?v=\_wiGpBQGCjU> |
| :tv: | AWS re:Invent 2015 (SEC318) AWS CloudTrail Deep Dive | 45 minutes | <https://www.youtube.com/watch?v=t0e-mz\_I2OU> |
| :tv: | AWS re:Invent 2017: AWS Security State of the Union (SID326) | 1 hour | <https://www.youtube.com/watch?v=Wvyc-VEUOns> |
| :tv: | AWS re:Invent 2017: NEW LAUNCH! Introduction to Amazon GuardDuty (SID218) | 50 minutes | <https://www.youtube.com/watch?v=Imjbh0WPSR4> |
| :tv: | AWS re:Invent 2017: The AWS Philosophy of Security (SID322) | 55 minutes | <https://www.youtube.com/watch?v=KJiCfPXOW-U> |
| :tv: | AWS re:Invent 2017: Best Practices for Managing Security Operations on AWS (SID206) | 1 hour | <https://www.youtube.com/watch?v=gjrcoK8T3To> |
| :tv: | AWS re:Invent 2017: Living on the Edge, It's Safer Than You Think! Building Strong (CTD310) | 1 hour | <https://www.youtube.com/watch?v=U-Xc3k0pmfo> |
| :tv: | AWS re:Invent 2017: Security and DevOps: Agility and Teamwork (SID315) | 1 hour | <https://www.youtube.com/watch?v=noBJdxlSYvw> |
| :tv: | AWS re:Invent 2017: Incident Response in the Cloud (SID319) | 1 hour | <https://www.youtube.com/watch?v=ufmgB9M2WII> |
| :tv: | AWS re:Invent 2017: Embedding Security into DevOps on AWS with Automation Toolsets (SID347) | 40 minutes | <https://www.youtube.com/watch?v=Gz68BlZm7ZQ> |
| :tv: | AWS re:Invent 2017: Architecting Security and Governance Across a Multi-Account Strategy (SID331) | 1 hour | <https://www.youtube.com/watch?v=71fD8Oenwxc> |
| :tv: | AWS re:Invent 2017: Security Anti-Patterns: Mistakes to Avoid (FSV301) | 45 minutes | <https://www.youtube.com/watch?v=tzJmE\_Jlas0> |
| :tv: | AWS re:Invent 2017: How Chick-fil-A Embraces DevSecOps on AWS (SID306) | 55 minutes | <https://www.youtube.com/watch?v=\_0BCJLIxowQ> |
| :tv: | AWS re:Invent 2017: Force Multiply Your Security Team with Automation and Alexa (SID302) | 50 minutes | <https://www.youtube.com/watch?v=e6sokCFRlns> |
| :tv: | AWS re:Invent 2017: Automating DDoS Response in the Cloud (SID324) | 57 minutes | <https://www.youtube.com/watch?v=6pQ3j4IcpY8> |
| :tv: | AWS re:Invent 2019: The fundamentals of AWS cloud security (SEC205-R2) | 57 minutes | <https://www.youtube.com/watch?v=QMBkq6MrT2w> |
| :tv: | AWS re:Invent 2019: Provable access control: Know who can access your AWS resources (SEC343-R) | 50 minutes | <https://www.youtube.com/watch?v=6DX7p-OirGU> |
| :tv: | AWS re:Invent 2019: Getting started with AWS identity (SEC209-R1) | 1hr| <https://youtu.be/Zvz-qYYhvMk>
| :tv: | AWS re:Invent 2019: Leadership session: AWS identity (SEC207-L) | 51 minutes | <https://www.youtube.com/watch?v=bqAGpeFUP9g> |
| :tv: | AWS re:Invent 2019: Leadership session: AWS security (SEC201-L) | 53 minutes | <https://www.youtube.com/watch?v=oam8FDNJhbE> |
| :tv: | AWS re:Invent 2019: Security benefits of the Nitro architecture (SEC408-R1) | 1hr | <https://youtu.be/0qcUOKupt7Y> |
| :tv: | AWS re:Invent 2019: Threat management in the cloud: Amazon GuardDuty & AWS Security Hub | 47 minutes | <https://youtu.be/vhYsm5gq9jE> |

### Object Storage

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the S3 home page, watch intro videos and review the customer case studies | 30 minutes | <https://aws.amazon.com/s3/> |
| :tv: | AWS re:Invent 2014: (SOV203) Understanding AWS Storage Options | 45 minutes | <https://www.youtube.com/watch?v=WnycsuQ4SF8> |
| :closed_book: | S3 Infrequent Access Blog Post | 15 minutes | <https://aws.amazon.com/blogs/aws/aws-storage-update-new-lower-cost-s3-storage-option-glacier-price-reduction/> |
| :closed_book: | Blog Posts related to S3 review and read any relevant to your role | 30 minutes | <https://aws.amazon.com/blogs/aws/category/amazon-s3/> |
| :closed_book: | review the Glacier home page and its referenced resources | 30 minutes | <https://aws.amazon.com/glacier/> |
| :tv: | AWS re:Invent 2015: (STG312) Amazon Glacier Deep Dive: Cold Data Storage in AWS | 1 hour | <https://www.youtube.com/watch?v=OT1Ggo4E2Xo> |
| :tv: | AWS re:Invent 2016: Deep Dive on Amazon S3 (STG303) | 40 minutes | <https://www.youtube.com/watch?v=bMhWWkhydFQ> |
| :tv: | AWS re:Invent 2017: Deep Dive on Amazon S3 & Amazon Glacier Infrastructure (STG301) | 1 hour | <https://www.youtube.com/watch?v=9\_vScxbIQLY> |
| :tv: | AWS re:Invent 2017: Best Practices for Amazon S3 (STG302) | 50 minutes | <https://www.youtube.com/watch?v=UKuL1K3oWuo&t=1s> |
| :tv: | AWS re:Invent 2017: Deep Dive on Amazon S3 & Amazon Glacier Storage Management (STG311) | 1 hour | <https://www.youtube.com/watch?v=SUWqDOnXeDw> |
| :tv: | AWS re:Invent 2018: What's New in Amazon S3, Amazon EFS, Amazon EBS, & more (STG213-L) | 1 hour | <https://www.youtube.com/watch?v=gidUa4lJd9Y> |

### Compute and Block Storage

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |   |
| --- | --- | --- | --- | --- |
| :closed_book: | review the EC2 home page, watch intro videos and review customer case studies | 30 minutes | <https://aws.amazon.com/ec2/> |
| :tv: | EC2 Instances Deep Dive re:Invent 2017 Video | 45 minutes | <https://www.youtube.com/watch?v=mZy6E2I5Rek> |
| :closed_book: | review the EBS home page, watch intro videos and review customer case studies | 30 minutes | <https://aws.amazon.com/ebs/> |
| :tv: | AWS re:Invent 2015: (STG403) Amazon EBS: Designing for Performance | 45 minutes | <https://www.youtube.com/watch?v=2wKgha8CZ\_w> |
| :tv: | AWS re:Invent 2016: (STG301) Deep Dive on Amazon EBS | 1 hour | <https://www.youtube.com/watch?v=1AHmTmCkdp8> |
| :closed_book: | Tutorial: Installing a LAMP Web Server on Amazon Linux2 | 1 hour | <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-lamp-amazon-linux-2.html> |
| :tv: | AWS re:Invent 2017: Deep Dive on Amazon EBS (CMP310) | 50 minutes | <https://www.youtube.com/watch?v=AnLCr99kFcY> |

### Load Balancing, CloudWatch and AutoScaling

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the ELB home page and related resources | 15 minutes | <https://aws.amazon.com/elasticloadbalancing/> |
| :tv: | AWS re:Invent 2016: Elastic Load Balancing Deep Dive and Best Practices (NET403) | 45 minutes | <https://www.youtube.com/watch?v=qy7zNaDTYGQ> |
| :closed_book: | review the CloudWatch home page and related resources | 15 minutes | <https://aws.amazon.com/cloudwatch/> |
| :tv: | AWS re:Invent 2015: (DVO315) Log, Monitor and Analyze your IT with Amazon CloudWatch | 1 hour | <https://www.youtube.com/watch?v=ZaOR-ybLJF0> |
| :tv: | AWS re:Invent 2015: (CMP201) All You Need To Know About Auto Scaling | 1 hour | <https://www.youtube.com/watch?v=4trGuelatMI> |
| :tv: | AWS re:Invent 2017: Deep Dive into the New Network Load Balancer (NET304) | 55 minutes | <https://www.youtube.com/watch?v=z0FBGIT1Ub4> |
| :tv: | AWS re:Invent 2017: Auto Scaling: The Fleet Management Solution for Planet Earth (CMP201) | 50 minutes | <https://www.youtube.com/watch?v=WUUbOQyrnJU> |
| :tv: | AWS re:Invent 2018: Elastic Load Balancing: Deep Dive and Best Practices (NET404-R1) | 1hr | https://www.youtube.com/watch?v=VIgAT7vjol8


### Backup and Archival

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | AWS re:Invent 2014: (BAC202) Introducing AWS Solutions for Backup and Archiving | 45 minutes | <https://www.youtube.com/watch?v=zYI4Gx0D54U> |
| :closed_book: | review the Solution page for Backup and Recovery, analyze customer case studies and watch the videos | 1 hour | <https://aws.amazon.com/backup-recovery/> |
| :closed_book: | review the Solution page for Data Archival, analyze customer case studies and watch the videos | 1 hour | <https://aws.amazon.com/archive/> |
| :tv: | AWS re:Invent 2017: Deep Dive on Backup to the AWS Cloud (STG305) | 40 min | <https://www.youtube.com/watch?v=NELpuY6B4Jc> |
| :tv: | AWS re:Invent 2017: Deep Dive: Backing Up Amazon EC2 with Amazon EBS Snapshots (CMP304) | 55 min | <https://www.youtube.com/watch?v=TUJCQRejA28> |
| :tv: | AWS re:Invent 2017: Deep Dive on Data Archiving in Amazon S3 & Amazon Glacier, with (STG304) | 1 hour | <https://www.youtube.com/watch?v=QZpLNgFEWBo> |
| :tv: | AWS re:Invent 2017: Turner's Cloud Archive for CNN's Video Library and Global Multip (MAE304) | 40 min | <https://www.youtube.com/watch?v=xAfC7ciWzS4> |
| :tv: | AWS re:Invent 2017: Building Queryable Archives and Data Lakes for Financial Service (FSV303) | 40 min | <https://www.youtube.com/watch?v=CLzrow07yHk> |

### Networking, VPC and Route53

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the VPC home page and related resources | 15 minutes | <https://aws.amazon.com/vpc/> |
| :closed_book: | Default VPC Jeff Barr Blog Post | 15 minutes | <https://aws.amazon.com/blogs/aws/amazon-ec2-update-virtual-private-clouds-for-everyone/> |
| :tv: | AWS re:Invent 2015: (NET201) VPC Fundamentals and Connectivity Options | 1 hour | <https://www.youtube.com/watch?v=5\_bQ6Dgk6k8> |
| :tv: | AWS re:Invent 2015:  From One to Many – Evolving VPC Designs | 1 hour | <https://www.youtube.com/watch?v=ykmqjgLdmL4> |
| :tv: | AWS re:Invent 2015 - Amazon Route 53 Deep Dive:  Delivering Resiliency, Minimizing Latency | 45 minutes | <https://www.youtube.com/watch?v=f9y-T7mQVxs> |
| :tv: | AWS re:Invent 2017: Advanced VPC Design and New Capabilities for Amazon VPC (NET305) | 50 min | <https://www.youtube.com/watch?v=Pj11NFXDbLY> |
| :tv: | AWS re:Invent 2017: Networking Many VPCs: Transit and Shared Architectures (NET404) | 1 hour 10 min | <https://www.youtube.com/watch?v=KGKrVO9xlqI> |
| :tv: | AWS re:Invent 2017: Creating Your Virtual Data Center: VPC Fundamentals and Connectivity (NET201) | 45 min | <https://www.youtube.com/watch?v=Tff1mekxOJ4> |
| :tv: | AWS re:Invent 2017: DNS Demystified: Global Traffic Management with Amazon Route 53 (NET302) | 45 min | <https://www.youtube.com/watch?v=PVBC1gb78r8> |
| :tv: | AWS re:Invent 2018: Advanced VPC Design and New Capabilities for Amazon VPC (NET303) | 57 min | <https://www.youtube.com/watch?v=fnxXNZdf6ew> |
| :tv: | AWS re:Invent 2014: (WEB202) Best Practices for Handling a 20x Traffic Spike | 45 minutes | <https://www.youtube.com/watch?v=nZTYbit3BiI> |
| :tv: | AWS re:Invent 2014: (BAC304) Deploying a DR Site on AWS: Min. Cost with Max. Efficiency | 45 minutes | <https://www.youtube.com/watch?v=A-AsaQeFhb0> |
| :tv: | AWS re:Invent 2014: (SEC307) Building a DDoS-Resilient Architecture with Amazon Web Services | 45 minutes | <https://www.youtube.com/watch?v=OT2y3DzMEmQ> |
| :tv: | AWS re:Invent 2014: (ENT308) Best Practices for Implementing Hybrid Architecture Solutions | 35 minutes | <https://www.youtube.com/watch?v=x-DynRJUugU> |
| :tv: | AWS re:Invent 2015: (ARC302) Running Lean Architectures: Optimizing for Cost Efficiency | 1 hour | <https://www.youtube.com/watch?v=SG1DsYgeGEk> |
| :tv: | AWS re:Invent 2015: (ARC307) Infrastructure as Code | 1 hour | <https://www.youtube.com/watch?v=WL2xSMVXy5w> |
| :tv: | AWS re:Invent 2018: Running Lean Architectures: How to Optimize for Cost Efficiency (ARC202-R2) | 1 hour | <https://www.youtube.com/watch?v=Vo1ytbsNsa4> |

### Relational Databases

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the RDS home page, customer case studies, and watch intro videos | 30 minutes | <https://aws.amazon.com/rds/> |
| :tv: | AWS re:Invent 2016: Introduction to Managed Database Services on AWS (DAT307) | 1 hour and 5 minutes | <https://www.youtube.com/watch?v=yX5C\_idmYf4> |
| :tv: | AWS re:Invent 2017: Deep Dive on Amazon Relational Database Service (RDS) (DAT302) | 52 minutes | <https://www.youtube.com/watch?v=TJxC-B9Q9tQ> |
| :tv: | re:Invent 2015 – Relational Database Management Systems in the Cloud (SQL Server) | 1 hour | <https://www.youtube.com/watch?v=oryGBLFGu3o> |
| :tv: | re:Invent 2015 – Amazon RDS for MySQL Best Practices  | 1 hour | <https://www.youtube.com/watch?v=eHg8LD5KNC0> |
| :tv: | re:Invent 2015 – Amazon RDS PostgreSQL  | 1 hour |  <https://www.youtube.com/watch?v=tZXp19q8RFo> |
| :tv: | re:Invent 2015 – Oracle on AWS and Amazon RDS  | 1 hour |  <https://www.youtube.com/watch?v=fDtmCBaEQyQ> |
| :tv: | re:Invent 2015 – New Launch! Introducing Maria DB on Amazon RDS  | 1 hour |  <https://www.youtube.com/watch?v=IEc8kSlpOQ0> |
| :tv: | re:Invent 2016 - Getting Started with Amazon Aurora  | 1 hour |  <https://www.youtube.com/watch?v=60QumD2QsF0> |
| :tv: | re:Invent 2016 - Deep Dive on Amazon Aurora (DAT303) | 50 minutes | <https://www.youtube.com/watch?v=duf5uUsW3TM> |
| :tv: | Introduction to AWS Database Migration Service | 1 hour | <https://www.youtube.com/watch?v=KJ5\_nnBZtJE> |

### Non-Relational Databases

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the DynamoDB home page and customer case studies, watch the intro video | 30 minutes | <https://aws.amazon.com/dynamodb/> |
| :tv: | re:Invent 2014: (BDT203) From Zero to NoSQL Hero: Amazon DynamoDB Tutorial | 45 minutes | <https://www.youtube.com/watch?v=tDqLwzQEOmM> |
| :tv: | re:Invent 2015 Building Scalable Applications and AWS NoSQL Services | 1 hour | <https://www.youtube.com/watch?v=ie4dWGT76LM> |
| :tv: | AWS re:Invent 2017: Advanced Design Patterns for Amazon DynamoDB (DAT403-R) | 50 min | <https://www.youtube.com/watch?v=jzeKPKpucS0> |
| :tv: | AWS re:Invent 2017: DynamoDB - What's new (DAT304) | 50 min | <https://www.youtube.com/watch?v=EFDDjzIGxA0> |
| :tv: | AWS re:Invent 2017: What's new for AWS Purpose Built, Non-relational Databases (DAT204) | 60 min | <https://www.youtube.com/watch?v=6OJ9FxjV1kw> |

### Queueing and Notification

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the SQS, SWF, and SNS home pages, customer case studies and watch intro videos | 1 hour | <https://aws.amazon.com/sqs/> |
| :tv: | Massive Message Processing with Amazon SQS and Amazon DynamoDB (ARC301) | AWS re:Invent 2013 | 1 hour | <https://www.youtube.com/watch?v=n9pMxdUbBGs> |
| :closed_book: | Tutorial: Working with Amazon SQS | 30 minutes | <https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSGettingStartedGuide/WorkingWithSQS.html> |
| :tv: | AWS re:Invent 2015: How Mobile Businesses and Enterprises Use Amazon SNS | 1 hour | <https://www.youtube.com/watch?v=eTM1nDv6x7s> |
| :closed_book: | Tutorial: Getting Started with Amazon Simple Notification Service | 30 minutes | <https://docs.aws.amazon.com/sns/latest/dg/GettingStarted.html> |
| :tv: | AWS re:Invent 2017: NEW LAUNCH! Introducing Amazon MQ Managed Message Broker Service (ENT228) | 50 minutes | <https://www.youtube.com/watch?v=dCucC1SKkvI> |
| :tv: | AWS re:Invent 2017: How the BBC Built a Massive Media Pipeline Using Microservices (ARC330) | 50 minutes | <https://www.youtube.com/watch?v=RZ7Husc\_yZo> |

### CDN/Edge Services

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the CloudFront home page, customer case studies and featured videos | 30 minutes | <https://aws.amazon.com/cloudfront/> |
| :tv: | AWS re:Invent 2016: Introduction to Amazon CloudFront (CTD205) | 56 minutes | <https://www.youtube.com/watch?v=h2uN9VoAnz8> |
| :tv: | AWS re:Invent 2016: CloudFront Flash Talks: Best Practices (CTD301) | 50 minutes | <https://www.youtube.com/watch?v=fgbJJ412qRE> |
| :tv: | AWS re:Invent 2017: Introduction to Amazon CloudFront and AWS Lambda@Edge (CTD201) | 50 minutes | <https://www.youtube.com/watch?v=wRaPw1tx6LA> |
| :tv: | AWS re:Invent 2017: Amazon CloudFront Flash Talks: Best Practices on Configuring, Securing (CTD301) | 50 minutes | <https://www.youtube.com/watch?v=8U3QdNSFJDU> |

### Object Storage and Hosting Static Websites

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | AWS re:Invent 2014: (WEB203) Building a Website That Costs Pennies to Operate | 45 minutes | <https://www.youtube.com/watch?v=BgU-GDgj4SM> |
| :tv: | AWS re:Invent 2018: [REPEAT 2] Best Practices for Amazon S3 and Amazon Glacier (STG203-R2) | 1 hour | <https://www.youtube.com/watch?v=rHeTn9pHNKo/> |

### Solutions for Databases, Disaster Recovery and Web Application Hosting

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the Solution page for Databases and its references resources | 1 hour | <https://aws.amazon.com/products/databases/> |
| :closed_book: | review the Solution page for Disaster Recovery, review the referenced whitepapers and customer case studies, analyst report, watch the videos | 2 hours | <https://aws.amazon.com/disaster-recovery/> |
| :closed_book: | review the Solution page for Website Hosting, review the referenced customer case studies and watch the videos | 2 hours | <https://aws.amazon.com/websites/> |
| :tv: | AWS re:Invent 2017: Disaster Recovery with AWS: Tiered Approaches to Balance Cost wi (ENT322) | 45 minutes | <https://www.youtube.com/watch?v=a7EMou07hRc> |
| :tv: | AWS re:Invent 2017: How to Design a Multi-Region Active-Active Architecture (ARC319) | 1 hour 20 minutes | <https://www.youtube.com/watch?v=RMrfzR4zyM4> |

### Architecting for High Availability and Scalability

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | Webinar: AWS Webcast - Design For Availability | 45 minutes | <https://www.youtube.com/watch?v=Rh-yTPZnE-8> |
| :tv: | AWS re:Invent 2018: Data Protection: Encryption, Availability, Resiliency, & Durability (SEC325-R1) | 1 hour | <https://www.youtube.com/watch?v=FH6AXreSQWQ/> |
| :tv: | AWS re: Invent ARC 205: Building Web-Scale Applications With AWS | 45 minutes | <https://www.youtube.com/watch?v=2wZAN2\_W6Ns> |
| :tv: | AWS re:Invent 2018: Scaling Up to Your First 10 Million Users (ARC205-R1) | 50 minutes | <https://www.youtube.com/watch?v=Ma3xWDXTxRg/> |
| :closed_book: | Review the Web Application Hosting, Disaster Recovery and Content/Media Serving reference architectures with your mentor and other new hires. Make sure you understand every piece of the diagram: what it does and what alternative services/approaches can be used instead | 2 hours | [http://media.amazonwebservices.com/architecturecenter/AWS\_ac\_ra\_web\_01.pdf](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_web_01.pdf),[http://media.amazonwebservices.com/architecturecenter/AWS\_ac\_ra\_disasterrecovery\_07.pdf](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_disasterrecovery_07.pdf) and [http://media.amazonwebservices.com/architecturecenter/AWS\_ac\_ra\_media\_02.pdf](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_media_02.pdf) |

### Elastic Beanstalk

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | re:Invent 2015 Scaling Your Web Applications with AWS Elastic Beanstalk | 1 hour | <https://www.youtube.com/watch?v=nkj0GXgaRv8> |

### DevTools

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | re:Invent 2015 Infrastructure as Code (CloudFormation and Code Pipeline) | 1 hour | <https://www.youtube.com/watch?v=WL2xSMVXy5w> |
| :tv: | re:Invent 2017 Deep Dive CloudFormation | 1 hour | <https://www.youtube.com/watch?v=01hy48R9Kr8> |
| :tv: | AWS re:Invent 2018: Deep Dive into AWS X-Ray: Monitor Modern Applications (DEV324) | 53 minutes | <https://youtu.be/5MQkX57eTh8>

### CodeDeploy

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | re:Invent 2015 AWS CodeDeploy: Automating Your Software Deployments | 45 minutes | <https://www.youtube.com/watch?v=A4NSyUbAEkw> |

### OpsWorks

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | re:Invent 2015 AWS OpsWorks Under the Hood | 45 minutes | <https://www.youtube.com/watch?v=WxSu015Zgak> |

### EC2 Container Service and Registry

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | Take a look at the ECS and ECR home pages, watch the intro video, review the key points and customer case studies | 45 minutes | <https://aws.amazon.com/ecs/> |
| :closed_book: | Werner Vogels' blog: **Under the Hood of Amazon Container Service (ECS)** | 10 minutes | [http://www.allthingsdistributed.com/2015/07/under-the-hood-of-the-amazon-ec2-container-service.html](http://www.allthingsdistributed.com/2015/07/under-the-hood-of-the-amazon-ec2-container-service.html) |
| :tv: | AWS re:Invent 2016: State of the Union: Containers (CON316) | 35 minutes | <https://www.youtube.com/watch?v=UR8BI2Exkbc> |
| :tv: | Amazon Container Service (ECS) Deployment Walkthrough | 10 minutes | <https://www.youtube.com/watch?v=1wLMLwjCqN4> |
| :tv: | AWS re:Invent 2016: Getting Started with Docker on AWS (CMP209) | 40 minutes | <https://www.youtube.com/watch?v=NMhacj2n0gk> |
| :tv: | AWS re:Invent 2016: Running Microservices on Amazon ECS (CON309) | 45 minutes | <https://www.youtube.com/watch?v=CtALTTjy7Qw> |
| Kubernetes training | \&gt; 1 hour  | <https://kubernetes.io/docs/tutorials/online-training/overview/> |
| :tv: | Amazon Elastic Container Service for Kubernetes (Amazon EKS) | 52 minutes | <https://www.youtube.com/watch?v=lef1qR7C\_GE&t=10s> |
| :tv: | AWS re:invent 2017: Introducing Amazon Fargate (CON214) | 40 minutes | <https://www.youtube.com/watch?v=0SceSgOTyrw> |

### Lambda, API Gateway, and Serverless Computing

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | Take a look at the Lambda and API Gateway home pages, watch the intro video, review key points and customer case studies | 45 minutes | <https://aws.amazon.com/lambda/> |
| :tv: | AWS Summit Series 2016 - Chicago - Getting Started with AWS Lambda and the Serverless Cloud | 1 hour | <https://www.youtube.com/watch?v=g5PNX-8MRt0> |
| :tv: | AWS re:Invent 2015: (DEV203) Amazon API Gateway & AWS Lambda to Build Secure and Scalable APIs | 45 minutes | <https://www.youtube.com/watch?v=ZBxWZ9bgd44> |

### General Principles for Big Data / Analytics

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | AWS re:Invent 2014: (BDT205) Your First Big Data Application on AWS | 1 hour 15 minutes | <https://www.youtube.com/watch?v=KKzJuo\_5huA> |
| :tv: | AWS re:Invent 2015: (BDT310) Big Data Architectural Patterns and Best Practices on AWS | 1 hour | <https://www.youtube.com/watch?v=K7o5OlRLtvU> |
| :tv: | AWS re:Invent 2015: (BDT317) Building a Data Lake on AWS | 1 hour | <https://www.youtube.com/watch?v=7Px5g6wLW2A>  |

### Amazon Redshift

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | Take a look at the Redshift home page, view the intro video, key points, and customer case studies | 30 minutes | <https://aws.amazon.com/redshift/> |
| :tv: | AWS re:Invent 2015: (DAT201) Introduction to Amazon Redshift | 1 hour | <https://www.youtube.com/watch?v=DIj1bFjiqd8> |
| :tv: | Amazon Redshift Masterclass | 1 hour | <https://www.youtube.com/watch?v=GgLKodmL5xE> |
| :tv: | AWS re:Invent 2014: (FIN401) Seismic Shift: Nasdaq's Migration to Amazon Redshift | 1 hour | <https://www.youtube.com/watch?v=O4wAH5FQjS8> |
| :tv: | AWS re:Invent 2015: (BDT401) Amazon Redshift Deep Dive: Tuning and Best Practices | 1 hour | <https://www.youtube.com/watch?v=fmy3jCxUliM> |

### Elastic Map/Reduce (EMR)

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | Take a look at the EMR home page, view the intro video, key points, and customer case studies | 30 minutes | <https://aws.amazon.com/emr/> |
| :tv: | AWS re:Invent 2015: (BDT208) A Technical Introduction to Amazon Elastic MapReduce | 1 hour | <https://www.youtube.com/watch?v=WnFYoiRqEHw> |
| :tv: | AWS March 2016 Webinar Series - Building Big Data Solutions with Amazon EMR and Amazon Redshift | 1 hour | <https://www.youtube.com/watch?v=1AHGcLnvinI> |
| :tv: | AWS Webcast - Masterclass Amazon Elastic MapReduce EMR | 1 hour | <https://www.youtube.com/watch?v=dQH2FqUcQog> |
| :closed_book: | Tutorial: Contextual Advertising using Apache Hive and Amazon EMR | 1 hour 30 minutes | <https://aws.amazon.com/articles/Elastic-MapReduce/2855> |
| :tv: | AWS re:Invent 2014: (BDT308) Using Amazon Elastic MapReduce as Your Scalable Data Warehouse | 1 hour | <https://www.youtube.com/watch?v=PO1oH9fzlgk> |
| :tv: | AWS re:Invent 2015: (BDT305) Amazon EMR Deep Dive and Best Practices | 1 hour | <https://www.youtube.com/watch?v=4HseALaLllc> |
| :tv: | AWS re:Invent 2015: (BDT309) Data Science & Best Practices for Apache Spark on Amazon EMR | 1 hour | <https://www.youtube.com/watch?v=RHfOZ1wn8Go> |
| :tv: | AWS re:Invent 2014: (SDD401) Amazon Elastic MapReduce Deep Dive and Best Practices | 1 hour | <https://www.youtube.com/watch?v=y5nep2CIeL0> |
| :tv: | AWS re:Invent 2015: (BDT314) A Big Data & Analytics App on Amazon EMR & Amazon Redshift (NASDAQ; focus on Security) | 1 hour | <https://www.youtube.com/watch?v=LuHxnOQarXU> |

### Amazon Kinesis

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | take a look at the Kinesis home page, watch the intro video, review key points and customer case studies | 30 minutes | <https://aws.amazon.com/kinesis/> |
| :tv: | AWS Summit Series 2016 - Chicago - Getting Started with Amazon Kinesis | 1 hour | <https://www.youtube.com/watch?v=7bhXafN9uNg> |
| :tv: | AWS Summit Series 2016 - Santa Clara - Streaming Data Processing with Amazon Kinesis | 1 hour | <https://www.youtube.com/watch?v=YX7GCkMT0Pc> |
| :closed_book: | Lab: Tutorial: Visualizing Web Traffic Using Amazon Kinesis Streams | 1 hour | <https://docs.aws.amazon.com/streams/latest/dev/kinesis-sample-application.html> |
| :tv: | AWS re:Invent 2015: (BDT320) New! Streaming Data Flows with Amazon Kinesis Firehose | 1 hour | <https://www.youtube.com/watch?v=lkRoQlhWDXA> |

### Amazon Elasticsearch Service

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | take a look at the Elasticsearch Service home page, watch the intro video, review key points and customer case studies | 30 minutes | <https://aws.amazon.com/elasticsearch-service/> |
| :tv: | AWS re:Invent 2015: (BDT209) New! Amazon Elasticsearch Service for Real-time Analytics | 1 hour | <https://www.youtube.com/watch?v=s7dJESec\_dY> |
| :tv: | AWS October 2015 Webinar Series - Essentials: Introducing Amazon Elasticsearch Service | 1 hour | <https://www.youtube.com/watch?v=cn7QLSPB3OA> |

### DynamoDB for Big Data

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :tv: | AWS re:Invent 2015: (BDT313) Amazon DynamoDB for Big Data | 1 hour | <https://www.youtube.com/watch?v=RBfWk3a6Lus> |
| :tv: | AWS re:Invent 2018: (DAT401) Amazon DynamoDB Deep Dive: Advanced Design Patterns for DynamoDB | 1 hour | <https://www.youtube.com/watch?v=HaEPXoXVf2k> |

### Introduction to Mobile and IoT

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | Review home pages for Mobile Hub, Cognito, SNS and IOT. Watch intro videos, review customer case studies | 1 hour | <https://aws.amazon.com/mobilehub/> |
| :tv: | AWS re:Invent 2017: Mobile Application Development: State of the Union (MBL306) | 1 hour | <https://www.youtube.com/watch?v=IaRt3zr5nxY> |
| :tv: | AWS re:Invent 2017: IoT State of the Union (IOT210) | 1 hour | <https://www.youtube.com/watch?v=gAi18SbtWwU> |
| :tv: | AWS re:Invent 2015: (MBL317) NEW! Introducing AWS Mobile Hub | 1 hour | <https://www.youtube.com/watch?v=MMz0XwRPY98> |
| :tv: | Engage Your Customers with Amazon SNS Mobile Push (MBL308) | AWS re:Invent 2013 | 45 minutes | <https://www.youtube.com/watch?v=DqaXXOOxEUY> |
| :tv: | AWS re:Invent 2014: (MBL303) Get Deeper Insights Using Amazon Mobile Analytics | 35 minutes | <https://www.youtube.com/watch?v=YU4yAYDFL2A> |
| :tv: | AWS re:Invent 2015: (MBL402) Mobile Identity Management & Data Sync Using Amazon Cognito | 1 hour | <https://www.youtube.com/watch?v=jX6pEWf344I> |
| :tv: | AWS re:Invent 2015: (MBL313) New! AWS IoT: Understanding Hardware Kits, SDKs, & Protocols   | 1 hour | <https://www.youtube.com/watch?v=rMiplPiU2nI> |

### Solutions and Architectures for Mobile, IoT, and Big Data

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | review the Solution page for Big Data and its referenced resources | 1 hour | <https://aws.amazon.com/big-data/> |
| :closed_book: | review the Solution page for Mobile and its referenced resources | 1 hour | <https://aws.amazon.com/mobile/> |
| :closed_book: | review the Solution page for Internet of Things (IoT) and its referenced resources | 1 hour | <https://aws.amazon.com/iot/> |

### Additional Resources

| **Type** | **Resource** | **Expected Duration** | **Link / Description** |
| --- | --- | --- | --- |
| :closed_book: | AWS Getting Started guides and quick tutorials | 2 hours | <https://aws.amazon.com/getting-started/> |
| :closed_book: | Install and configure the AWS CLI and preferred development environment SDK (Python, Java, etc.) | 30 minutes | <https://aws.amazon.com/cli/> |
| :closed_book: | Tutorial: Hosting a WordPress Blog with Amazon Linux | 1 hour | <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/hosting-wordpress.html> |
| :closed_book: | Review the different instance types | 20 minutes | [http://aws.amazon.com/ec2/instance-types/](http://aws.amazon.com/ec2/instance-types/)  and [http://aws.amazon.com/ec2/#instance](http://aws.amazon.com/ec2/#instance)  |
| :tv: | Watch Stephen Schmidt (AWS CISO) 2015 re:Invent Security Overview | 1 hour | <https://www.youtube.com/watch?v=fCH4r3s4THQ> |
| :tv: | AWS Summit Series 2016 - Chicago - Compliance in the Cloud Using Security by Design | 1 hour | <https://www.youtube.com/watch?v=JVzrGr4Fkzc> |
| :tv: | a collection of security-related sessions from re:Invent-2015 | 1-2hrs | <https://www.youtube.com/watch?v=hRQgpQMzwTI&list=PLhr1KZpdzukc9aw8-gnLmyralfsBv7zcR>  |
| :closed_book: | AWS re:Invent 2014: High Availability Application Architectures in Amazon VPC | 1 hour | <https://www.youtube.com/watch?v=5fEHhBX7YKE> |

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, David Christiansen has waived all copyright and
related or neighboring rights to this work.
