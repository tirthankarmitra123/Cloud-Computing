# Cloud-Computing

# FIGMA

COMPANY: CODTECH IT SOLUTIONS

NAME: Tirthankar Mitra

*INTERN ID*: CT120AU

*DOMAIN*:: Cloud Computing

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

#DESCRIPTION 

Here I create a AWS S3 object storage service and upload a text file in a bucket. 
An Amazon S3 bucket is a public cloud storage resource available in Amazon Web Services (AWS) Simple Storage Service (S3) platform. It provides object-based storage, where data is stored inside S3 buckets in distinct units called objects instead of files.

Amazon S3 buckets are similar to file folders and can be used to store, retrieve, back up and access objects. Each object has three main components -- the object's content or data, a unique identifier for the object and the descriptive metadata, including the object's name, URL and size.
An object must exist within a bucket, as it can't exist alone. Each Amazon account could have hundreds of buckets, each containing numerous objects.

What are S3 buckets used for?
Amazon's Simple Storage Service buckets are mainly used to help individuals and enterprises meet their data storage, backup and delivery needs in the cloud.
An infinite amount of data can be stored and protected using Amazon S3 buckets for a variety of use cases:
Data lakes.
Dynamic websites.
Mobile applications.
Backup and restore operations.
Big data analytics.
User-generated content.
Storage archives.
Enterprise applications.
IoT devices.

I follow these following steps- 
Step 1: create an AWS S3 bucket

Go to AWS console home > Search S3 > Select Buckets > Create Bucket > 
in Create Bucket window, select- 
Bucket type- General Purpose
Bucket Name- myawsbucket8563
object ownership- ACLS disabled
Uncheck all public access
Bucket versioning- disable
Encryction type- server side encryption with Amazon S3 managed key
Bucket key- enable
Select Create Bucket 

after creating bucket Go to myawsbucket8563 > upload > add files > select file1 > open > upload 

Step 2: Create a user 

Go to security credentials > users > create user > user name- mybucketuser1 > next > set permission >
permission option - add user to a group > next > create user 

Step 3: Add permissions to the user

Go to mybucketuser1 > add permission > create inline policy > service- S3 > select all S3 actions > Resources- all > next
policy name- user1policy > create policy

*Output*

![Image](https://github.com/user-attachments/assets/cc2d47b0-259d-4494-a2df-1a761ce3d18c)
![Image](https://github.com/user-attachments/assets/4166b30d-cf6e-4bbb-852d-4b0576aee281)
