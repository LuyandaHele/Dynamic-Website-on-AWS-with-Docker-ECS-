Summary & Key Takeaways 
The deployment leveraged a wide range of AWS services to architect a scalable, secure, 
and highly available cloud environment. The solution centered on containerization, 
automation, and robust networking to support modern application needs. Below are the 
principal AWS services utilized, the supporting DevOps and containerization tools, and 
real-world use cases illustrating the value of these technologies. 
AWS Services Covered 
• VPC (Virtual Private Cloud) – Custom network configuration and isolation 
• Subnets (Public & Private) – Tiered design for application and database separation 
• Internet Gateway (IGW) – Enabled inbound/outbound traffic for public subnets 
• NAT Gateway – Allowed private subnets to access the Internet securely 
• Route Tables – Directed public and private traffic paths 
• Security Groups – Controlled inbound and outbound access between layers 
• EC2 Instance Connect Endpoint (EICE) – Provided secure SSH access to private 
EC2 instances 
• RDS (Relational Database Service) – Managed MySQL database with subnet 
groups 
• Secrets Manager – Stored and retrieved sensitive database credentials and GitHub 
tokens securely 
• IAM Users & Roles – Enabled programmatic access and service-to-service 
permissions 
• Amazon ECR (Elastic Container Registry) – Stored private Docker images 
• Application Load Balancer (ALB) – Distributed incoming requests across ECS tasks 
with IP-based routing 
• Target Groups – Defined backend ECS tasks for load balancing and health checks 
• Amazon ECS (Elastic Container Service) – Orchestrated containerized application 
deployment with Fargate 
• ECS Task Definitions – Specified container configurations, resources, and 
environment variables 
• ECS Services – Maintained desired task counts and integrated with ALB 
• ECS Auto Scaling – Automated scaling based on performance metrics 
• Route 53 – Managed DNS and domain routing for public access 
• AWS Certificate Manager (ACM) – Issued and managed SSL/TLS certificates for 
secure HTTPS connections 
• CloudWatch – Monitored container health, performance, and scaling metrics 
Containerization & DevOps Tools 
• Docker – Containerized the web application for consistency across environments 
• Dockerfile – Defined application dependencies and runtime configuration 
• Git – Distributed version control system for tracking code changes and collaboration 
• GitHub – Version-controlled application code and Docker configurations 
• AWS CLI – Automated resource creation and deployment workflows 
