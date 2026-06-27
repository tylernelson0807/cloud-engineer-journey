# Day 46 – Weak Areas Review & Self-Reflection

**Date:** June 26, 2026  
**Focus:** Detailed review of weak areas identified from the practice exam and recognizing the need to slow down during exams 

## Topics Covered
- Deep review of AWS Systems Manager (Session Manager, Run Command, Patch Manager, Parameter Store, and OpsCenter)
- Detailed comparison between AWS IAM and IAM Identity Center
- Review of AWS CloudFormation and AWS CodeDeploy
- Amazon EventBridge and scheduled events
- Cost optimization services: Cost Explorer, AWS Budgets, Compute Optimizer, and Trusted Advisor
- APN Consulting Partner

## Key Takeaways
- Session Manager continues to be an area that needs reinforcement. It is better than traditional SSH + Bastion Hosts because it requires no inbound ports, no public IPs, no SSH key management, and provides built-in session logging through IAM.
- AWS IAM is used for fine-grained permissions on specific resources. IAM Identity Center is used for centralized user management and Single Sign-On across multiple AWS accounts. These two services solve different problems.
- CloudFormation is used for Infrastructure as Code (defining infrastructure in templates). CodeDeploy is used for deploying application code to EC2 instances.
- EventBridge can be used for scheduled events (similar to cron jobs), allowing tasks to run automatically at specific times (such as in the middle of the night).
- Cost Explorer is best for analyzing historical spending trends. AWS Budgets is used for setting spending limits and receiving alerts. Compute Optimizer provides right-sizing recommendations based on actual resource utilization (CPU/memory), not just spending.
- Trusted Advisor provides general recommendations across cost, security, performance, and fault tolerance.
- An APN Consulting Partner is an external company approved by AWS that can be hired to help with AWS projects and migrations.

## Progress Reflection
Today was spent doing a focused review of the topics I missed on the 81% practice exam. 

## Next Steps
- Tomorrow (Day 47): Take Practice Exam #2 with a conscious effort to slow down and stay in the 55–70 minute range. 
- After the exam, immediately review all missed questions while the material is still fresh.
- Continue reinforcing IAM vs IAM Identity Center distinctions and Systems Manager tools.
