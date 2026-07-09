---
title: "Week 9 Worklog"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
  

### Week 9 Objectives:

* Materialize theoretical knowledge by deploying a fully functional end-to-end Web Application infrastructure on AWS.
* Master practical skills in configuring secure networking environments (VPC, Subnets) integrated with fault-tolerant mechanics (Auto Scaling, Elastic Load Balancing).
* Successfully integrate persistent storage/database tiers (S3, RDS) and establish automated performance monitoring (CloudWatch) prior to group evaluation.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Review core cloud systems architecture models and deployment methodologies structured on AWS <br> - Conduct in-depth research on building a production-ready Web Application using core AWS services (EC2, RDS, S3, VPC, and Load Balancers) <br> - Formulate an architectural design blueprint and blueprint mapping for the project | 06/15/2026   | 06/15/2026      |    |
| 3   | - Execute the practical deployment phase of the full-stack Web Application on AWS <br> - Configure the network topology layout: Set up a dedicated VPC, target Subnets, Internet Gateways, and precise Security Group inbound/outbound rules <br> - Connect and synchronize the Frontend, Backend, and Database tiers within the cloud space | 06/16/2026   | 06/16/2026      |    |
| 4   | - Investigate data management regulations and secure storage mechanics within the AWS ecosystem <br> - **Hands-on Practice:** Bind the application server to Amazon RDS, configure Database Instances, establish automated snapshot Backup cadences, and thoroughly test application data retrieval flows | 06/17/2026   | 06/17/2026      |    |
| 5   | - Analyze elasticity parameters, scalability matrices, and High Availability (HA) frameworks of AWS infrastructures <br> - **Hands-on Practice:** Configure an Auto Scaling Group tied with an Elastic Load Balancer to guarantee the infrastructure dynamically adapts to unpredictable traffic spikes | 06/18/2026   | 06/18/2026      |    |
| 6   | - Study performance monitoring workflows and resource optimization tactics on the AWS platform <br> - **Hands-on Practice:** Deploy Amazon CloudWatch to observe resource metrics, establish automated threshold Alarms, and perform deep performance bottlenecks analysis on the application | 06/19/2026   | 06/19/2026      |    |
| 7   | - Consolidate all core architectural knowledge frameworks and cloud engineering skills accumulated during Week 9 <br> - Audit the deployed architecture stack, testing the stability and continuity of the utilized AWS services <br> - Conduct the weekly online group sync: Exchange hands-on testing results, review project development speed, and identify optimization areas for the next sprint | 06/20/2026   | 06/20/2026      | System Infrastructure Files / Group Meeting |


### Week 9 Achievements:

* **Production-Grade Web Application Deployment:**
  * Successfully provisioned a secure multi-tier network topology from scratch by properly routing Public Subnets for the presentation tier and Private Subnets for the database tier, achieving unified connectivity among Frontend, Backend, and Database components.

* **Cloud Storage & Database Management Proficiency:**
  * Successfully bound a relational Amazon RDS instance to the backend application codebase and configured automated daily snapshot schedules, securing data assets against unforeseen failure scenarios.

* **High Availability (HA) Infrastructure Realization:**
  * Implemented an end-to-end load-balancing architecture utilizing Elastic Load Balancing combined with an Auto Scaling Group. The design successfully scales horizontally by spawning new EC2 instances when CPU utilization thresholds are breached, spreading traffic uniformly across distinct Availability Zones.

* **Supervision Capabilities & High-Velocity Team Alignment:**
  * Acquired practical capability utilizing Amazon CloudWatch to curate visual performance Dashboards and automated trigger Alarms, ensuring immediate alerts on resource anomalies.
  * Facilitated a highly productive group sync, auditing the live application environment, resolving misconfigured Route Table parameters, and distributing tasks for the final production milestones.