# AWS-WordPress-Project
# this is my wordpress project
 this is my wordpress project
 1.a: Provisioning an Ubuntu Server on AWS
I began with provisioning an Ubuntu server using EC2 Compute service provided by AWS. I selected the Ubuntu 22.04 LTS t.2 micro instance type and deployed the server in the region closest to me, in this case, eu-west-2 (London). 
I modified the instance settings for the storage and network configuration ( 8GB SSD gp2 and default VPC). I also added a simple tag in order to identify my resource.
I also configured the security group of the instance by setting inbound rules in order to allow SSH, HTTP & HTTPS traffic into my server. This kept port 22, 80 and 443 open for incoming traffic from all hosts (0.0.0.0/0). Once this was completed, I launched the ubuntu server and it was up and running very quickly

