# EC2 Web Server Terraform Project

This project provisions an AWS EC2 instance and a security group using Terraform. The EC2 instance is configured as a basic web server running Apache HTTPD.

## Resources

- **EC2 Instance**: Launches an Amazon Linux instance and installs Apache HTTPD with a custom welcome page.
- **Security Group**: Allows inbound HTTP (port 80) traffic from anywhere and all outbound traffic.

## Input Variables

- **region**: (Required) AWS region where resources will be created.
