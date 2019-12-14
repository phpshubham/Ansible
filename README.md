# Ansible


 

 

Write a ansible play book to create Ec2 Instances,  ELB(Elastic load balancer) and deploy index.html files:

 

The EC2 Instance 1 will serve an index.html file with an image and the text “Hello from EC2 Instance1  server IP:_._._._”   (print the serverIP dynamically EX: server IP: 1.2.3.4)

The EC2 Instance 1 will serve an index.html file with an image and the text “Hello from EC2 Instance2  server IP:_._._._”


The ELB should load balance between the 2 instances. So, when one visits the ELB endpoint, we ought to get alternating hello messages
