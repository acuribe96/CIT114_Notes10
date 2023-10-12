Aneissa Uribe

**CIT114 - Notes 10, Automatic Scaling and Monitoring**

*Elastic Load Balancing*

- distributes incoming application or network traffic across multiple targets in a single Availability Zone or across multiple Availability Zones.
- scales your load balancer as traffic to your application changes over time

*3 Types of Elastic Load Balancers*

- 1. application load balancer
  2. network load balancer
  3. classic load blancer (previous generation)

*How it works*

- you register targets in target groups, and route traffic to the target groups (with application load-balancers and network load balancers)
- you register instances with the load balancer (with classic load balancers)

*CloudWatch metrics*

- used to verify that the system is performing as expected and creates an alarm to initiate an action if a metric goes outside an acceptable range

*Access Logs*

- capture detailed info about requests sent to your load balancer

*AWS CloudTrail Logs*

- capture the who, what, when, and where of API interactions in AWS services

*Amazon CloudWatch*

- monitors, collects and tracks, alarms, and events

*Scaling*

- ability to increase or decrease the compute capacity of your application.

*Auto Scaling Groups*

- a collection of EC2 instances that are treated as a logical grouping for the purposes of automatic scaling and management
  
**Question 2**

>CloudWatch monitors your AWS resources and the applications that you run on AWS in real-time.

- I think it's neat that AWS can do that for you, instead of before you'd have to monitor everything by someone.

>Amazon EC2 Auto Scaling performs a periodic health check on running instances in Auto Scaling group.

- I find that cool that not only in Auto Scaling they keep track of your instances, but also look after the health and discard the instances that are bad.

**Question 4**

- If autoscaling keeps track of everything, should one still look over it?
