# AWS_AutoScaling-Project
The project is implemented to ensure the consistent availability of  the application

# REQUIREMENTS:
1. AWS Account :
 a. Launch Template
 b. Elastic Loadbalancer
 c. Target-group
 d. Elastic Autoscaling
 
 # Introduction:
In today's dynamic digital landscape, ensuring the availability and reliability of applications is paramount. To meet this demand, my project focuses on leveraging AWS autoscaling and load balancing capabilities to maintain consistent availability of our application.

 # Launch Template:
A launch template is a powerful tool provided by AWS to simplify the process of launching instances within an autoscaling group. It serves as a blueprint for configuring the launch parameters of EC2 instances, such as instance type, AMI (Amazon Machine Image), security groups, storage, and networking settings.

# Target Group:
A target group is a fundamental component of the AWS Application Load Balancer (ALB) and Network Load Balancer (NLB) services. It serves as a logical grouping of targets, such as EC2 instances, IP addresses, or Lambda functions, that receive incoming traffic from the load balancer.

# Load Balancer:
A load balancer acts as a traffic distributor, evenly distributing incoming requests across multiple instances of our application. AWS offers various types of load balancers, including Application Load Balancer (ALB) and Network Load Balancer (NLB), each suited for different use cases. By deploying a load balancer in front of our application instances, we achieve high availability and fault tolerance, as well as improved scalability and security.

# Autoscaling:
Autoscaling is a crucial feature provided by AWS that automatically adjusts the number of instances in a computing group based on the demand. By configuring autoscaling policies, we ensure that our application can seamlessly handle fluctuations in traffic without manual intervention. This not only improves performance but also optimizes costs by scaling resources up or down as needed.

# Integration and Configuration:
Integrating autoscaling with load balancing in AWS involves configuring autoscaling groups and attaching them to the load balancer. This ensures that new instances launched by autoscaling are automatically registered with the load balancer, seamlessly expanding the capacity of our application to handle increased traffic.

# Creation of Launch Template

![alt text](<Screenshot 2024-04-29 195351.png>)