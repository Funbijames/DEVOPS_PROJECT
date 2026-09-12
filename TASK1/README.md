# DEVOPS PROJECT

# WEB STACK IMPLEMENTATION
## (LAMP STACK)

## PREPARING PREREQUISITES

For this project, an AWS EC2 instance was created using Ubuntu Server.

The EC2 instance was used as the server environment for implementing the LAMP stack.

The LAMP stack consists of:

- Linux
- Apache
- MySQL
- PHP

### AWS EC2 SERVER

The Ubuntu server was accessed through AWS EC2 Instance Connect.

![AWS EC2 Ubuntu Server](image-1.png)


# STEP 1 - INSTALLING THE APACHE WEB SERVER

Apache is the web server component of the LAMP stack. It is responsible for receiving HTTP requests and serving web pages to visitors.

First, the server's package index was updated.

```bash
sudo apt update
