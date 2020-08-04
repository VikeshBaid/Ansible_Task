# Ansible Task

## Task 1: Lauched Docker Container on EC2 Instance using Ansible

### Important Points for Task 1:

1. httpd_configuration: It is the group for all the managed node ip, and ssh credentials where we have  to set up httpd server.
2. Tasks: It includes all the task we want to perform using ansible modules
3. Modules:
   1. yum_repository: To create a yum repository inside a rpm based system. Go to the [yum_repository module docs](https://docs.ansible.com/ansible/latest/modules/yum_repository_module.html "yum_repository docs"), for more information.
   2. package: To install a software using name of the package. Go to the [package module docs](https://docs.ansible.com/ansible/latest/modules/package_module.html "package docs"), for more information.
   3. service: To start or stop the service. Go to the [service module docs](https://docs.ansible.com/ansible/latest/modules/service_module.html "service docs"), for more information.
   4. command: Used when there is a requirement to run specific commands. Go to the [command module docs](https://docs.ansible.com/ansible/latest/modules/command_module.html "command docs"), for more information.
   5. file: To create a file or directory in managed node. Go to the [file module docs](https://docs.ansible.com/ansible/latest/modules/file_module.html "file module docs"), for more information.
   6. copy: To copy a static file to managed node. Go to the [copy module docs](https://docs.ansible.com/ansible/latest/modules/copy_module.html "copy module docs"), for more information.
   7. docker_image: used to pull image from docker hub. Go to the [docker_image module docs](https://docs.ansible.com/ansible/latest/modules/docker_image_module.html "docker_image module docs), for more information.
   8. docker_container: To run a contianer on the managed node. Go to the [docker_container module docs](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html "docker_contianer module docs"), for more information.  
