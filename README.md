# Hosting_On_Amazon_EC2

### Objective:  
Install, configure, and launch a WordPress blog on an Amazon Linux 2023 instance. <br>  

 

### Architecture: 

A VPC with one public subnet and one private subnet in one Availability Zone. 

A Network Load Balancer in the public subnet. 

An EC2 instance acting both as a web server and a database server in the private subnet. 

A webserver security group configured to allow HTTPs traffic to the Amazon EC2 web and database server. 


 ![Architecture_Host a WordPress Blog](https://github.com/user-attachments/assets/5293783a-b464-41e1-baa5-0931432e281c)



### Summary of Tasks Completed: 

1. Launch an EC2 using AWS Session Manger 

2. Downloaded software pages for setting up database and web server 

3. Downloaded latest WordPress package 

4. Configuring SSL/TLS on Amazon Linux 2023 

5. Install and configure MarDB Server and set up a database for WordPress installation 

![Host a WordPress Blog_MariaDB install](https://github.com/user-attachments/assets/c8c4825d-bc4d-4936-8e8b-5763c7dbf02b)

6. Configure WordPress installation - Edited WordPess configuration files to fit specifications provided 

7. Installing WordPress files under Apache document root 

8. Allow WordPress to use permalinks 

9. Installing PHP graphics drawing library on the Amazon Linux image 

10. Configuring WordPress file permissions for Apache web server 

11. Launching WordPress installation script and verified database server and Apache web server are launched 

![Hosting a WordPress Blog_Wordpress Installation](https://github.com/user-attachments/assets/26551ea8-e73a-4f9a-9e15-52e6b36e28bd)

12. Verified WordPress blog has been activated and running! Logged into WordPress with username and password created 

![Hosting a WordPress Blog_HomePage of Site](https://github.com/user-attachments/assets/66e69a25-18b3-438b-b96f-9e653c2366d8)

 

 
