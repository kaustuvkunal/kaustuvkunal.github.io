---
title: "Data Automation System "
collection: Projects
type: 
permalink: /projects/das
desc: "Big-data processing production system deployed over Cloud" 
date: 2016-02-01
location: ""
---

Data Automation system

## DAS (Data Automation system)

Data Automation System is a resilient, autoscaling, near real-time Big Data processing automation systems based on Hadoop, Amazon Elastic Beanstalk, CloudBreak, Cascading and Java. DAS systems process thousands of campaign’s events & clicks data at the scale of Petabytes per day. We have used Hadoop MapReduce, Avro and Cascading modules for processing impression, click and event data. 
 
 
##  DAS Architecture 

- DAS architecture is based on <B>Server As a function</B>
- DAS has four module and each execute as a separate server
	- Data Pump : To copy log data into DAS
	- Data Filter : To Structure the data (Avro)
	- Data Summary :  To Process the data
	- Data Reporting :   Prepare customized  business relevant reports


![ ](/images/das.png)


##  Technologies 

- Avro
- MapReduce
- Spark
- Cascading 
- Java
- Maven
- Netbeans
- Springboot
