# devops-interview-questions



# AWS - Amazon Web Services



## AWS Infra

1. what is a Region ?
2. What is availablity zone [AZ] ?

## IAM

1. What is IAM ?
2. What is policy ?
3. What is an IAM role

### S3

1. What is s3 and why do we use it ?
2. what is a bucket ?
3. can we have 2 buckets with same name ?
4. what is storage limit of s3
5. what are different storage classes in s3 ?
6. What are lifecycle policies ?
7. Which one can you host with s3 only - dynamic or static site ? and how ?

### EC2

1. what is a virtual machine ? what is ec2 ? why it is used ?
2. what are different pricing modes for ec2 ? Explain each one
3. what are different  instance families in ec2. ? When to use which instance family , explain with examples .
4. what is elastic IP, what is difference ec2 public ip and Elastic IP
5. Explain pricing of Elastic IP
6. how to increase CPU/RAM of ec2 instance/ how to change instance size of ec2 instance ?
7. you got an e-mail of hardware degradation from amazon and they are retiring your ec2 instance, how do you tackle this ?
8.  what is an AMI
9. can you share your AMI publicly or with another AWS account
10. What is an security group
11. Difference between security group and NACL
12. What is a key-pair/Pem file in EC2. 
13. How to recover an Lost Pem file/ Key-pair
14.  What is ec2 User-Data ?
15. What is shutdown / Hibernate / Terminate option in EC2
16. can you add multiple security groups in ec2 ?

### EBS and EFS

1. What is EBS ? Explain usage 
2. what are different type of EBS ?
3. what is Block based storage  ?
4. What is object based storage ?
5. what is IOPS ?
6. How many IOPS are available in GP2
7. What is provisoned IOPS and when to use it ?
8. What is instance store ?
9. EBS vs Instance store ?
10. What is EFS? Explain Benefits ?

### Load Balancer 

1. What is load balancer ? why do we use it ?
2. Explain CLB, ALB, NLB
3. What is load balacer stickiness ?
4. What is Cross-Zone load balancing ?
5. What are health checks in Load Balancers ?
6. What are listeners  ?
7. What are target groups in ALB ?
8. CLB vs ALB vs NLB 

### AutoScaling

1. What is an ASG ?
2. What is Launch config ?
3. Explain Minimum , Maximum and Desired  capacity  in an ASG .
4. What are different scaling policies ?
5. Can you recieve traffice from a load balancer in ASG 
6. How do you deploy code to ASG ?