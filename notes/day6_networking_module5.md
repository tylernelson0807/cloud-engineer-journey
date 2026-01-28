## Day 6 – Networking Module 5 Completion (January 18, 2026)

**Goal:** Complete Skill Builder Module 5 (Networking), explore VPC/subnets/routing, test connectivity with EC2 instance

**Skill Builder Progress:**
- Module 5: Networking → Completed (100% – VPC, subnets, routing, security groups)

**What I Completed in Module 5: Networking**
- Introduction to Networking  
- Amazon VPC basics (virtual private cloud)  
- Subnets (public/private) and routing tables  
- Internet gateways, NAT gateways  
- Security groups and network ACLs  
- Passed final quiz/assessment with 100% score

**VPC & EC2 Test Project:**
- Explored default VPC and existing subnets  
- Confirmed route table with 0.0.0.0/0 to IGW for public access  
- Launched test EC2 in public subnet, connected via browser terminal  
- Ran `curl google.com` (confirmed internet access) and `uptime`  
- Terminated instance

**Screenshots:**
![day6_default_igw_attached.png](../images/day6_default_igw_attached.png)  
![day6_default_subnet_details.png](../images/day6_default_subnet_details.png)  
![day6_ec2_instance_terminated.png](../images/day6_ec2_instance_terminated.png)  
![day6_module5_networking_100percent_outline.png](../images/day6_module5_networking_100percent_outline.png)  
![day6_module5_quiz_100percent.png](../images/day6_module5_quiz_100percent.png)  
![day6_route_table_associated.png](../images/day6_route_table_associated.png)  
![day6_route_table_updated.png](../images/day6_route_table_updated.png)  
![day6_test_ec2_running.png](../images/day6_test_ec2_running.png)  
![day6_test_terminal_curl.png](../images/day6_test_terminal_curl.png)  
![day6_test_terminal_uptime.png](../images/day6_test_terminal_uptime.png)  
![day6_vpc_created.png](../images/day6_vpc_created.png)  
![day6_vpc_deleted.png](../images/day6_vpc_deleted.png)  
![day6_vpc_subnets_full_list.png](../images/day6_vpc_subnets_full_list.png)

**Takeaways:**
- VPC = your private network in AWS — isolated from others  
- Public subnets = internet access (need IGW + route table), private = secure backends  
- Security groups = stateful firewalls (allow/deny traffic)  
- Networking is key for secure, scalable cloud apps — foundation for EC2, S3, databases  
- Test EC2 connectivity proved the setup works

**Next:** Day 7 – Start S3 storage concepts + simple bucket project
