# Day 45 – First Practice Exam Review & Targeted Deep Dive

**Date:** June 25, 2026  
**Focus:** Detailed review of the first full-length practice exam (Stephane Maarek) and targeted reinforcement of weak areas identified from missed questions

## Topics Covered
- Reviewed all missed questions from the first full-length practice exam
- Deep dive into AWS Systems Manager tools and use cases (Session Manager, Run Command, Patch Manager, Parameter Store, and OpsCenter)
- DynamoDB Global Tables vs DynamoDB Accelerator (DAX)
- Block-level storage services (Amazon EBS and Amazon EC2 Instance Store)
- Docker containers and AWS container services (ECS, EKS, and Fargate)
- Exam strategy and the importance of keyword recognition

## Key Takeaways
- Session Manager provides interactive shell access to EC2 instances without requiring inbound ports to be opened or public IP addresses to be assigned.
- Run Command is best suited for executing one-time scripts or commands across multiple instances at scale.
- Patch Manager automates operating system patching on a defined schedule.
- Parameter Store securely stores configuration data and secrets.
- OpsCenter provides a centralized view of operational issues across an AWS environment.

- DynamoDB Global Tables enable active-active, multi-region replication. A single table can exist in multiple regions, with both regions able to accept reads and writes. This is primarily used to improve reliability and support disaster recovery across regions.
- DynamoDB Accelerator (DAX) is an in-memory cache that reduces read latency within a single region. It does not provide multi-region replication or active-active capabilities.
- The phrase “active-active configuration with cross-region support” points to Global Tables, not DAX.

- The two AWS services that provide block-level storage are Amazon EBS (persistent) and Amazon EC2 Instance Store (ephemeral).
- Amazon ECS is a container orchestration service and does not provide block-level storage.

- Several missed questions on the practice exam were due to wording and keyword traps rather than gaps in knowledge.
- Slowing down to identify key phrases in questions will be a focus area moving forward.

## Progress Reflection
Today was spent reviewing the first practice exam in detail. While it was frustrating to see the questions I missed, the review helped identify clear patterns, especially around keyword recognition and distinguishing between similar services.
## Next Steps
- Conduct a light, targeted review of weak areas identified today.
- Take Practice Exam #2 and track progress against the first exam.
- Continue applying improved exam strategy with a focus on reading questions carefully before selecting answers.
