# ⚡ Ultimate Quick Revision Guide (Read Day Before Exam)

> **Exam:** AWS Certified Cloud Practitioner (CLF-C02)
> **Last Updated:** 2026-06

---

## 🏛️ 1. Global Infrastructure
- **Region:** A geographical area containing 2 or more Availability Zones.
- **Availability Zone (AZ):** One or more discrete data centers with redundant power and networking.
- **Edge Location:** Used by CloudFront (CDN) to cache content closer to users for lower latency.

## 💻 2. Compute
- **EC2:** Virtual servers. You manage the OS.
  - *On-Demand:* Pay by the second. No long-term commitment.
  - *Reserved:* 1 or 3-year commitment. Huge discount.
  - *Spot:* Unused capacity. Cheapest, but AWS can terminate it with a 2-minute warning.
- **Lambda:** Serverless compute. Run code without provisioning servers. Pay per millisecond.
- **Elastic Beanstalk:** PaaS. You upload code, AWS handles deployment, capacity, and scaling.

## 💾 3. Storage
- **S3:** Object storage. Good for files, images, backups. Not for OS or databases.
  - *S3 Standard:* Frequently accessed data.
  - *S3 IA:* Infrequently accessed, but needs rapid access when needed.
  - *S3 Glacier Deep Archive:* Cheapest, for archiving. 12+ hour retrieval.
- **EBS:** Block storage. Hard drive attached to an EC2 instance.
- **EFS:** File storage. Shared network drive for multiple Linux EC2 instances.

## 🗄️ 4. Databases
- **RDS:** Relational database (MySQL, PostgreSQL).
- **Aurora:** AWS-proprietary relational database. Very fast, scales up to 128 TiB.
- **DynamoDB:** NoSQL database. Key-value. Single-digit millisecond latency.
- **Redshift:** Data warehouse for Analytics / Business Intelligence.
- **ElastiCache:** In-memory cache (Redis/Memcached) for sub-millisecond latency.

## 🔒 5. Security
- **IAM:** Manage users, groups, roles, and policies.
  - *Roles:* Used by AWS services (e.g., EC2) to access other services safely.
- **WAF:** Web Application Firewall. Protects against SQL injection and XSS.
- **Shield:** DDoS protection.
- **KMS:** Manages encryption keys.
- **CloudTrail:** API logging. Tracks "who did what".
- **Config:** Tracks resource configuration changes over time.
- **Artifact:** Download AWS compliance reports (SOC, ISO).

## 💰 6. Billing & Pricing
- **Pricing Calculator:** Estimate costs *before* building.
- **Cost Explorer:** View graphs of past spending and forecast future costs.
- **Budgets:** Set spending limits and get email alerts.
- **Organizations:** Consolidated billing for volume discounts.
- **Trusted Advisor:** Automated checks for Cost, Performance, Security, Fault Tolerance, and Limits.
