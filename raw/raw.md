# Table of Contents

1. [AWS Certified Cloud Practitioner](#aws-certified-cloud-practitioner)

   - [4 Sections](#4-sections)
   - [Passing Score](#passing-score)
   - [Useful Links](#useful-links)

2. [Cloud Concepts](#cloud-concepts)

   - [Servers](#servers)
   - [Usage Types](#usage-types)
   - [Advantages of Cloud Computing](#advantages-of-cloud-computing)
   - [Technical Terms](#technical-terms)
   - [CapEx vs. OpEx](#capex-vs-opex)
   - [Cloud Computing Models](#cloud-computing-models)
   - [Cloud Deployment Models](#cloud-deployment-models)
   - [Regions](#regions)
   - [Availability Zones (AZs)](#availability-zones-azs)
   - [Edge Locations](#edge-locations)
   - [AWS Management Console](#aws-management-console)
   - [Root User](#root-user)
   - [AWS Command Line Interface (AWS CLI)](#aws-command-line-interface-aws-cli)

3. [Technology](#technology)

   - [Types of Services](#types-of-services)
   - [Elastic Compute Cloud (EC2)](#elastic-compute-cloud-ec2)
   - [Lambda](#lambda)
   - [Additional Compute Services](#additional-compute-services)
   - [Simple Storage Service (S3)](#simple-storage-service-s3)
   - [EC2 Storage](#ec2-storage)
   - [Storage Gateway](#storage-gateway)
   - [AWS Backup](#aws-backup)
   - [Content Delivery Network](#content-delivery-network)
   - [Amazon CloudFront](#amazon-cloudfront)
   - [Amazon Global Accelerator](#amazon-global-accelerator)
   - [Amazon S3 Transfer Acceleration](#amazon-s3-transfer-acceleration)
   - [Amazon Virtual Private Cloud (VPC)](#amazon-virtual-private-cloud-vpc)
   - [Domain Name System (DNS)](#domain-name-system-dns)
   - [Amazon Route 53](#amazon-route-53)
   - [AWS Direct Connect](#aws-direct-connect)
   - [AWS VPN](#aws-vpn)
   - [API Gateway](#api-gateway)
   - [Database Services](#database-services)
   - [Database Migration Service (DMS)](#database-migration-service-dms)
   - [Snow Family](#snow-family)
   - [DataSync](#datasync)
   - [Data Warehousing](#data-warehousing)
   - [AWS RedShift](#aws-redshift)
   - [Analytics Services](#analytics-services)
   - [Artificial Intelligence and Machine Learning](#artificial-intelligence-and-machine-learning)
   - [Developer Tools](#developer-tools)
   - [Infrastructure as Code (IaC)](#infrastructure-as-code-iac)
   - [Loose Coupling](#loose-coupling)
   - [Auditing, Monitoring, and Logging](#auditing-monitoring-and-logging)

4. [Security and Compliance](#security-and-compliance)

   - [Shared Responsibility Model](#shared-responsibility-model)
   - [Well Architected Framework: 6 Pillars](#well-architected-framework-6-pillars)
   - [Identity and Access Management (IAM)](#identity-and-access-management-iam)
   - [IAM Best Practices](#iam-best-practices)
   - [Web Application Firewall (WAF)](#web-application-firewall-waf)
   - [Shield](#shield)
   - [Macie](#macie)
   - [Config](#config)
   - [GuardDuty](#guardduty)
   - [Inspector](#inspector)
   - [Artifact](#artifact)
   - [Cognito](#cognito)
   - [Key Management Service (KMS)](#key-management-service-kms)
   - [Cloud HSM](#cloud-hsm)
   - [Secrets Manager](#secrets-manager)

5. [Billing and Pricing](#billing-and-pricing)

   - [Free Offer Types](#free-offer-types)
   - [Pricing Models](#pricing-models)
   - [EC2 Pricing](#ec2-pricing)
   - [Lambda Pricing](#lambda-pricing)
   - [S3 Pricing](#s3-pricing)
   - [RDS Pricing](#rds-pricing)
   - [Application Discovery Service](#application-discovery-service)
   - [Reduce Total Cost of Ownership (TCO)](#reduce-total-cost-of-ownership-tco)
   - [AWS Price List API](#aws-price-list-api)
   - [Budgets](#budgets)
   - [Budget Types](#budget-types)
   - [Budgets in the Real World](#budgets-in-the-real-world)
   - [Cost and Usage Reports](#cost-and-usage-reports)
   - [Cost Explorer](#cost-explorer)
   - [Cost Allocation Tags](#cost-allocation-tags)

6. [Governance and Management Services](#governance-and-management-services)

   - [Organizations](#organizations)
   - [Control Tower](#control-tower)
   - [Systems Manager](#systems-manager)
   - [Trusted Advisor](#trusted-advisor)
   - [License Manager](#license-manager)
   - [Certificate Manager](#certificate-manager)
   - [Managed Services](#managed-services)
   - [Professional Services](#professional-services)
   - [AWS Partner Network (APN)](#aws-partner-network-apn)
   - [Marketplace](#marketplace)
   - [Personal Health Dashboard](#personal-health-dashboard)

7. [Support Plans](#support-plans)
   - [Basic Support Plan](#basic-support-plan)
   - [Developer Support Plan](#developer-support-plan)
   - [Business Support Plan](#business-support-plan)
   - [Enterprise Support Plan](#enterprise-support-plan)
   - [Support Case Types](#support-case-types)
   - [Basic Support Plan Features](#basic-support-plan-features)
   - [Developer Support Plan Features](#developer-support-plan-features)
   - [Business Support Plan Features](#business-support-plan-features)
   - [Enterprise Support Plan Features](#enterprise-support-plan-features)

# AWS Certified Cloud Practitioner

## 4 Sections:

1. **Cloud Concepts:** 24%
   - AWS cloud value proposition
   - Cloud economics
   - Cloud architecture design principles
2. **Technology:** 34%
   - Deployments and operations
   - Global infrastructure
   - AWS services
   - Technology support
3. **Security and Compliance:** 30%
   - Shared responsibility model
   - Security and compliance concepts
   - Access management capabilities
4. **Billing and Pricing:** 12%
   - Pricing models
   - Account structures
   - Billing pricing
   - Billing support resources

**Passing Score:** 70%

**Useful Links:**

- [AWS Overview Whitepaper](https://d1.awsstatic.com/whitepapers/aws-overview.pdf)
- [AWS Terminology Cheat Sheet](https://www.pluralsight.com/resources/blog/cloud/your-aws-terminology-cheat-sheet)

**Exam Resources:**

- [AWS Certified Cloud Practitioner Sample Exam Questions](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Sample-Questions.pdf)
- [Examstopics - AWS Certified Cloud Practitioner Practice Exams](https://www.examtopics.com/exams/amazon/aws-certified-cloud-practitioner-clf-c02/)

---

## Cloud Concepts

### Servers

- Powerful computers that handle your requests.
- AWS’s servers are located in data centers.
- Virtualization divides hardware resources on a single physical server into smaller units (smaller units are VMs).

### Usage Types

- **On Demand:** No long-term commitments or upfront payments.
- **Pay as you go:** Pay by the hour or by the second.

### Advantages of Cloud Computing

- **Go global in minutes:** Deploy applications around the world at the click of a button.
- **Stop spending money on running and maintaining data centers:** Focus on building applications instead of managing hardware.
- **Benefit from massive economies of scale:** Volume discounts are passed on to you, which provide lower pay-as-you-go prices.
- **Increase speed and agility:** Faster time to market, innovate more quickly, and deliver applications faster.
- **Stop guessing capacity:** Your capacity is matched exactly to your demand, avoiding idle resources or limited capacity.
- **Trade capital expense for variable expense:** You pay for what you use instead of making huge upfront investments.

### Technical Terms

- **High Availability:** Systems designed to operate continuously without failure.
- **Elasticity:** Provision only what you need and grow or shrink based on demand.
- **Agility:** Increased agility from cloud services, allowing faster innovation.
- **Durability:** Long-term data protection to ensure data remains intact without corruption.

### CapEx vs. OpEx

- **Capital Expenditures (CapEx):** Upfront purchases towards fixed assets like equipment, property, computer, software.
- **Operating Expenses (OpEx):** Funds used to run day-to-day operations, including rent, marketing, employee salaries.

### Cloud Computing Models

- **Infrastructure as a Service (IaaS):** Building blocks that can be rented (e.g., AWS EC2).
- **Software as a Service (SaaS):** Complete application or product managed by the provider (e.g., AWS Sagemaker).
- **Platform as a Service (PaaS):** Tools for developers to build and deliver applications (e.g., Cloud9).

### Cloud Deployment Models

- **Private Cloud (OnPrem):** Company's internal data center, everything runs on an internal network.
- **Public Cloud (AWS):** Not responsible for physical hardware, leveraging advantages of cloud computing.
- **Hybrid Cloud:** Combination of private and public clouds; highly sensitive data is stored locally.

### Regions

- A physical location with multiple availability zones.
- Choose a region closest to users for faster downloads and response times.
- Regions are independent; issues in one do not affect others.

### Availability Zones (AZs)

- Data centers within a region, physically separated, and connected through low-latency links.
- Provides fault tolerance and high availability.

### Edge Locations

- Used to cache content to speed up delivery, reduce latency, and improve application performance.

### AWS Management Console

- Web-based interface to access and manage AWS resources.
- Suitable for users new to cloud, non-technical roles, and technical roles.

### Root User

- Automatically created when creating an AWS account.
- Should be protected with Multi-Factor Authentication (MFA).
- Recommended to limit root user use for day-to-day tasks.

### AWS Command Line Interface (AWS CLI)

- Allows access to AWS account through terminal or command window.
- Suitable for developers for programmatic access to AWS services.

---

## Technology

### Types of Services

- **Compute:** Provision compute resources from AWS.
- **Storage:** Store data securely and efficiently.
- **Content Delivery:** Distribute content globally with low latency.
- **Networking:** Connect local environments to AWS.
- **Databases:** Store and manage structured and unstructured data.
- **Migration and Transfer:** Move applications and data to the AWS cloud.
- **Analytics:** Gain insights from data using various AWS tools.
- **Machine Learning:** Leverage AI and ML to add intelligence to applications.
- **Developer Tools:** Accelerate software development and deployment.
- **Deployment and Infrastructure Management:** Use tools to manage and provision infrastructure.

### Elastic Compute Cloud (EC2)

- Rent and manage virtual servers in the cloud.
- Supports various instance types for different use cases (e.g., on-demand, spot, reserved).
- Provides features like load balancing, auto-scaling, and high availability.

### Lambda

- Serverless compute service to run code without managing servers.
- Supports multiple programming languages.
- Scales automatically based on demand.

### Additional Compute Services

- **AWS Fargate:** Serverless compute engine for containers.
- **AWS Lightsail:** Quick deployment of small projects and applications.
- **AWS Outposts:** Run cloud services in internal data centers.
- **AWS Batch:** Process large workloads in smaller chunks.

### Simple Storage Service (S3)

- Object storage service with virtually unlimited storage capacity.
- Supports various storage classes (e.g., S3 Standard, Glacier) for different use cases.
- Provides features like versioning, access controls, and data durability.

### EC2 Storage

- **EBS Volumes:** Persistent storage attached to EC2 instances.
- **EC2 Instance Store:** Temporary storage directly attached to EC2 instances, faster with higher I/O speed.
- **Amazon Elastic File Systems (EFS):** Serverless network file system for sharing files among multiple instances.

### Storage Gateway

- Hybrid storage service connecting on-premises environments with AWS cloud storage.
- Useful for backup, data migration, and reducing costs.

### AWS Backup

- Centralized backup service for AWS resources, providing backup plans and retention policies.

### Content Delivery Network

- Delivers content based on geographic location, improving speed and reducing latency.

### Amazon CloudFront

- Content delivery network that caches content at edge locations.
- Supports low-latency delivery for static and dynamic content.

### Amazon Global Accelerator

- Directs users through AWS's global network, improving latency and availability.

### Amazon S3 Transfer Acceleration

- Speeds up transfers to and from S3 using CloudFront edge locations.

### Amazon Virtual Private Cloud (VPC)

- Isolated network in AWS to launch resources securely.
- Supports features like subnets, route tables, internet gateways, and VPC peering.

### Domain Name System (DNS)

- Connects domain names with web servers, facilitating internet traffic routing.

### Amazon Route 53

- DNS service that routes users to applications and provides domain name registration.

### AWS Direct Connect

- Dedicated physical network connection from on-premises to AWS for secure data transfer.

### AWS VPN

- Secure connection between internal networks and AWS VPCs over the internet.

### API Gateway

- Build and manage APIs, facilitating data exchange between systems.

### Database Services

- **Amazon Relational Database Service (RDS):** Managed relational databases.
- **Amazon Aurora:** MySQL and PostgreSQL compatible relational database.
- **Amazon DynamoDB:** NoSQL key-value and document database.
- **Amazon DocumentDB:** Managed MongoDB-compatible document database.
- **Amazon ElastiCache:** In-memory datastore compatible with Redis and Memcached.
- **Amazon Neptune:** Managed graph database service for connected datasets.

### Database Migration Service (DMS)

- Migrate databases to or within AWS with minimal downtime and data replication.

### Snow Family

- Physical devices to transfer large amounts of data to AWS.

### DataSync

- Online data transfer service for moving data from on-premises to AWS.

### Data Warehousing

- Aggregates historical data for querying, reporting, and analytics.

### AWS RedShift

- Scalable data warehouse solution for handling exabyte-scale data.

### Analytics Services

- **Athena:** Query data in S3 using SQL.
- **Glue:** ETL service for preparing data for analytics.
- **Kinesis:** Analyze real-time data streams.
- **Elastic MapReduce (EMR):** Process big data with Hadoop
- **QuickSight:** Visualize data and create interactive dashboards.

### Artificial Intelligence and Machine Learning

- **Rekognition:** Automates image and video analysis.
- **Comprehend:** Natural language processing service to find relationships in text.
- **Polly:** Converts text to speech with natural-sounding voices.
- **SageMaker:** Build, train, and deploy machine learning models.
- **Translate:** Real-time and batch language translation.
- **Lex:** Build conversational interfaces like chatbots.

### Developer Tools

- **Cloud9:** Web-based IDE for writing and debugging code.
- **CodeCommit:** Source control system for private Git repositories.
- **CodeBuild:** Build and test application source code.
- **CodeDeploy:** Manages code deployment to AWS services.
- **CodePipeline:** Automates the software release process.
- **X-Ray:** Analyze and debug production applications.
- **CodeStar:** Collaborative tool for managing the development pipeline.

### Infrastructure as Code (IaC)

- **CloudFormation:** Provision AWS resources using templates.
- **Elastic Beanstalk:** Deploy web applications and manage resources.
- **OpsWorks:** Automate server configuration using Chef or Puppet.

### Loose Coupling

- **Simple Queue Service (SQS):** Message queuing service for building loosely coupled systems.
- **Simple Notification Service (SNS):** Send notifications via email or SMS.
- **Simple Email Service (SES):** Send richly formatted HTML emails.

### Auditing, Monitoring, and Logging

- **CloudWatch:** Monitoring service for cloud resources and applications.
- **CloudTrail:** Tracks user activity and API calls for auditing.
- **Amazon WorkSpaces:** Virtual desktops in the cloud.
- **Amazon Connect:** Cloud-based contact center service.

---

## Security and Compliance

### Shared Responsibility Model

- **AWS Responsibility:** Security of the cloud, including infrastructure and managed services.
- **Customer Responsibility:** Security in the cloud, including data management and application security.

### Well Architected Framework: 6 Pillars

1. **Operational Excellence:** Plan for failure and continuously improve operations.
2. **Security:** Automate security, encrypt data, and enforce least privilege.
3. **Reliability:** Design systems to recover quickly from failures.
4. **Performance Efficiency:** Use resources efficiently and experiment with new services.
5. **Cost Optimization:** Deliver resilient solutions at the lowest cost.
6. **Sustainability:** Minimize environmental impact and maximize utilization.

### Identity and Access Management (IAM)

- **Users:** Represent people or applications needing access.
- **Groups:** Collections of users with common access requirements.
- **Roles:** Temporary access permissions for users or services.
- **Policies:** JSON documents defining access permissions.

### IAM Best Practices

- Enable MFA for privileged users.
- Use strong password policies.
- Create individual users instead of using root.
- Use roles for EC2 instances.

### Web Application Firewall (WAF)

- Protects web applications from common web attacks like SQL injection.

### Shield

- Managed DDoS protection service with standard and advanced options.

### Macie

- Uses machine learning to discover and protect sensitive data.

### Config

- Tracks and evaluates configurations of AWS resources.

### GuardDuty

- Intelligent threat detection system for unauthorized behavior.

### Inspector

- Assesses applications for vulnerabilities and security risks.

### Artifact

- Provides access to AWS compliance and security reports.

### Cognito

- User authentication and authorization for mobile and web applications.

### Key Management Service (KMS)

- Manages and stores encryption keys.

### Cloud HSM

- Hardware security module for managing your own encryption keys.

### Secrets Manager

- Store and manage secrets like database credentials securely.

---

## Billing and Pricing

### Free Offer Types

- **12 months free:** Available for new customers for 12 months.
- **Always free:** Offers that do not expire.
- **Trials:** Short-term free trials for specific services.

### Pricing Models

- **Compute:** Pay based on compute time used.
- **Storage:** Charges based on the amount of data stored.
- **Data Transfer:** Costs for data moving between systems.

### EC2 Pricing

- **On-Demand:** Pay per hour or second without pre-payment. Suitable for short-term, irregular workloads.
- **Savings Plan:** Commit to a specific amount of usage (measured per hour) for 1 or 3 years to receive a discount.
- **Reserved Instances (RIs):** Commit to using an instance type in a particular region for 1 or 3 years. Offers significant savings for predictable workloads.
- **Spot Instances:** Use spare AWS capacity at a discounted rate. Instances can be terminated if capacity is no longer available, making it suitable for flexible, fault-tolerant workloads.
- **Dedicated Hosts:** Pay for a physical server fully dedicated to your use. Helps meet compliance requirements and allows use of existing server-bound software licenses.

### Lambda Pricing

- **Number of Requests:** Charged based on the total number of requests, including test invokes from the console.
- **Code Execution Time:** Charged from the time the code begins execution to its completion, measured in milliseconds.
- **Always Free:** The first 1 million requests per month and 400,000 GB-seconds of compute time are free.

### S3 Pricing

- **Storage Class:** Different classes like S3 Standard, S3 Intelligent-Tiering, S3 Glacier, etc., offer various storage options and costs.
- **Storage:** Charges are based on the number and size of objects stored.
- **Data Transfer:** Charges apply for data transferred out of S3 to the internet or other AWS regions.
- **Request and Data Retrieval:** Fees based on the number of requests made and the amount of data retrieved.

### RDS Pricing

- **Running Clock Hours:** Time the database instance is running.
- **Type of Database:** Cost varies based on the database engine (e.g., MySQL, PostgreSQL, Oracle).
- **Storage:** Charges for the amount of storage provisioned and used.
- **Purchase Type:** Options include On-Demand, Reserved Instances, or Spot Instances.
- **Database Count:** Total number of database instances running.
- **API Requests:** Fees for API requests made to manage databases.
- **Deployment Type:** Single-AZ or Multi-AZ deployment options.
- **Data Transfer:** Costs for data transferred in and out of RDS.

### Application Discovery Service

- Helps you plan migration projects by understanding the on-premises environment. Useful for estimating Total Cost of Ownership (TCO).

### Reduce Total Cost of Ownership (TCO) using AWS

- **Minimize Capital Expenditures:** Use cloud resources to avoid upfront hardware costs.
- **Utilize Reserved Instances:** Commit to reserved capacity for predictable workloads to save costs.
- **Right Size Resources:** Match resource types and sizes to actual workload requirements to avoid over-provisioning.

### AWS Price List API

- Allows programmatic access to AWS service pricing information.
- Supports querying in JSON or HTML formats.
- Helps receive alerts when prices change.

### Budgets

- **Set Custom Budgets:** Create budgets for costs and usage, with alerts when thresholds are exceeded.
- **Improve Planning:** Helps in managing and forecasting cloud spend.
- **Budget Alerts:** Get notified if you exceed predefined cost or usage limits.

### Budget Types

- **Cost Budgets:** Define how much you want to spend on specific services.
- **Usage Budgets:** Plan the amount of usage for particular services.
- **RI and Savings Plans Budgets:** Set targets for Reserved Instances or Savings Plans utilization.

### Budgets in the Real World

- **Monitor Free Tier Usage:** Keep track of free tier usage to avoid unexpected costs.
- **Control Project Budgets:** Manage spending limits for different projects or teams.

### Cost and Usage Reports

- **Comprehensive Report:** Provides detailed cost and usage data, aggregated on a daily, hourly, or monthly level.
- **Downloadable:** Helps with deep analysis of AWS bill.
- **Use Cases:** View granular details of AWS bill and usage for transparency.

### Cost Explorer

- **Visualize Costs:** Helps analyze and forecast costs and usage over time.
- **Historical Data:** View the past 12 months of usage and cost data.
- **Forecasting:** Predicts future costs for up to 3 months based on historical usage.
- **Use Cases:** Analyze EC2 instance usage patterns over 7, 30, or 60 days to optimize costs.

### Cost Allocation Tags

- **Tagging:** Label AWS resources using key-value pairs.
- **Tracking:** Track and report costs by tagging resources with project names, departments, or other identifiers.
- **Cost Allocation Reports:** Generate reports based on tag-specific usage.

---

## Governance and Management Services

- Help maintain control over costs, compliance, and security across AWS accounts.

### Organizations

- **Centralized Management:** Manage multiple AWS accounts under one organization.
- **Single Billing:** Consolidated billing for all linked accounts.
- **Resource Allocation:** Distribute resources and apply policies across accounts.
- **Service Control Policies (SCPs):** Enforce permission policies for the entire organization.
- **Organizational Units (OUs):** Group accounts for specific departments or projects.
- **Member Accounts:** Standard individual AWS accounts that contain resources.

### Control Tower

- **Multi-Account Strategy:** Helps set up and govern a secure, multi-account environment.
- **Policy Enforcement:** Ensure accounts conform to company-wide policies.
- **Integration:** Works with AWS Organizations for centralized management.
- **Dashboard:** Provides visibility and control over multiple accounts.
- **Use Cases:** Disallow public write access to all S3 buckets across all accounts.

### Systems Manager

- **Centralized Management:** Visibility and control over AWS resources.
- **Automation:** Automate operational tasks on AWS resources.
- **Resource Grouping:** Group resources by application, environment, or other criteria.
- **Patch Management:** Automatically deploy operating system and software patches.

### Trusted Advisor

- **Best Practices:** Provides real-time guidance to optimize AWS infrastructure according to best practices.
- **Checks and Recommendations:** Offers checks for cost optimization, security, fault tolerance, and performance.
- **Example Checks:** Unrestricted access to EC2 ports, S3 bucket permissions, IAM password policies.
- **Use Cases:** Monitor DynamoDB read and write capacity usage to stay within service limits.

### License Manager

- **Manage Software Licenses:** Track and manage on-premises and AWS software licenses.
- **Compliance:** Ensure compliance with software licensing agreements.
- **Tracking:** Monitor licenses for software from vendors like Oracle, Microsoft, and SAP.

### Certificate Manager

- **SSL/TLS Certificates:** Provision, manage, and deploy public and private SSL/TLS certificates.
- **Integration:** Works with AWS services like Elastic Load Balancing and API Gateway.
- **Free Certificates:** Provides free public and private certificates for secure communication.

### Managed Services

- **AWS Managed Services:** Helps manage AWS infrastructure and reduce operational risk.
- **Augment Internal Staff:** Provides support to supplement internal teams.
- **Monitoring:** Develop application-specific health monitoring with CloudWatch.

### Professional Services

- **Consulting Services:** AWS Professional Services help enterprise customers transition to the cloud.
- **Solution Design:** Proposes and architects solutions based on customer needs.
- **Implementation:** Assists with implementing cloud-based solutions.
- **Use Cases:** Evaluate and migrate on-premises applications to the AWS cloud.

### AWS Partner Network (APN)

- **Global Community:** Network of approved partners providing software and consulting services for AWS.
- **Technology Partners:** Offer pre-built software solutions.
- **Consulting Partners:** Provide professional services and expertise.
- **Use Cases:** Partner with experienced vendors to design and build new applications.

### Marketplace

- **Digital Catalog:** Prebuilt software solutions available for purchase or license.
- **Sell Solutions:** Developers can list and sell their own applications.
- **Try Before Buying:** Offers trials to evaluate applications before committing.
- **Use Cases:** Deploy third-party software solutions quickly and efficiently.

### Personal Health Dashboard

- **Customized Alerts:** Provides alerts about events that might impact your AWS environment.
- **Troubleshooting Guidance:** Offers guidance to resolve issues affecting specific services.
- **Tailored Feedback:** Information tailored to the specific AWS environment.

---

## Support Plans

### Basic Support Plan

- **Included for Free:** Available to all AWS customers.
- **Support:** Includes account and billing support.
- **Service Limit Increases:** Requests for default service quota increases.
- **Access:** Support via email only.

### Developer Support Plan

- **Cost:** Starts at $29 per month.
- **Support:** Technical support for development and testing environments.
- **Contacts:** Allows for 1 primary contact.
- **Cases:** Unlimited support cases.
- **Access:** Cloud Support Associate available during business hours via email.

### Business Support Plan

- **Cost:** Starts at $100 per month.
- **Support:** Technical support for production workloads.
- **Contacts:** Unlimited contacts.
- **Cases:** Unlimited support cases.
- **Trusted Advisor:** Full set of Trusted Advisor checks.
- **Access:** 24/7 support via email, phone, or chat with Cloud Support Engineers.

### Enterprise Support Plan

- **Cost:** Starts at $15,000 per month.
- **Support:** Comprehensive technical support for business or mission-critical workloads.
- **Contacts:** Unlimited contacts and cases.
- **Technical Account Manager (TAM):** Dedicated TAM for proactive guidance.
- **Concierge Support Team:** Access to a dedicated concierge support team.
- **Infrastructure Event Management:** Support for major infrastructure events.
- **Trusted Advisor:** Full set of Trusted Advisor checks.
- **Access:** 24/7 support via email, phone, or chat with Cloud Support Engineers.

### Support Case Types

- **Account and Billing:** Support cases related to account and billing issues, available to all customers.
- **Service Limit Increases:** Requests for increasing default service quotas, available to all customers.
- **Technical Support:** Available for customers on Developer, Business, or Enterprise plans. Covers technical issues related to AWS services.

### Basic Support Plan Features

- **Account and Billing Support:** Included.
- **Service Limit Increases:** Included.
- **Customer Service Access:** Available via email only.
- **Discussion Forums:** Access to AWS discussion forums for community-based support.

### Developer Support Plan Features

- **Account and Billing Support:** Included.
- **Service Limit Increases:** Included.
- **Technical Support:** Available for 1 primary contact.
- **Unlimited Cases:** Can open unlimited technical support cases.
- **Cloud Support Associate:** Business-hours access via email.

### Business Support Plan Features

- **Account and Billing Support:** Included.
- **Service Limit Increases:** Included.
- **Technical Support:** Available for unlimited contacts and cases.
- **Trusted Advisor Checks:** Access to a full set of Trusted Advisor checks for account optimization.
- **Cloud Support Engineers:** 24/7 access via email, phone, or chat.

### Enterprise Support Plan Features

- **Account and Billing Support:** Included.
- **Service Limit Increases:** Included.
- **Technical Support:** Available for unlimited contacts and cases.
- **Technical Account Manager (TAM):** Assigned for proactive account management.
- **Concierge Support Team:** Access to a dedicated team for billing and account management issues.
- **Infrastructure Event Management:** Support for planning and management during major events.
- **Trusted Advisor Checks:** Full access to all checks for comprehensive account health monitoring.
- **Cloud Support Engineers:** 24/7 access via email, phone, or chat.
