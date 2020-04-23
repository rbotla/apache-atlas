
Create an EC2 instance
```
aws ec2 run-instances --image-id ami-173d747e --count 1 --instance-type t2.micro --key-name ravi-aws-web.pem --security-groups my-sg
```
