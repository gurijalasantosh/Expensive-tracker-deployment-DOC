Expensive Tracker Deployment in AWS

Let’s deploy the application using a 3-tier architecture model.

Architecture Topology:
User → Load Balancer → Frontend → Backend → Database Server


Technologies Used
Operating System: RHEL 9
Database Server: MySQL Server
Backend: Node.js, MySQL Client
Frontend: Nginx


Steps to Follow

Create 4 EC2 instances in AWS.
You can use the AWS Free Tier for learning and beginner practice.

1st Instance: Database Server

Configure the MySQL server by following:
mysql.md

2nd Instance: Backend Server

Configure the backend server by following:

backend_conf.md
3rd Instance: Frontend Server

Configure the Nginx frontend server by following:

front_end_conf.md
4th Instance: Load Balancer

Configure the load balancer by following:
load_balance.conf


What You Will Learn in This Project
Creating EC2 instances in AWS
Understanding Public IP and Private IP
Creating and configuring Security Groups in AWS
Inbound Rules
Outbound Rules
Understanding Reverse Proxy and Forward Proxy
How load balancer works 
DNS Configuration in AWS
DNS and Domain Setup

You can purchase your own domain from providers such as:

GoDaddy
Hostinger

Then transfer or configure the domain in AWS Route 53.

Using a domain name is recommended because:

Public IP addresses may change when instances restart.
DNS helps map your application to a stable domain name.
You do not need to update IP addresses manually in your application configuration.

You can configure your own DNS records in AWS to manage the application efficiently.






