# 📘 Database Course Documentation

This repository captures important concepts from a database course. It covers the design and usage of modern databases, including cloud-based ones, as well as organized comparisons, diagrams, and realistic role descriptions. The aim is to increase our understanding of the functioning of databases as well as the connections between various systems and technologies.

---

## 📂 Table of Contents

1. [Relational Databases vs. Flat File Systems](#relational-databases-vs-flat-file-systems)
2. [Benefits of DBMS – Mind Map](#benefits-of-dbms--mind-map)
3. [A Description of Database Roles](#a-description-of-database-roles)
4. [Different Kinds of Databases](#different-kinds-of-databases)
5. [Cloud Storage and Databases](#cloud-storage-and-databases)
6. [List of References](#list-of-references)

---
<a name="relational-databases-vs-flat-file-systems"></a>
## 🆚 Relational Databases vs. Flat File Systems

The following comparison between relational databases and flat file systems is based on redundancy, structure, relationships, applications, and downsides.

| Attribute       | Flat File Systems                                                                 | Relational Databases                                                                 |
|----------------|-------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| **Structure**   | Data is stored in plain text files, such as CSV files. There are no regulations or enforcement. | Utilizes a well-organized framework with tables, defined schemas, rows, and columns. |
| **Redundancy**  | Frequently includes duplicate information.                                         | The redundancy is lessened by design strategies like normalization.                  |
| **Relationships**| No built-in mechanism for data relation.                                          | Using keys (primary and foreign) to connect tables helps ensure consistency.         |
| **Usage Examples**| Perfect for straightforward jobs like logs or configs.                           | Utilized in real-world applications such as banking systems, inventory management, and e-commerce sites. |
| **Drawbacks**   | Not scalable for complicated systems and prone to mistakes.                        | Needs preparation and configuration, but far superior for managing and querying complex data. |

---
<a name="benefits-of-dbms--mind-map"></a>
## 🧠 Benefits of DBMS – Mind Map

Databases offer far more than just storing data. Below is a mind map showing the main advantages of using a Database Management System (DBMS).

![DBMS Mind Map](./images/dbms_mind_map.png)  
*Created using Mermaid Live Editor*

### Important points

- **Security**: User authentication, encryption, and access controls.  
- **Integrity**: Maintains data accuracy and consistency while following rules and restrictions.
- **Backup**: Helps one to get over crises and go back to past data situations.
- **Redundancy Control**: Prevents data from being repeated unnecessarily.  
- **Concurrency**: Enables several users to collaborate on the same data without any conflicts.  
- **Data Sharing**: Facilitates data access centrally for various users and programs.  

---
<a name="a-description-of-database-roles"></a>
## 👥 A Description of Database Roles

Various individuals have different duties in relation to the database in a genuine project. The following is a list of who does what:

- **System Analyst**: Interact with consumers or clients to identifiy the system's requirements and then writes them in a manner intelligible to the team so that they can build it.  
- **Database Designer**: Converts those requirements into a design with tables, columns, relationships, and other components.
- **Database Developer**: Writes the actual code to build the database architecture and adds logic like stored procedures
- **Database Administrator (DBA)**: Keeps the database running by controlling users, carrying out backups, upholding security, and fixing problems.
- **Application Developer**: Builds the website or app that uses queries or APIs to interact with the database.
- **BI Developer**: Helps businesses make choices by using data to produce reports and dashboards.

---
<a name="different-kinds-of-databases"></a>
## 🧾 Different Kinds of Databases

### 📍 Relational vs. Non-Relational

**Relational Databases**  
- Data should be stored in well-structured tabular format with static columns.
- SQL is used to insert or retrieve data.
- Follows ACID principles (Atomicity, Consistency, Isolation, Durability).  

**Non-Relational Databases (NoSQL)**  
- Designed more flexibly. Perfect for uses needing great speeds and large data volumes.
- Data does not need tables and can be kept in several forms.

**Typical Instances Include:**
- **MongoDB** – employs documents that resemble JSON.  
- **Cassandra** – handles enormous volumes of data and simple to scale.

**Applications:**  
- *Relational:* Inventory, order management, and banking.  
- *Non-relational:* Social media, analytics, and CMS platforms.

---

### 📍 Centralized, Distributed, and Cloud-Based Databases

| Kind          | What It Means                                                                                  | Use Cases / Examples                                                  |
|---------------|-----------------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| **Centralized** | All information is kept in one location.                                                     | Desktop applications, small business tools.                           |
| **Distributed** | Though data is scattered over several places, it acts like it were a single system. | High availability needed by corporate systems.                    |
| **Cloud-Based** | Hosted by services like AWS or Azure. Provides scalability, speed, and simple maintenance.   | SaaS applications, mobile backends, and global platforms requiring low latency. |

---
<a name="cloud-storage-and-databases"></a>
## ☁️ Cloud Storage and Databases

### 🔗 What is cloud storage?

Unlike storing data on your machine or a local server, cloud storage saves data online across a network of servers. Maintaining it is largely under the control of big firms like Google, Microsoft, and Amazon.

### 🧩 What kind of database support does it offer?

Databases might expand in the cloud storage setting; instruments can be used to maintain their accessibility and backed up. For instance, a cloud database could have increased capacity or faster access without needing a change to fresh hardware.

### ✅ Advantages

- **Scalability**: Develops automatically as your need for data grows.
- **Redundancy**:Redundant copies spread around the area lower downtime.
- **Security**: Encrypted storage and access controls.  
- **Low Maintenance**: Hardware, updates, and a lot of administrative chores are handled by providers.
- **Affordable**: Only pay for what you use.  

### ⚠️ Cons

- **Vendor Lock-In**: It's challenging to switch providers without running into migration issues.
- **Internet Reliance**: Access is limited to those who have an internet connection.  
- **Additional Expenses**: Some businesses have outrageous fees for massive data transfers.
- **Intricate Setup**: You must still be familiar with cloud technologies and best practices.  

### 💻 Model Cloud DB Platforms

| Platform          | Provider         | Features                                                                 |
|-------------------|------------------|--------------------------------------------------------------------------|
| **Amazon RDS**    | AWS              | Supports a number of well-known DB engines.                              |
| **Azure SQL**     | Microsoft Azure  | Close integration with Microsoft tools.                                  |
| **Cloud Spanner** | Google Cloud     | Designed for scalability and high worldwide consistency.                 |

---
<a name="list-of-references"></a>
## 📚 List of References

- IBM. (2021). What is a relational database?: https://www.ibm.com/think/topics/relational-databases
- MongoDB. What is NoSQL?: https://www.mongodb.com/resources/basics/databases/nosql-explained
- Oracle Database Docs: https://docs.oracle.com/en/database/
- AWS RDS Overview: https://aws.amazon.com/rds/
- Azure SQL: https://learn.microsoft.com/en-us/azure/azure-sql/
- Google Cloud Spanner: https://cloud.google.com/spanner
