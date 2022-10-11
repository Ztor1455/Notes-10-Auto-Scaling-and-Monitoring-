# Notes-10-Auto-Scaling-and-Monitoring-

**“These three services work well individually, but together they become more powerful and increase the control and flexibility over how your applications handle customer demand.” (Elastic Load Balancing, Amazon CloudWatch, and EC2 Auto Scaling)** 

## Elastic Load Balancing 

•	Distributes network traffic & applications across multiple targets in a single Availability Zone or even multiple 

Availability Zones 

•	Scales load balancer as traffic to application over time 

•	Types of Load Balancers 

    o	Application load balancer – operates at the application level or layer 7 of OSI model 

      	Simplifies and improves the security of the application by ensuring latest security ciphers and protocol are being used 

      	Rotes traffic to targets based on content of requests 

      	Ideal for advanced load balancing of HTTP and HTTPS 

    o	Network load balancer – operates at the network transport level or layer 4 of OSI model 

      	Routes connections to targets based on IP protocol data 

      	Handles millions of requests per second while maintaining ultra-low latencies

      	Optimized to hand le sudden and volatile network traffic patterns 

    o	Classic load balancer – operates at both application and network transport levels 

      	Supports the load balancing of applications that use HTTP, HTTPS, and SSL protocols 

      	Older implementation 

## Amazon CloudWatch 

•	Monitoring and observability service that is built for many users 

•	Use to collect and track metrics (variables used to measure resources and applications) 

•	Create alarm to monitor any CloudWatch metric in account as well as on custom metric that user specifies for own apps and infrastructure 

•	CloudWatch events to define rules that match incoming events or changes in AWS environment and route them to targets for 
processing. 

•	Becomes aware of operational changes as they occur and respond to take corrective actions as necessary 

•	User pains system-wide visibility into resource utilization, application performance, and operational health 

•	Pay for what you use 

## Amazon EC2 Auto Scaling 

•	Scaling is the ability to increase or decrease the compute capacity of user application 

•	Without scaling, applications can underperform or unavailable fore users 

•	Amazon EC2 Auto Scaling: an AWS service that helps maintain application availability and enables user to automatically add or 
remove EC2 instances according to defined conditions  

•	Provides ways adjust scaling to best meet the needs of users application 

**“AWS Auto Scaling is a separate service that monitors applications, automatically adjust capacity to maintain steady 
predictable performance at the lowest possible costs.”** 

