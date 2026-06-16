# AWS Certified Cloud Practitioner — Practice Sets & Mini Mock Test

> **Exam:** AWS Certified Cloud Practitioner (CLF-C02)
> **Guide Part:** 4 of 4
> **Covers:** 30 Practice Questions (Easy, Medium, Tricky) + 15-Question Mock Test
> **Level:** Exam Prep
> **Language:** Simple Indian English

---

## Part 1: Fresh Self-Check Questions

Here are 30 original practice questions to check your preparation. Attempt them honestly before checking the answers.

---

### Easy Questions (10 Questions)

#### Question 1
A startup in Delhi wants to deploy a new web application on AWS but has no experience in managing operating systems or provisioning servers. Which AWS service allows them to upload their application code and let AWS handle the infrastructure automatically?
*   A. Amazon EC2
*   B. AWS Elastic Beanstalk
*   C. AWS Config
*   D. Amazon Redshift

**Correct answer:** B
*   **Explanation:** AWS Elastic Beanstalk is a Platform as a Service (PaaS). You only upload your application code, and Beanstalk automatically handles provisioning, load balancing, auto-scaling, and health monitoring, while keeping control of the underlying resources.
*   **Why other options are incorrect:**
    *   **A is incorrect:** Amazon EC2 is an Infrastructure as a Service (IaaS) where you must manage the guest operating system, updates, and server setups yourself.
    *   **C is incorrect:** AWS Config is a resource tracking and compliance evaluation tool, not a application deployment service.
    *   **D is incorrect:** Amazon Redshift is an analytical data warehouse database service.

---

#### Question 2
Under the AWS Shared Responsibility Model, which of the following is considered a responsibility of AWS?
*   A. Managing IAM user password policies
*   B. Patching application code running on EC2 instances
*   C. Physical security of the AWS data centers
*   D. Enabling encryption for S3 buckets

**Correct answer:** C
*   **Explanation:** Under the Shared Responsibility Model, AWS is responsible for security *of* the cloud, which includes the physical infrastructure, hardware, hypervisors, and security of physical data centers.
*   **Why other options are incorrect:**
    *   **A, B, and D are incorrect:** These are responsibilities of the customer (security *in* the cloud). You own your IAM user setup, guest OS/application patches, and data encryption configurations.

---

#### Question 3
Which AWS billing tool helps you visualize and analyze your historic costs and usage trends over time?
*   A. AWS Cost Explorer
*   B. AWS Organizations
*   C. AWS Compute Optimizer
*   D. AWS Service Catalog

**Correct answer:** A
*   **Explanation:** AWS Cost Explorer is the default dashboard tool that lets you visualize, filter, and analyze your AWS spending and resource usage over time.
*   **Why other options are incorrect:**
    *   **B is incorrect:** AWS Organizations is used to manage multiple accounts and consolidate billing, not for detailed cost trend graphs.
    *   **C is incorrect:** AWS Compute Optimizer gives recommendations to rightsize over-provisioned or under-provisioned resources.
    *   **D is incorrect:** AWS Service Catalog allows you to create portfolios of approved AWS services for users.

---

#### Question 4
A small graphic design studio in Pune wants to store raw images that are accessed frequently. They need a storage service that stores data as objects and offers high durability. Which service should they choose?
*   A. Amazon EBS
*   B. Amazon EFS
*   C. Amazon S3 Standard
*   D. Amazon Redshift

**Correct answer:** C
*   **Explanation:** Amazon S3 (Simple Storage Service) is an object storage service designed for storing files like images and videos. The S3 Standard class is ideal for frequently accessed data and provides 99.999999999% durability.
*   **Why other options are incorrect:**
    *   **A is incorrect:** EBS is block-level storage (virtual hard drive) meant to be attached to a single EC2 instance.
    *   **B is incorrect:** EFS is a shared file system for mounting onto multiple EC2 instances, not simple object storage.
    *   **D is incorrect:** Redshift is an analytical database, not a file storage service.

---

#### Question 5
What is the minimum number of Availability Zones (AZs) present in an AWS Region?
*   A. 1
*   B. 2
*   C. 3
*   D. 5

**Correct answer:** C
*   **Explanation:** AWS designs all modern Regions to have a minimum of three independent Availability Zones (AZs) to ensure high availability and partition tolerance.
*   **Why other options are incorrect:**
    *   **A, B, and D are incorrect:** The standard minimum design rule for AWS Regions is 3 AZs.

---

#### Question 6
Which cloud concept refers to the ability to scale compute resources up or down automatically based on demand?
*   A. Loose coupling
*   B. High economies of scale
*   C. Elasticity
*   D. Capital expenditure (CapEx)

**Correct answer:** C
*   **Explanation:** Elasticity is the ability of cloud systems to dynamically match resource allocation with real-time demand (scaling out when load increases, and scaling in when load drops).
*   **Why other options are incorrect:**
    *   **A is incorrect:** Loose coupling refers to reducing interdependencies between components.
    *   **B is incorrect:** Economies of scale refers to AWS pricing drops due to bulk hardware purchasing.
    *   **D is incorrect:** CapEx refers to fixed upfront costs.

---

#### Question 7
Which AWS Support Plan provides access to a dedicated Technical Account Manager (TAM) and a 15-minute response time for business-critical system down issues?
*   A. Basic Support
*   B. Developer Support
*   C. Business Support
*   D. Enterprise Support

**Correct answer:** D
*   **Explanation:** The Enterprise Support plan is the highest tier and includes access to a Technical Account Manager (TAM), Concierge support, and the fastest SLA response times (within 15 minutes for critical system outages).
*   **Why other options are incorrect:**
    *   **A, B, and C are incorrect:** Basic has no tech support. Developer and Business do not provide a dedicated TAM or a 15-minute SLA.

---

#### Question 8
Which AWS database service is a fully managed, serverless NoSQL database ideal for low-latency key-value queries?
*   A. Amazon RDS
*   B. Amazon Neptune
*   C. Amazon DynamoDB
*   D. Amazon Redshift

**Correct answer:** C
*   **Explanation:** Amazon DynamoDB is a fully managed NoSQL database service that provides single-digit millisecond latency at any scale. It is serverless and works on key-value models.
*   **Why other options are incorrect:**
    *   **A is incorrect:** Amazon RDS is a relational (SQL) database service.
    *   **B is incorrect:** Neptune is a graph database service.
    *   **D is incorrect:** Redshift is a data warehouse service.

---

#### Question 9
A company wants to block SQL injection attacks on their web applications hosted on AWS. Which service should they use?
*   A. AWS WAF
*   B. AWS Shield Standard
*   C. Network ACL
*   D. Security Group

**Correct answer:** A
*   **Explanation:** AWS WAF (Web Application Firewall) operates at Layer 7 (Application layer) and can inspect web requests to block common web attacks like SQL injection and cross-site scripting (XSS).
*   **Why other options are incorrect:**
    *   **B is incorrect:** Shield Standard blocks DDoS attacks at Layers 3 and 4, not Layer 7 application exploits.
    *   **C and D are incorrect:** NACLs and Security Groups operate at network levels (IP and Port), they cannot inspect application payloads for SQL injection patterns.

---

#### Question 10
Which of the following data transfers is generally free of cost in AWS?
*   A. Transferring data out from AWS to the internet
*   B. Transferring data in from the internet to AWS
*   C. Transferring data across different AWS Regions
*   D. Transferring data between Availability Zones

**Correct answer:** B
*   **Explanation:** AWS does not charge for inbound data transfer from the internet into AWS resources.
*   **Why other options are incorrect:**
    *   **A, C, and D are incorrect:** Outbound data transfer to the internet, cross-region transfers, and inter-AZ data transfers incur standard data transfer charges.

---

### Medium Questions (10 Questions)

#### Question 11
An online education website in Bengaluru stores course syllabus PDFs in Amazon S3. These PDFs are accessed heavily by students during exam season, but are rarely opened for the rest of the year. The company wants to optimize storage costs automatically without losing performance. What S3 storage class should they use?
*   A. S3 Standard
*   B. S3 Glacier Deep Archive
*   C. S3 Intelligent-Tiering
*   D. S3 Glacier Flexible Retrieval

**Correct answer:** C
*   **Explanation:** S3 Intelligent-Tiering monitors access patterns and automatically moves files between frequent access and infrequent access tiers without operational overhead or performance impact.
*   **Why other options are incorrect:**
    *   **A is incorrect:** S3 Standard would be expensive since files sit idle for most of the year.
    *   **B and D are incorrect:** Glacier classes have retrieval delays (minutes to hours), making them unsuitable for active students needing immediate access during exams.

---

#### Question 12
Which AWS security tool can verify whether EC2 instances in your account are using only approved Amazon Machine Images (AMIs)?
*   A. AWS Config
*   B. AWS CloudTrail
*   C. Amazon GuardDuty
*   D. AWS Shield Advanced

**Correct answer:** A
*   **Explanation:** AWS Config records resource configurations and can evaluate them against rules (e.g., "Check if all EC2 instances run approved AMIs") to flag non-compliant resources.
*   **Why other options are incorrect:**
    *   **B is incorrect:** CloudTrail records API audit logs (who made changes), it does not continuously evaluate state compliance rules.
    *   **C is incorrect:** GuardDuty is a threat detection service that monitors logs for malicious activity.
    *   **D is incorrect:** Shield Advanced is a DDoS protection service.

---

#### Question 13
Which perspective of the AWS Cloud Adoption Framework (CAF) focuses on building a digitally fluent workforce and helping employees transition to cloud roles?
*   A. Platform Perspective
*   B. Governance Perspective
*   C. Business Perspective
*   D. People Perspective

**Correct answer:** D
*   **Explanation:** The People Perspective of the AWS CAF focuses on organizational capabilities, building cloud skills, training, change management, and workforce development.
*   **Why other options are incorrect:**
    *   **A is incorrect:** Platform Perspective focuses on cloud architecture and infrastructure patterns.
    *   **B is incorrect:** Governance Perspective focuses on cloud financial control and risk management.
    *   **C is incorrect:** Business Perspective aligns IT investments with business strategy.

---

#### Question 14
Which AWS service allows you to provision a dedicated physical network link from your on-premises data center directly to AWS, bypassing the public internet?
*   A. AWS Client VPN
*   B. AWS Direct Connect
*   C. Amazon Route 53
*   D. AWS Transit Gateway

**Correct answer:** B
*   **Explanation:** AWS Direct Connect establishes a dedicated, private network connection from your office or co-location facility directly to AWS, resulting in lower network latency and more consistent speeds compared to public internet connections.
*   **Why other options are incorrect:**
    *   **A is incorrect:** VPN goes over the public internet, even though it is encrypted.
    *   **C is incorrect:** Route 53 is a Domain Name System (DNS) service.
    *   **D is incorrect:** Transit Gateway connects VPCs and on-premises networks at a routing level.

---

#### Question 15
An application needs to run uninterrupted for a period of one year. The instance type and configuration will remain completely constant. What is the most cost-effective EC2 purchasing option?
*   A. On-Demand Instances
*   B. Spot Instances
*   C. Standard Reserved Instances
*   D. Dedicated Hosts

**Correct answer:** C
*   **Explanation:** Standard Reserved Instances provide up to 72% discount for a commitment of 1 or 3 years. Since the workload is constant, uninterrupted, and long-term, Reserved Instances offer the best savings.
*   **Why other options are incorrect:**
    *   **A is incorrect:** On-Demand is more expensive for continuous long-term workloads.
    *   **B is incorrect:** Spot Instances can be terminated by AWS, so they cannot be used for uninterrupted workloads.
    *   **D is incorrect:** Dedicated Hosts are physical servers dedicated to your use, which are more expensive and not needed unless licensing rules require it.

---

#### Question 16
What design principle is represented by deploying an application across multiple Availability Zones in an AWS Region?
*   A. Loose coupling
*   B. High availability and fault tolerance
*   C. Vertical scaling
*   D. Monolithic architecture

**Correct answer:** B
*   **Explanation:** Deploying across multiple AZs ensures that even if one data center (AZ) fails due to power loss or flood, the application remains available (High Availability) and can handle the fault without crashing (Fault Tolerance).
*   **Why other options are incorrect:**
    *   **A is incorrect:** Loose coupling refers to separating system components using message queues like SQS.
    *   **C is incorrect:** Vertical scaling means adding more CPU/RAM to a single server.
    *   **D is incorrect:** Monolithic refers to single-tier tightly coupled designs.

---

#### Question 17
A company wants to manage AWS accounts for several departments centrally, combine their usage to obtain volume discounts, and set policies that restrict what services each department can use. What service fits this requirement?
*   A. AWS Identity and Access Management (IAM)
*   B. AWS Organizations
*   C. AWS Service Catalog
*   D. AWS Cost Explorer

**Correct answer:** B
*   **Explanation:** AWS Organizations allows central management of multiple accounts, consolidated billing (sharing volume discounts), and the use of Service Control Policies (SCPs) to restrict available AWS services across member accounts.
*   **Why other options are incorrect:**
    *   **A is incorrect:** IAM manages identities within a single account, not across multiple AWS accounts.
    *   **C is incorrect:** Service Catalog is for managing approved IT services, not account groups.
    *   **D is incorrect:** Cost Explorer analyzes costs, it cannot restrict actions.

---

#### Question 18
Which task is the customer's responsibility when running database applications on Amazon RDS?
*   A. Performing physical disk replacements
*   B. Patching the underlying operating system
*   C. Managing database user credentials and access permissions
*   D. Running automated database backups

**Correct answer:** C
*   **Explanation:** Under the RDS model, AWS manages the database platform, operating system patches, backups, and physical hardware. The customer is still responsible for managing user access and credentials inside the database engine.
*   **Why other options are incorrect:**
    *   **A, B, and D are incorrect:** These are managed automatically by AWS as RDS is a managed service.

---

#### Question 19
Which AWS Well-Architected Framework design principle belongs to the Operational Excellence pillar?
*   A. Scale horizontally to increase workload availability
*   B. Anticipate failure
*   C. Implement security controls at all layers
*   D. Rightsize resources based on demand

**Correct answer:** B
*   **Explanation:** "Anticipate failure" is a core design principle of the Operational Excellence pillar, which focuses on running and monitoring systems, and continually improving processes.
*   **Why other options are incorrect:**
    *   **A and B are incorrect:** Horizontal scaling belongs to Reliability.
    *   **C is incorrect:** Security layers belong to the Security pillar.
    *   **D is incorrect:** Rightsizing belongs to Cost Optimization / Performance Efficiency.

---

#### Question 20
Which AWS service uses global edge locations to deliver cached files, videos, and APIs to users worldwide with low latency?
*   A. Amazon Route 53
*   B. AWS Global Accelerator
*   C. Amazon CloudFront
*   D. Amazon S3

**Correct answer:** C
*   **Explanation:** Amazon CloudFront is AWS's Content Delivery Network (CDN) service that caches files at Edge Locations close to users worldwide to reduce retrieval latency.
*   **Why other options are incorrect:**
    *   **A is incorrect:** Route 53 is a DNS system.
    *   **B is incorrect:** Global Accelerator optimizes IP routing, it does not cache files at edge locations.
    *   **D is incorrect:** Amazon S3 stores objects in a specific Region, not at Edge Locations directly.

---

### Tricky Scenario-Based Questions (10 Questions)

#### Question 21
A school management company in Noida wants to migrate some test databases to AWS. The databases will only be used by developers for testing, and the databases can be stopped at any time without warning. The company is extremely cost-sensitive. Which EC2 instance option should they choose?
*   A. Dedicated Instances
*   B. Spot Instances
*   C. On-Demand Instances
*   D. Reserved Instances

**Correct answer:** B
*   **Explanation:** Spot Instances use spare AWS capacity and offer up to 90% discount. However, AWS can terminate them with a 2-minute notice if they need the capacity back. Since these are test databases that can be stopped at any time without warning, Spot Instances are the most cost-effective choice.
*   **Why other options are incorrect:**
    *   **A is incorrect:** Dedicated Instances are physical hosts, which are very expensive.
    *   **C is incorrect:** On-Demand is more expensive than Spot.
    *   **D is incorrect:** Reserved Instances require a 1-year or 3-year commitment, which is not suitable for temporary test environments.

---

#### Question 22
A logistics company in Hyderabad runs a processing app on EC2. The app extracts text from scanned cargo invoices. The database logs show that the EC2 instances are over-provisioned, operating at only 15% CPU utilization. What is the most immediate cost-optimization step the company should take?
*   A. Set up AWS Budgets alerts
*   B. Migrate the database to Amazon DynamoDB
*   C. Rightsize the EC2 instances using AWS Compute Optimizer recommendations
*   D. Convert the EC2 instances to Dedicated Hosts

**Correct answer:** C
*   **Explanation:** "Rightsizing" means matching the CPU, memory, and storage configurations of resources to their actual performance requirements. Using Compute Optimizer recommendations, they can change the EC2 instance types to smaller, cheaper sizes that match their 15% usage.
*   **Why other options are incorrect:**
    *   **A is incorrect:** Budgets only alert you about costs, they do not optimize the resource sizing.
    *   **B is incorrect:** Migrating databases does not fix the EC2 compute over-provisioning issue.
    *   **D is incorrect:** Dedicated hosts increase cost, which is the opposite of optimization.

---

#### Question 23
A financial advisory firm in Chennai wants to block incoming connections to their private database subnet from a range of specific IP addresses identified as malicious. Where and how should they implement this rule?
*   A. Create a "Deny" rule in the database Security Group.
*   B. Create a "Deny" rule in the subnet Network ACL (NACL).
*   C. Block the IP addresses in AWS WAF.
*   D. Use AWS Shield Advanced to configure IP blocks.

**Correct answer:** B
*   **Explanation:** Network ACLs operate at the subnet level and support both "Allow" and "Deny" rules. This allows you to explicitly block specific IP address ranges from reaching the subnet.
*   **Why other options are incorrect:**
    *   **A is incorrect:** Security Groups operate at the instance level and only support "Allow" rules (everything else is denied by default). You cannot create a specific "Deny" rule in a Security Group.
    *   **C is incorrect:** WAF protects Layer 7 web apps, not database ports.
    *   **D is incorrect:** Shield is for DDoS protection, not manual IP range subnet blocking.

---

#### Question 24
A hospital group in Mumbai stores sensitive patient records on AWS. The hospital has a strict compliance requirement: they must track every change in their resource setup and verify if all S3 buckets are configured as private. Which AWS service does this monitoring?
*   A. Amazon CloudWatch
*   B. AWS CloudTrail
*   C. AWS Config
*   D. AWS Artifact

**Correct answer:** C
*   **Explanation:** AWS Config tracks resource configuration histories and evaluates them against rules (e.g., checking if S3 buckets have public-read enabled) to flag non-compliance.
*   **Why other options are incorrect:**
    *   **A is incorrect:** CloudWatch monitors system performance metrics, not resource configuration states.
    *   **B is incorrect:** CloudTrail records API audit logs (who did what), it does not continuously evaluate compliance rules.
    *   **D is incorrect:** AWS Artifact provides on-demand access to AWS compliance reports, it does not evaluate your live resource configurations.

---

#### Question 25
A company wants to build a recommendation engine for its e-commerce website. The engine needs to analyze complex relationships between products, customers, and purchase history. Which database service is built specifically for this graph data structure?
*   A. Amazon RDS
*   B. Amazon Neptune
*   C. Amazon DynamoDB
*   D. Amazon Redshift

**Correct answer:** B
*   **Explanation:** Amazon Neptune is a fast, reliable, fully managed graph database service built for storing and navigating highly connected datasets (like recommendation engines or social network graphs).
*   **Why other options are incorrect:**
    *   **A is incorrect:** RDS is a relational database.
    *   **C is incorrect:** DynamoDB is a key-value NoSQL database.
    *   **D is incorrect:** Redshift is a tabular column-based data warehouse.

---

#### Question 26
A media company needs a storage solution that can be attached to multiple EC2 instances running Linux simultaneously, allowing them to share files and project assets. Which AWS service fits this requirement?
*   A. Amazon EBS
*   B. Amazon EFS
*   C. Amazon S3
*   D. Amazon FSx for Windows File Server

**Correct answer:** B
*   **Explanation:** Amazon Elastic File System (EFS) is a serverless, shared file system that can be mounted to multiple EC2 instances (running Linux) simultaneously across different Availability Zones.
*   **Why other options are incorrect:**
    *   **A is incorrect:** EBS volumes can only be attached to a single EC2 instance at a time.
    *   **C is incorrect:** S3 is object storage accessed via APIs, not mounted directly as a traditional file system.
    *   **D is incorrect:** FSx for Windows supports SMB protocols for Windows-native environments, not standard Linux mounts.

---

#### Question 27
An enterprise company wants to host an application in a hybrid cloud environment. They must keep a database on-premises due to physical sovereignty rules, but want to use AWS for web compute. Which AWS service extends AWS infrastructure and services directly into their physical data center?
*   A. AWS Direct Connect
*   B. AWS Outposts
*   C. AWS Snowball Edge
*   D. AWS Local Zones

**Correct answer:** B
*   **Explanation:** AWS Outposts is a fully managed service that extends AWS infrastructure, services, APIs, and tools to virtually any on-premises data center or co-location space for a consistent hybrid experience.
*   **Why other options are incorrect:**
    *   **A is incorrect:** Direct Connect is just a network connection, it does not run AWS compute services on-premises.
    *   **C is incorrect:** Snowball Edge is for physical data migration and offline computing, not active hybrid app hosting.
    *   **D is incorrect:** Local Zones are AWS data centers located in cities, not on your physical premises.

---

#### Question 28
Which phase of the AWS Cloud Transformation Journey (under CAF) focuses on identifying measurable business outcomes and aligning cloud adoption with strategic goals?
*   A. Align Phase
*   B. Envision Phase
*   C. Launch Phase
*   D. Scale Phase

**Correct answer:** B
*   **Explanation:** The Envision phase of the cloud transformation journey focuses on identifying business opportunities, defining strategic outcomes, and creating a business case for cloud migration.
*   **Why other options are incorrect:**
    *   **A, C, and D are incorrect:** These are later phases focusing on preparing teams (Align), deploying early workloads (Launch), and growing operations (Scale).

---

#### Question 29
A developer wants to set up automated email notifications to be sent whenever an EC2 instance in their account changes its state to "Stopped". Which combination of AWS services should they use? (Select TWO)
*   A. Amazon EventBridge
*   B. Amazon Simple Queue Service (SQS)
*   C. Amazon CloudTrail
*   D. Amazon Simple Notification Service (SNS)
*   E. AWS Config

**Correct answers:** A and D
*   **Explanation:** Amazon EventBridge detects changes in resource states (such as an EC2 state change to Stopped) and routes the event to a target. Amazon SNS (Simple Notification Service) acts as the target to send out email notifications to subscribers.
*   **Why other options are incorrect:**
    *   **B is incorrect:** SQS is a message queue, it does not send emails directly.
    *   **C is incorrect:** CloudTrail logs activity, it does not alert in real-time.
    *   **E is incorrect:** AWS Config tracks configurations, it is not the primary routing service for real-time notifications.

---

#### Question 30
Which AWS Well-Architected Framework design principle belongs to the Reliability pillar?
*   A. Test recovery procedures
*   B. Manage operations as code
*   C. Analyze and attribute expenditure
*   D. Structure security layers

**Correct answer:** A
*   **Explanation:** "Test recovery procedures" is a core design principle of the Reliability pillar. It emphasizes validating that your systems can recover from failures automatically.
*   **Why other options are incorrect:**
    *   **B is incorrect:** Managing operations as code belongs to Operational Excellence.
    *   **C is incorrect:** Analyzing expenditure belongs to Cost Optimization.
    *   **D is incorrect:** Security layers belong to Security.

---

## Part 2: Mini Mock Test

*Rules:*
*   *Attempt all 15 questions.*
*   *Time limit: 20 minutes.*
*   *Keep a piece of paper to write down your choices before looking at the answer key at the end.*

---

### Questions

#### Mock Question 1
A retail company is planning to migrate its workloads to AWS. Which costs will be completely eliminated by moving their physical servers to the cloud? (Select TWO)
*   A. Software development costs
*   B. Physical data center cooling and electricity costs
*   C. Operating system license management
*   D. Upfront hardware server purchasing costs
*   E. Database administrator salaries

---

#### Mock Question 2
Under the AWS Shared Responsibility Model, which of the following is considered a responsibility of the customer?
*   A. Replacing faulty hypervisor servers
*   B. Encrypting customer data at rest and in transit
*   C. Disposing of old hard drives securely
*   D. Maintaining physical network connections between data centers

---

#### Mock Question 3
A web application uses microservices that need to communicate with each other. The developers want to decouple these services so that if one service fails, the other services can still process messages. Which service should they use?
*   A. Amazon Route 53
*   B. Amazon Simple Queue Service (SQS)
*   C. Amazon Connect
*   D. Amazon ECS

---

#### Mock Question 4
Which service should a company use to purchase third-party software, such as pre-configured firewall virtual appliances, that runs on AWS?
*   A. AWS Marketplace
*   B. AWS Service Catalog
*   C. AWS Organizations
*   D. AWS Systems Manager

---

#### Mock Question 5
A company wants to run a containerized microservice application without managing the underlying virtual servers or scaling them manually. Which AWS service provides this serverless container compute capacity?
*   A. Amazon EC2
*   B. AWS Elastic Beanstalk
*   C. AWS Fargate
*   D. Amazon ECS with EC2 launch type

---

#### Mock Question 6
Which tool provides rightsizing recommendations for low-utilized Amazon EBS volumes and over-provisioned EC2 instances in your account?
*   A. AWS Cost Explorer
*   B. AWS Compute Optimizer
*   C. AWS Config
*   D. AWS Trusted Advisor

---

#### Mock Question 7
A company wants to check if their AWS account is complying with security standards such as locking the root account MFA. Which security tool aggregates security findings from multiple AWS services and highlights compliance failures?
*   A. AWS WAF
*   B. AWS Security Hub
*   C. Amazon GuardDuty
*   D. AWS Config

---

#### Mock Question 8
Which AWS support feature is available only to customers on the Enterprise Support plan?
*   A. Support via 24/7 phone and email
*   B. Access to AWS Trusted Advisor recommendations
*   C. Access to the AWS Concierge Support team
*   D. Guidance from cloud support engineers

---

#### Mock Question 9
A company wants to deploy identical copies of their application infrastructure across test, staging, and production environments using templates. Which service automates this setup?
*   A. AWS Elastic Beanstalk
*   B. AWS CloudFormation
*   C. AWS Config
*   D. AWS Systems Manager

---

#### Mock Question 10
Which database service is a fully managed columnar data warehouse designed for running complex analytical queries across petabytes of data?
*   A. Amazon RDS
*   B. Amazon Redshift
*   C. Amazon DynamoDB
*   D. Amazon ElastiCache

---

#### Mock Question 11
What is the primary benefit of deploying an application across multiple Availability Zones in one AWS Region?
*   A. Decreased billing costs
*   B. Low latency for international users
*   C. High availability and fault tolerance
*   D. Automatic software code deployments

---

#### Mock Question 12
Which AWS service allows you to generate time-stamped text transcripts and subtitles from video files?
*   A. Amazon Rekognition
*   B. Amazon Transcribe
*   C. Amazon Polly
*   D. Amazon Translate

---

#### Mock Question 13
Which task is the responsibility of AWS under the Shared Responsibility Model?
*   A. Configuring Security Groups on an EC2 instance
*   B. Restricting IAM user access using policies
*   C. Installing guest OS updates on an EC2 server
*   D. Running automated backups of Amazon RDS databases

---

#### Mock Question 14
A company wants to set up automated alerts that trigger if their monthly AWS billing costs exceed a pre-defined threshold. Which service should they use?
*   A. AWS Budgets
*   B. AWS Cost Explorer
*   C. AWS Config
*   D. Amazon EventBridge

---

#### Mock Question 15
Which service is an in-memory data store that acts as a database cache to speed up query response times?
*   A. Amazon DynamoDB
*   B. Amazon RDS
*   C. Amazon ElastiCache
*   D. Amazon Neptune

---

### Answer Key

1. **B, D**
2. **B**
3. **B**
4. **A**
5. **C**
6. **B**
7. **B**
8. **C**
9. **B**
10. **B**
11. **C**
12. **B**
13. **D**
14. **A**
15. **C**

---

### Detailed Explanations

#### Mock 1
*   **Answers:** B and D
*   **Explanation:** Moving to the cloud eliminates capital expenditures like purchasing physical servers (D) and running costs of physical locations such as cooling and power (B). Software development (A), OS licenses (C), and DB salaries (E) are not completely eliminated.

#### Mock 2
*   **Answer:** B
*   **Explanation:** Customer data encryption (both at rest and in transit) is the customer's responsibility. Physical infrastructure maintenance (A, C, D) is the responsibility of AWS.

#### Mock 3
*   **Answer:** B
*   **Explanation:** Amazon SQS is a message queuing service that decouples microservices by holding messages in a buffer, ensuring failure in one service doesn't break the application chain.

#### Mock 4
*   **Answer:** A
*   **Explanation:** AWS Marketplace is the digital storefront where you find and buy third-party software products that run on AWS.

#### Mock 5
*   **Answer:** C
*   **Explanation:** AWS Fargate is the serverless compute engine for running Docker containers without managing virtual machines. ECS is the container orchestrator, but Fargate provides the serverless capacity.

#### Mock 6
*   **Answer:** B
*   **Explanation:** AWS Compute Optimizer uses machine learning to analyze resource configurations and recommend rightsizing improvements for EC2 instances and EBS volumes.

#### Mock 7
*   **Answer:** B
*   **Explanation:** AWS Security Hub centralizes and prioritizes security checks and compliance alerts from multiple AWS accounts and services.

#### Mock 8
*   **Answer:** C
*   **Explanation:** The Concierge Support Team (which helps with billing and account queries) and the Technical Account Manager (TAM) are benefits exclusive to the Enterprise support tier.

#### Mock 9
*   **Answer:** B
*   **Explanation:** AWS CloudFormation uses templates (Infrastructure as Code) to automate resource creation across multiple environments.

#### Mock 10
*   **Answer:** B
*   **Explanation:** Amazon Redshift is AWS's relational OLAP data warehouse service designed for analytical queries.

#### Mock 11
*   **Answer:** C
*   **Explanation:** Multi-AZ deployments protect applications from data center failures, increasing availability and fault tolerance.

#### Mock 12
*   **Answer:** B
*   **Explanation:** Amazon Transcribe is an AI service that converts speech to text, making it suitable for generating subtitles.

#### Mock 13
*   **Answer:** D
*   **Explanation:** Since RDS is a managed database service, AWS is responsible for database backups, patches, and physical hardware maintenance. The customer manages application settings and user credentials.

#### Mock 14
*   **Answer:** A
*   **Explanation:** AWS Budgets allows you to set custom budgets and trigger alerts (via email/SNS) if your usage costs exceed your targets.

#### Mock 15
*   **Answer:** C
*   **Explanation:** Amazon ElastiCache is a managed in-memory data store service (Redis/Memcached) used to cache query data and speed up database latency.

---

## Part 3: Final Summary & Encouragement

### What You Must Remember
As you prepare for the AWS Certified Cloud Practitioner exam, keep these core principles in mind:

1.  **Look for Keywords:** The exam uses specific keywords that point to specific services. For example:
    *   *Decouple / Queue* → **Amazon SQS**
    *   *Audit / API calls / Who did what* → **AWS CloudTrail**
    *   *Performance / Monitor / Metrics* → **Amazon CloudWatch**
    *   *Hybrid / Extend on-premises* → **AWS Outposts**
    *   *Compliance rules / Track resource history* → **AWS Config**
    *   *Layer 7 Firewall / SQL Injection* → **AWS WAF**

2.  **Shared Responsibility Boundaries:** Understand exactly who is responsible for what. AWS owns the physical layer, customer owns data access, patching (on EC2), and encryption settings.

3.  **Deploy for Availability:** Multi-AZ deployment is the standard way to protect applications from single points of failure.

### Simple Encouragement
The AWS Certified Cloud Practitioner exam is designed for beginners. It does not test deep configuration details. If you understand what each service does, why it is used, and how the cloud changes business costs, you are already 90% ready.

Keep studying, attempt the mock test again, read the explanation details, and you will clear the exam easily!

**All the best! You can do this! 👍**
