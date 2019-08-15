# Infrastructure Deployment.
This project consist of network and server stack.
The Network stack deploys Virtual Private Cloud, its public subnet, private subnet, and also it deploys Internet gateway, Nat Gatewat for private subnets to reach internet without exposing private ip address 
The Server stack deploys two security groups for our load balancer and web server group.Also, created role, policy and instace profile for allowing our web instance to get index.html file from S3 bucket. Then it deploys launch configuration to create instances with Auto scalling group component. Lastly, it deploys load balancer with listener, listener rule, and target group component to associate with Auto scalling group.

Also, you can find a diagram which indicates our infrastructure visual. 
