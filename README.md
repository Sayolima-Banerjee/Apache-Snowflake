# **Apache Snowflake**

## **What is Snowflake**?

Snowflake is an analytic data warehouse provided as *Software-as-a-Service (SaaS)*. It provides a data warehouse that is faster, easier to use and far more flexible than traditional data warehouse offerings. 

It is a *Cloud Data Platform* which gives us the ability to perform data analysis without worrying about lot of internal details about data warehouse.

The **Snowflake**  combines a completely new SQL query engine with an innovative architecture natively designed for the cloud.

## **Features of Snowflake Data Warehouse**

* **Security and Data Protection** - Snowflake data warehouse provides Multi-Factor Authentication (MFA), federal authentication and Single Sign-on (SSO) and OAuth. All the communication between the client and server is protected by TLS.

* **Standard and Extended SQL Support** - Snowflake data warehouse supports most DDL and DML commands of SQL. It also supports advanced DML, transactions, lateral views, stored procedures, etc.

* **Connectivity** - It supports Python connector, Spark connector, Node.js driver, .NET driver, etc.

* **Data Sharing** - It offers us to securely share our data with other Snowflake accounts.


## **Snowflake Architecture**

Snowflake architecture comprises a hybrid of traditional shared-disk and shared-nothing architectures to offer the best of both.

Similar to shared-disk architectures, Snowflake uses a central data repository for persisted data that is accessible from all compute nodes in the platform. But similar to shared-nothing architectures, Snowflake processes queries using MPP (massively parallel processing) compute clusters where each node in the cluster stores a portion of the entire data set locally. This approach offers the data management simplicity of a shared-disk architecture, but with the performance and scale-out benefits of a shared-nothing architecture.

It consists of three key layers
* Storage Layer
* Compute Layer
* Cloud Services Layer

### **Storage Layer**

Snowflake organizes the data into multiple micro partitions that are compressed and optimized internally. Here columnar format is used to store. Data is stored in the cloud storage and works as a shared-disk model, making data management simple. 

### **Compute Layer**

Snowflake uses “Virtual Warehouse” for running queries. It separates the query processing layer from the disk storage. Queries execute in this layer using the data from the storage layer.

### **Cloud Services Layer**

All the activities such as authentication, security, metadata management of the loaded data and query optimizer that coordinate across Snowflake happens in this layer.

## **Advantages of Snowflake**

* **Easy to Implement** - Snowflake is offered as a *Software-as-a-Service (SaaS)* which can be quickly implemented without affecting our day to day work. Its implementation does not require any expensive software or hardware configuration. Snowflake brings all our data into one system and the process for analysis is simplified.

* **Cloud-First Approach** - It has been designed to harness the power of cloud computing technology. It simplifies the process to store and analyze data using cloud-based software and hardware. It's cloud-oriented design supports multi-cloud systems and cross-cloud applications.

* **Performance** - It provides high performance compared to traditional data warehouse platforms. Its advanced architecture allows the users to run huge volumes of queries and to easily scale up and down, based on the requirements. The Infinite scalability feature allows its users to manage all workloads independently without affecting systems overall performance. 

* **Supports Multiple Data Structures** - Unlike the traditional data warehouse platforms, Snowflake supports both structured and semi-structured data. It allows users to combine all types of structured and unstructured data for analysis and load it into a database without demanding any transformations or conversions. It automatically optimizes the data storage and querying process.

* **Advanced Data Sharing Capabilities** - Snowflake architecture supports advanced data sharing capabilities and streamlines the process to share data among its users. It also supports data sharing with external parties using reader accounts.

* **Access and Security** - It can be distributed across all the regions of the cloud provider. It has been designed in such a way to deliver constant services and shows little impact even when there are component or network failovers. It also offers advanced security measures by using SOC2 type II and more extra standard features.

## **Disadvantages of Snowflake**

* Snowflake owns the deployment infrastructure which makes the organizations fully depend on it. During times of emergency, it becomes a challenging task to take fast actions.

* Snowflake shared cloud layer is shared among a large number of customers. If any security incident occurs the entire data will be exposed to all the customers.

* It works on very few cloud tools like AWS, Azure and Google cloud.



## **How to Connect to Snowflake**

There are multiple ways to connect to Snowflake : 

* A web-based user interface from which all aspects of managing and using Snowflake can be accessed.
* Command line clients (e.g. SnowSQL) can also access all aspects of managing and using Snowflake.
* ODBC and JDBC drivers that can be used by other applications (e.g. Tableau) to connect to Snowflake.
* Native connectors (e.g. Python, Spark) that can be used to develop applications for connecting to Snowflake.
* Third-party connectors that can be used to connect applications such as ETL tools (e.g. Informatica) and BI tools (e.g. ThoughtSpot) to Snowflake.


---

### **Reference Links**

[Reference 1](https://docs.snowflake.com/en/user-guide/intro-key-concepts.html)
[Reference 2](https://hevodata.com/blog/snowflake-architecture-cloud-data-warehouse/)
