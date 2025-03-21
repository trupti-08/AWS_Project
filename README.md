# AWS_Project
Deploying Multitier Website Using AWS EC2 and RDS Service
# Project Solution:
**Step 1:** Create an EC2 Instance, Connect it via CLi or PuTTY
**Step 2:** Install apache2 and php-mysql using the following command
            - sudo apt-get update
            - sudo add-apt-repository -y ppa:ondrej/php
            - sudo apt install php5.6 mysql-client php5.6-mysqli
**Step 3:** Deploy PHP website on the EC2 Server
**Step 4:** To connect mysql with RDS - Create Database using RDS Service on AWS Management Console
**Step 5:** Create a MySQL Database & Set Up Connection Over EC2 Server with Proper Tesing
**Step 6:** Create a launch template with the required AMI, instance type, security group, and user data to configure Apache and PHP
**Step 7:** Set up an Auto Scaling Group (ASG) using the launch template to manage EC2 instances
**Step 8:** Create a target group and register the EC2 instances to route traffic efficiently
**Step 9:** Create an Application Load Balancer (ALB) and configure it to route traffic to the target group
**Step 10:** Attach the Load Balancer to the Auto Scaling Group to ensure traffic is balanced across instances
**Step 11:** Update DNS records in Route 53 or another domain registrar to point traffic to the Load Balancer(Optional)
**Step 12:** Check the Load Balancer’s DNS name and verify that traffic is routed correctly
**Step 13:** Test Auto Scaling to Ensure Proper Scaling
**Step 14:** Verify that the PHP application can connect to the database and execute queries properly
  
