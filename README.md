# A-high-available-web-app-Deployment-on-AWS-Infrastruacture-
The project shows Deployment of web servers for a highly available web app using CloudFormation.
This project has a diagram that helps to visualize, understand, and optimize the cloud infrastructure.
The second part is CloudFormation script to build and automate AWS infrastructure in Yaml format which is readable data-serialization language
The Cloudformation script deploys a VPC_four Application servers,two located in each of Private subnets. 
the launch configuration will be used by an auto-scaling group,a pair of NAT Gateways available in Public Subnets (one in each AZ), 
and default routes for them in the private subnets.Intstance Size and AMI spec_Two VCPU,4GB OF RAM, OS_Ubuntu 18 with 10 GB of Disk space
