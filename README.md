# Database-Course-Documentation
1- Flat File Structure:

- Stores data in one single table or spreadsheet-like format.

- Data is saved as plain text, often separated by commas or tabs.

- No built-in way to connect related data across different files.


2- Relational Database Structure:

- Stores data in multiple linked tables.

- Each table holds one type of entity (e.g., Customers, Orders).

- Uses Primary Keys and Foreign Keys to create relationships.



3- Key Difference in Flat Files: 
-  High redundancy. The same data (like customer info) must be repeated in every related record,    making updates inconsistent.

4- Relational Databases:
-  Low redundancy. Unique data is stored once and linked to other tables via keys, ensuring consistency.

5- When to Use Flat Files:
 - Simple, independent data with no complex relationships.

6- Databases:
- Complex, interrelated data where integrity and scalability matter.

7- Drawbacks Flat Files:


- High redundancy and inconsistency.

- Hard to manage large datasets.

- No data relationships.

- Poor multi-user control.

- Limited security.

8- Databases:

- More complex to set up and manage.

- Needs technical knowledge (SQL).

- Requires maintenance and resources.

- Higher initial cost.


# DBMS Advantages – Mind Map
<img width="1920" height="1080" alt="DBMS advantages" src="https://github.com/user-attachments/assets/c13af1e7-e002-437d-aba5-f2d576373f6a" />


# Roles in a Database System

-System Analys:
Acts as a bridge between business needs and technical solutions.

Database Designer
 Acts as the architect of the database, creating the structure to store and organize data efficiently.

Builds, maintains, and troubleshoots databases to handle large amounts of information securely and efficiently.

Database Administrator (DBA)
 Ensures the database is secure, available, and running smoothly at all times.

Application Developer
Converts client requirements into functional software applications that interact with the database.

BI (Business Intelligence) Developer
 Turns raw data into meaningful insights and reports to help businesses make data-driven decisions

# Types of Databases

Relational vs. Non-Relational Databases
Relational Databases (RDBMS):

Organize data into interrelated tables with rows and columns.

Use SQL (Structured Query Language) for querying and enforcing relationships.

Ensure data accuracy and integrity using schemas and constraints.

Examples: MySQL, PostgreSQL, Oracle.

Use Cases: Finance, healthcare, ERP systems – where structured data and complex queries are required.

Non-Relational Databases (NoSQL):

Store data in flexible formats such as documents, key-value pairs, graphs, or column stores.

Support schema-less design, ideal for unstructured or semi-structured data.

Designed for scalability and high traffic using distributed clusters.

Examples: MongoDB, Cassandra, Redis.

Use Cases: Social media apps, IoT networks, content management systems – where flexibility and rapid scaling are important.

Centralized vs. Distributed vs. Cloud Databases
Centralized Database:

All data is stored on a single server or location.

Advantages: Easy to manage, consistent data source.

Disadvantages: Single point of failure, limited scalability.

Use Case: Small businesses or organizations with one office.

Distributed Database:

Data is spread across multiple servers or geographic locations.

Advantages: High availability, better performance, fault tolerance.

Disadvantages: Complex management and synchronization.

Use Case: Large e-commerce platforms or multinational companies.

Cloud Database:

Hosted on cloud platforms like AWS, Azure, or Google Cloud.

Advantages: Scalable, accessible from anywhere, managed infrastructure.

Disadvantages: Requires internet, potential data privacy concerns.

Use Case: SaaS applications, startups, and apps needing global access.

3. Use Case Examples for Each Type
Relational Database Example:

A bank storing customer accounts and transactions with strict consistency requirements.

Non-Relational Database Example:

A social media app storing user profiles, posts, and comments that need rapid scaling.

Centralized Database Example:

A small retail shop with one location managing its inventory on a single server.

Distributed Database Example:

An online marketplace (like Amazon) with data replicated across regions for speed and fault tolerance.

Cloud Database Example:

A SaaS company using Amazon RDS or Azure SQL to allow global user access without managing hardware.
