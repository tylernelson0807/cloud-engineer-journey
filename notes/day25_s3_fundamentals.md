# Day 25 – Amazon S3 Fundamentals

**Date:** June 5, 2026  
**Focus:** Amazon S3 core concepts, storage classes, security features, and role-play practice with a finance stakeholder focus

## Topics Covered

- Amazon S3 overview (buckets, objects, bucket policies)
- S3 storage classes and Lifecycle Policies for cost optimization
- S3 encryption, versioning, and replication
- Static website hosting on S3
- AWS Snow Family for large-scale data migration
- Role-play practice explaining S3 features to a finance stakeholder

## Key Takeaways

- **Amazon S3** is AWS’s object storage service. It uses **buckets** as containers and **objects** as the actual files stored inside them. Access is controlled through **bucket policies**.

- **Storage Classes** allow cost optimization based on access patterns. S3 Standard is used for frequently accessed data, while Standard-IA, Intelligent-Tiering, and Glacier classes help reduce costs for less frequently accessed or archival data.

- **Lifecycle Policies** automatically move objects to cheaper storage classes after a defined period of inactivity, helping control storage costs without manual intervention.

- **Versioning** protects against accidental deletion or overwrites by keeping multiple versions of objects. **Encryption** (at rest and in transit) and **replication** support security and disaster recovery requirements.

- **Static website hosting** can be enabled directly on an S3 bucket, eliminating the need for traditional web servers and reducing operational overhead.

- **AWS Snow Family** (primarily Snowball Edge) is used for physically shipping large volumes of data to AWS when transferring over the internet would be too slow or expensive.

## Progress Reflection

Today focused on building a strong foundation in Amazon S3. The role-play practice explaining S3 features to a finance stakeholder was particularly valuable, as it reinforced the ability to connect technical capabilities (storage classes, lifecycle policies, encryption, replication) to business outcomes such as cost control, risk management, and operational simplicity. Understanding when to use Snow Family for large data migrations also added practical context.

## Next Steps

- Continue reinforcing storage services (EBS, EFS, FSx, S3) through quizzes and explanations
- Maintain daily role-play practice to strengthen verbal communication of concepts
