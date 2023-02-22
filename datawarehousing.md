## Data Warehouse 
A data warehouse is a type of data management system that is designed to enable and support business intelligence (BI) activities, especially analytics. Data warehouses are solely intended to perform queries and analysis and often contain large amounts of historical data. The data within a data warehouse is usually derived from a wide range of sources such as application log files and transaction applications.
A data warehouse centralizes and consolidates large amounts of data from multiple sources. Its analytical capabilities allow organizations to derive valuable business insights from their data to improve decision-making. Over time, it builds a historical record that can be invaluable to data scientists and business analysts. Because of these capabilities, a data warehouse can be considered an organization’s “single source of truth.”
A typical data warehouse often includes the following elements:

A relational database to store and manage data
An extraction, loading, and transformation (ELT) solution for preparing the data for analysis
Statistical analysis, reporting, and data mining capabilities
Client analysis tools for visualizing and presenting data to business users
Other, more sophisticated analytical applications that generate actionable information by applying data science and artificial intelligence (AI) algorithms, or graph and spatial features that enable more kinds of analysis of data at scale
# Benefits of a Data Warehouse
Data warehouses offer the overarching and unique benefit of allowing organizations to analyze large amounts of variant data and extract significant value from it, as well as to keep a historical record.

Four unique characteristics (described by computer scientist William Inmon, who is considered the father of the data warehouse) allow data warehouses to deliver this overarching benefit. According to this definition, data warehouses are

Subject-oriented. They can analyze data about a particular subject or functional area (such as sales).
Integrated. Data warehouses create consistency among different data types from disparate sources.
Nonvolatile. Once data is in a data warehouse, it’s stable and doesn’t change.
Time-variant. Data warehouse analysis looks at change over time.
A well-designed data warehouse will perform queries very quickly, deliver high data throughput, and provide enough flexibility for end users to “slice and dice” or reduce the volume of data for closer examination to meet a variety of demands—whether at a high level or at a very fine, detailed level. The data warehouse serves as the functional foundation for middleware BI environments that provide end users with reports, dashboards, and other interfaces.

## Data Warehouse Architecture
The architecture of a data warehouse is determined by the organization’s specific needs. Common architectures include

Simple. All data warehouses share a basic design in which metadata, summary data, and raw data are stored within the central repository of the warehouse. The repository is fed by data sources on one end and accessed by end users for analysis, reporting, and mining on the other end.
Simple with a staging area. Operational data must be cleaned and processed before being put in the warehouse. Although this can be done programmatically, many data warehouses add a staging area for data before it enters the warehouse, to simplify data preparation.
Hub and spoke. Adding data marts between the central repository and end users allows an organization to customize its data warehouse to serve various lines of business. When the data is ready for use, it is moved to the appropriate data mart.
Sandboxes. Sandboxes are private, secure, safe areas that allow companies to quickly and informally explore new datasets or ways of analyzing data without having to conform to or comply with the formal rules and protocol of the data warehouse.
## What is a Cloud Data Warehouse?
A cloud data warehouse uses the cloud to ingest and store data from disparate data sources.

The original data warehouses were built with on-premises servers. These on-premises data warehouses continue to have many advantages today. In many cases, they can offer improved governance, security, data sovereignty, and better latency. However, on-premises data warehouses are not as elastic and they require complex forecasting to determine how to scale the data warehouse for future needs. Managing these data warehouses can also be very complex.

On the other hand, some of the advantages of cloud data warehouses include:

Elastic, scale-out support for large or variable compute or storage requirements
Ease of use
Ease of management
Cost savings
The best cloud data warehouses are fully managed and self-driving, ensuring that even beginners can create and use a data warehouse with only a few clicks. An easy way to start your migration to a cloud data warehouse is to run your cloud data warehouse on-premises, behind your data center firewall which complies with data sovereignty and security requirements.

In addition, most cloud data warehouses follow a pay-as-you-go model, which brings added cost savings to customers.

## What is a Modern Data Warehouse?
Whether they’re part of IT, data engineering, business analytics, or data science teams, different users across the organization have different needs for a data warehouse.

A modern data architecture addresses those different needs by providing a way to manage all data types, workloads, and analysis. It consists of architecture patterns with necessary components integrated to work together in alignment with industry best practices. The modern data warehouse includes:

A converged database that simplifies management of all data types and provides different ways to use data
Self-service data ingestion and transformation services
Support for SQL, machine learning, graph, and spatial processing
Multiple analytics options that make it easy to use data without moving it
Automated management for simple provisioning, scaling, and administration
A modern data warehouse can efficiently streamline data workflows in a way that other warehouses can’t. This means that everyone, from analysts and data engineers to data scientists and IT teams, can perform their jobs more effectively and pursue the innovative work that moves the organization forward, without countless delays and complexity.

## Designing a Data Warehouse
When an organization sets out to design a data warehouse, it must begin by defining its specific business requirements, agreeing on the scope, and drafting a conceptual design. The organization can then create both the logical and physical design for the data warehouse. The logical design involves the relationships between the objects, and the physical design involves the best way to store and retrieve the objects. The physical design also incorporates transportation, backup, and recovery processes.

Any data warehouse design must address the following:

### Specific data content
Relationships within and between groups of data
The systems environment that will support the data warehouse
The types of data transformations required
Data refresh frequency
A primary factor in the design is the needs of the end users. Most end users are interested in performing analysis and looking at data in aggregate, instead of as individual transactions. However, often end users don’t really know what they want until a specific need arises. Thus, the planning process should include enough exploration to anticipate needs. Finally, the data warehouse design should allow room for expansion and evolution to keep pace with the evolving needs of end users.

The Cloud and the Data Warehouse
Data warehouses in the cloud offer the same characteristics and benefits of on-premises data warehouses but with the added benefits of cloud computing―such as flexibility, scalability, agility, security, and reduced costs. Cloud data warehouses allow enterprises to focus solely on extracting value from their data rather than having to build and manage the hardware and software infrastructure to support the data warehouse.
## Schemas in data warehouses
Schemas are ways in which data is organized within a database or data warehouse. There are two main types of schema structures, the star schema and the snowflake schema, which will impact the design of your data model.

Star schema: This schema consists of one fact table which can be joined to a number of denormalized dimension tables. It is considered the simplest and most common type of schema, and its users benefit from its faster speeds while querying.

Snowflake schema: While not as widely adopted, the snowflake schema is another organization structure in data warehouses. In this case, the fact table is connected to a number of normalized dimension tables, and these dimension tables have child tables. Users of a snowflake schema benefit from its low levels of data redundancy, but it comes at a cost to query performance. 
### The Evolution of Data Warehouses—From Data Analytics to AI and Machine Learning
When data warehouses first came onto the scene in the late 1980s, their purpose was to help data flow from operational systems into decision-support systems (DSSs). These early data warehouses required an enormous amount of redundancy. Most organizations had multiple DSS environments that served their various users. Although the DSS environments used much of the same data, the gathering, cleaning, and integration of the data was often replicated for each environment.

As data warehouses became more efficient, they evolved from information stores that supported traditional BI platforms into broad analytics infrastructures that support a wide variety of applications, such as operational analytics and performance management.

Data warehouse iterations have progressed over time to deliver incremental additional value to the enterprise with enterprise data warehouse (EDW).




