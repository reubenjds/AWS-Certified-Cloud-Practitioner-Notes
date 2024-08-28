## Billing and Pricing

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
