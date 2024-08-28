## Technology

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