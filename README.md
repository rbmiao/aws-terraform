Create id_rsa. It will be uploaded to AWS
```
ssh-keygen
```
terraform init
terraform plan
terraform apply

It will create alb, elb, nlb in a new VPC. Then 3 instances will be launched in private subnets.

https://techbloc.net/archives/3167
https://techbloc.net/archives/3195


