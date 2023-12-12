# This project deals with hosting a php application 
setps followed for quick review:
-create an ec2 instance 
-update 
-install apache2 web server 
-upload the php code 
-create a RDS resource with required credentials in the aws 
-update the security groups with the required ports 
-check the local status of appplication with instance ip
-log into the mysqldb from the ec2 instance 
-use the specified database name and create a table of any name as requirement  
-try to enter the user data from the website might get error 
-provide the endpoint and db details in the php code and save and exit 
-refresh the page will able to see the user data recorded as expected 
-now, autoscaling the application for high avaliblility and scalability
-create a AMI from the base instance 
-lunch in different region and enable all the subnets 
-attach it to the load balancer and specify the required number of instances 
-then attach it to the route53 with given website hostaddress
-can be attached to the CDN  for edge location and low latency
-verify the end user experinece 
----------------------------------------------------------------
sudo apt-get update
sudo add-apt-repository -y ppa:ondrej/php
sudo apt install php5.6 mysql-client php5.6-mysqli
mysql -h endpoint -u username-of-db -p
show databases 
create table data(firstname varchar(15), email varchar(25));
select * from the tablename 
---------------------------------------------------------------------------





