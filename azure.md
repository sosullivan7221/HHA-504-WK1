## Compute

1. SQL Server

    Microsoft Azure gives users access to a virtual machine SQL Server. They have a variety of VM locations and sizes to accomodate the user's needs and geographic location. Some features include automated backups, automated patching, flexible licensing, flexible versions, and disaster recovery. Python can be used to access the data that is stored using a package called pyodbc, allowing direct connection to the SQL tables. Pandas could then be used to read a SQL query and turn it in a dataframe in which data can be analyzed.

2. API Apps

    Azure allows users to use their cloud environment to create web applications and use RESTful APIs. It supports multiple languages, is highly scalable, and provides DevOps and security tools for the application. Through Flask and Django, users can create python-based web applications that are running through Azure's cloud.


## Databases

1. Azure Confidential Ledger

    Azure Confidential Ledger is a data storage designed specifically for high value and sensitive data. All of the data is hardware backed and designed to be tamper proof, designed to store data such as business transactions, administrative and control changes, and security events. There are packages that exsit specifically for utilization in python. Python applications that are using Acure Confidential Ledger create varables and, store them confidentially, and interact with the variables.

2. Azure Migration Database Service

    Azure Migration Database Service is a tool used for migrating already existing databses onto Azure's cloud servers. This can be done using Azure's SQL migration extension for Azure Data Studio, Azure Portal, Powershell, and Azure CLI. This service can interact with MySQL, RDS MySql, PostgreSQL, and MongoDB. While python may not be used to directly interact with the migration of the databases, python will be able to interact with the SQL databases once they are onto the azure server for data analysis.


## Storage

1. Azure Data Lake Storage

    Azure supports a data lake platform, allowing any user to store data that exists in multiple formats. Data is stored in blobs in a hierarchical structure due to the varying formats. It supports large scalability and a finer grain security model with optimized costs and performance. Python can use packages to directly interact with this storage. The Azure Storage File Datalake and Azure Identity packages are used to allow users to interact and create directories and files.

2. Azure Queue Storage

    Azure Queue Storage allows users to store a large number of messages at once. These messages can be accessed using HTTP or HTTPS. The queues are used to create a backlog of work to be completed. By installing the Azure Identity and Azure Storage Queue packages, python is able to interact with this queue storage. Within python, you can create, receive, delete, and peek at messages that are in the queue.

