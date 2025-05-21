

![image alt](https://github.com/Gertrudechichi/Relational-database/blob/d79b5e74cd2987320cc4fafcc52ed4a290000182/Relational%20database%20infrastructure%20options.png)
 
 
 Traditional relational database services such as MySQL, PostgreSQL, oracle run on the on-premise environment. With AWS resources such as EC2 instances, Amazon RDS and Amazon Aurora, a more scalable, flexible and reliable infrastructure to host databases can be made available.
A database hosted on the on-premise environment can be migrated to the cloud and can benefit from the cloud platform which provides a scalable, flexible and highly available infrastructure. By leveraging database migration service, databases can be migrated to EC2 instances, Amazon RDS or even Amazon Aurora. The database ceases to exit in the data-center (on-premise) and it will run in the cloud environment by leveraging the cloud platforms mentioned.

Ec2 as an Infrastructure as a service can provide the compute power such as CPU, memory and storage needed to run databases in a more efficient manner compared to on-premise data-centers. With an EC2 instance, the user will have complete control over the instance just like having control over storage, Operating system, network CPU on the on-premise data-center. EC2 can also be attached to autoscaling groups to automatically scale in or out, up or down in response to traffic demands which user has control of as well.
The disadvantage of hosting your database on EC2 is that, administrative tasks to keep the instance running such as patching, disaster recovery, failover and backups is the responsibility of the user and not on AWS. However, if you are looking at having control of your EC2 instance and the compute resources then Amazon EC2 is the best option.
Amazon RDS is a more managed service by AWS and it supports most of the major traditional database engines such as PostgreSQL and MySQL hosted on premise. Instead of running a database on EC2 instance, a database can be run on Rds. With RDS, AWS manages the patching backups, redundancy and failovers. AWS provides heavy lifting of infrastructure management when RDS is used to run your databases instead of EC2.

A more managed service is Amazon Aurora. Aurora which provides a serverless platform for running databases. Aurora is cost effective highly available and redundant across multiple availability zones.








This demo shows a screenshot of the step by step procedure in creating database instance on the AWS management console. MySQL engine was used and was connected SQL workbench which is an open-source MySQL client. Using the workbench, a database schema was designed using simple SQL queries.

A major challenge was that, the change in IP address due to a change in my location made it impossible to connect to the workbench. After troubleshooting and changing the security group settings to suit the current IP there was a successful connection of the database instance to the MySQL workbench.

Overall, relational databases are suitable for data analytics and business intelligence workloads because relational databases have a well defined schema necessary to run queries and derive insights for business operations.  



DEMO- Connecting Amazon RDS to MySQL Workbench: A Step-by-Step Guide




![image alt](https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20075805.png)



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20075822.png


https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20075923.png


https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20080004.png



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20080132.png



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20080200.png



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20080229.png



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20080648.png


https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20080711.png


https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20080850.png



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20081001.png



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20081024.png



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20081503.png



https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20081845.png


https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20082135.png


https://github.com/Gertrudechichi/Relational-database/blob/8389ef88541a7fff957230e3f0b6473b08b0f3e6/Screenshot%202025-05-15%20082241.png









