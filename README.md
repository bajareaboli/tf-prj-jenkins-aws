# project-cts 

**Auto Provision of Jenkins on AWS EC2**

Terraform Scripts for ec2 provsion and Jenkins install on it.
Jenkins Install scripts

Using these scripts you can automate the provision of Jenkins on AWS EC2 instance.

Before executing terraform apply command, login aws console and create a KeyPair and downlaod the publickey (*.pem). This key is will associated with ec2 instance and will be used to ssh to ec2 instance whenever it is needed.

Once the key is generated and add the keyname. Please ensure the keypair must be created in the same region that you are going to provide ec2 instance.

