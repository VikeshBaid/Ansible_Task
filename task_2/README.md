# Task 2: Launch an EC2 Instance using Ansible and use IP Address to setup a httpd server

## Modules Used:

1. "ec2_instance" module: to launch the EC2 Instance. [Docs Link](https://docs.ansible.com/ansible/latest/modules/ec2_instance_module.html) 
2. "package" module: To install httpd package. [Docs Link](https://docs.ansible.com/ansible/latest/modules/package_module.html)
3. "add_host" module: To create a in memeory inventory which can be used by play to get the "host Ip address".[Docs Link](https://docs.ansible.com/ansible/latest/modules/add_host_module.html)
4. "service: module: to start the httpd service inside the ec2 instance.[Docs Link](https://docs.ansible.com/ansible/latest/modules/service_module.html)
5. "copy" module: to copy the website/webpages to the ec2 instance, in the "/var/www/html" folder.[Docs Link](https://docs.ansible.com/ansible/latest/modules/copy_module.html)

In ec2_instance we have to use "aws_access_key" and "aws_secret_key" to let ansible create a instance. This provides the access policy, which tells AWS the power of the user.
