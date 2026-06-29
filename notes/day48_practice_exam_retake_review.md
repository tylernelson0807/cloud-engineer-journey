# Day 48 – Practice Exam Retake + Microservices Decoupling Review

**Date:** June 28, 2026  
**Focus:** Took another practice exam retake and reviewed key weak areas including microservices decoupling, NAT Gateway, and AWS Organizations vs IAM

## Topics Covered
- Completed a retake of a previously taken practice exam 
- Reviewed the concept of decoupling components in a microservices architecture
- Clarified which AWS services are used to decouple microservices (SQS, SNS, EventBridge, and Kinesis)
- Confirmed that a NAT Gateway is a fully managed service by AWS
- Completed a short 4-question quiz on AWS Organizations vs AWS IAM (scored 4/4)
- Discussed the relationship between Service Control Policies (SCPs) and IAM policies

## Key Takeaways
- Decoupling microservices means designing services so they are independent and do not directly depend on each other. This improves reliability, scalability, and maintainability. The main AWS services used for this are Amazon SQS (queue-based), Amazon SNS (pub/sub), Amazon EventBridge (event-driven), and Amazon Kinesis (real-time streaming).
- A NAT Gateway is a fully managed service by AWS. You do not need to manage any underlying infrastructure, patching, or high availability.
- AWS Organizations (with Service Control Policies) sets high-level guardrails across multiple AWS accounts. These policies cannot be overridden by IAM policies. AWS IAM is used for detailed, fine-grained permissions inside individual accounts.

## Progress Reflection
Today I took another practice exam and saw some improvement compared to previous attempts. While I’m happy with the progress, I was hoping for a higher score. I’m realizing that some of my remaining weak areas are more conceptual than purely technical. Topics like decoupling microservices, the relationship between Organizations and IAM, and understanding the purpose of different services are areas I need to continue strengthening.

## Next Steps
- Tomorrow (Day 49): Review additional missed questions from recent practice exams and continue targeted reinforcement of weak topics.
- Maintain focus on reading questions carefully and avoiding rushing during exams.
