---
title: "Week 10 Worklog"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
  

### Week 10 Objectives:

* Comprehensive audit of the stability and security configurations of the Web Application architecture deployed on AWS.
* Optimize advanced storage solutions (S3), integrated Serverless designs (DynamoDB, Lambda), and disaster recovery mechanisms.
* Analyze system performance metrics via CloudWatch to formulate strategic resource optimization proposals.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Review and evaluate all architectural aspects of the Web Application infrastructure deployed on AWS <br> - Assess in-depth the connectivity and data flows among EC2, RDS, S3, VPC, and Load Balancers <br> - Audit system configurations, access permissions, and security groups to guarantee operational stability | 06/22/2026   | 06/22/2026      |    |
| 3   | - Conduct advanced research into cloud data management solutions on AWS <br> - Explore methods for optimizing Amazon S3: Configure Bucket Policies, enable Versioning, establish Lifecycle Rules, and manage strict data access controls <br> - **Hands-on Practice:** Test storage capabilities, data integrity, and asset protection mechanisms on the cloud | 06/23/2026   | 06/23/2026      |    |
| 4   | - Investigate advanced Serverless application architectures within the AWS ecosystem <br> - Study the integration of various serverless components to drive workflow automation <br> - **Hands-on Practice:** Integrate AWS Lambda, API Gateway, DynamoDB, and S3 to build an automated data processing application <br> - Evaluate the cost-reduction and operational simplification benefits of Serverless models | 06/24/2026   | 06/24/2026      |    |
| 5   | - Study comprehensive backup frameworks and Disaster Recovery (DR) strategies on AWS <br> - Learn the application of AWS Backup, EC2 Snapshots, and RDS Automated Backups <br> - **Hands-on Practice:** Provision resource backup plans, simulate system failure scenarios, and thoroughly test full data restoration flows | 06/25/2026   | 06/25/2026      |    |
| 6   | - Execute comprehensive performance testing and system optimization routines for the deployed cloud environment <br> - Utilize Amazon CloudWatch to track fine-grained hardware utilization (CPU, Memory, Network) and application layer metrics <br> - Analyze captured monitoring charts and formulate structured proposals to improve overall system performance | 06/26/2026   | 06/26/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Week 10 Achievements:

* **Web Application Security Hardening & Optimization:**
  * Successfully verified the connectivity and workload performance of the multi-tier application stack. Audited access controls to ensure permission boundaries between EC2, RDS, and S3 resources remain securely isolated without any potential data exposure risk.

* **Advanced S3 Data Protection & Management:**
  * Mastered advanced Amazon S3 governance skills: Successfully applied object Versioning to protect against accidental overwrites, configured Bucket Policies to restrict public accessibility, and implemented S3 Lifecycle rules to automatically transition aging data to cost-effective storage tiers.

* **Advanced Serverless System Deployment:**
  * Engineered a fully operational Serverless application architecture incorporating a NoSQL layer (Amazon DynamoDB). The pipeline smoothly handles inbound requests via API Gateway, triggers decoupled logical functions via AWS Lambda, stores assets into S3, and writes real-time logs into DynamoDB autonomously.

* **Disaster Recovery Preparedness & Performance Auditing:**
  * Deployed a centralized backup routine utilizing AWS Backup. Successfully simulated operational failure scenarios and validated infrastructure recovery mechanisms by restoring healthy environments from EC2 Snapshots and RDS Backups.
  * Acquired profound analytical skills interpreting CloudWatch performance metric trends, pinpointing application execution bottlenecks, and producing tailored instance-rightsizing proposals to match actual production baselines.