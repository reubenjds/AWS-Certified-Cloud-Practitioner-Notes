## Cloud Concepts

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
