
Create an EC2 instance
```
aws ec2 run-instances --image-id ami-eca289fb --count 1 --instance-type t2.micro --key-name ravi-aws-web --security-group-ids sg-83365bd9 --subnet-id subnet-70e8b12c
```

