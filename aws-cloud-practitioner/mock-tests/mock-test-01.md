# Full Mock Test 01: AWS Cloud Practitioner

> **Exam:** AWS Certified Cloud Practitioner (CLF-C02)
> **Questions:** 10 (Mini-Mock)
> **Time Limit:** 15 Minutes
> **Passing Score:** 70%

---

## 📝 Test Instructions
1. Take this test only after completing all chapters.
2. Note your answers on a piece of paper.
3. Check your answers using the key at the bottom.

---

### Questions

**1. A startup is building an application that requires a NoSQL database with single-digit millisecond latency. Which service should they choose?**
A) Amazon Aurora
B) Amazon RDS
C) Amazon DynamoDB
D) Amazon Redshift

**2. Which AWS service is specifically designed to protect web applications against SQL injection and cross-site scripting (XSS) attacks?**
A) AWS Shield
B) AWS WAF
C) Amazon Inspector
D) AWS KMS

**3. An organization wants to combine the AWS bills of its multiple departments into a single payment. Which service provides this feature?**
A) AWS Cost Explorer
B) AWS Budgets
C) AWS Organizations
D) AWS Pricing Calculator

**4. Which AWS service allows you to track API calls made by users and resources within your AWS account for auditing purposes?**
A) AWS Config
B) Amazon CloudWatch
C) AWS CloudTrail
D) AWS Trusted Advisor

**5. A company needs to store data that is rarely accessed but must be retained for 10 years for compliance reasons. Which S3 storage class is the most cost-effective?**
A) S3 Standard
B) S3 Intelligent-Tiering
C) S3 One Zone-IA
D) S3 Glacier Deep Archive

**6. Which AWS well-architected pillar focuses on using IT and computing resources efficiently, selecting the right resource types and sizes based on workload requirements?**
A) Reliability
B) Performance Efficiency
C) Cost Optimization
D) Operational Excellence

**7. Which component of the AWS Global Infrastructure allows you to cache content closer to end-users to reduce latency?**
A) Availability Zones
B) Edge Locations
C) AWS Regions
D) AWS Local Zones

**8. Which AWS service provides a virtual network dedicated to your AWS account, allowing you to launch resources into a logically isolated environment?**
A) Amazon Route 53
B) AWS Direct Connect
C) Amazon VPC
D) AWS VPN

**9. What is the primary benefit of deploying an Amazon EC2 instance in multiple Availability Zones?**
A) Lower latency for global users
B) Fault tolerance and high availability
C) Reduced compute costs
D) Automatic software patching

**10. A company needs an automated tool to check their AWS environment for unattached EBS volumes and open security groups. Which tool should they use?**
A) AWS Trusted Advisor
B) AWS CloudTrail
C) AWS Config
D) AWS Systems Manager

---

### 🛑 STOP! Do not scroll further until you have answered all questions.

---

## ✅ Answer Key & Explanations

1. **C** - DynamoDB is AWS's fully managed, serverless NoSQL database providing millisecond latency.
2. **B** - AWS WAF operates at Layer 7 to protect against common web exploits like SQLi and XSS.
3. **C** - AWS Organizations offers Consolidated Billing, combining multiple accounts into one invoice.
4. **C** - CloudTrail logs API activity ("who did what").
5. **D** - Glacier Deep Archive is the cheapest storage class, designed for long-term data retention where retrieval time of 12+ hours is acceptable.
6. **B** - Performance Efficiency focuses on selecting the right resource types and sizes and maintaining efficiency as demand changes.
7. **B** - Edge Locations are used by Amazon CloudFront to cache content close to users.
8. **C** - Amazon VPC (Virtual Private Cloud) provides a logically isolated network section.
9. **B** - Multiple AZs protect your application from a failure in a single data center.
10. **A** - Trusted Advisor acts as an automated expert, checking for Cost Optimization (unattached volumes) and Security (open ports).
