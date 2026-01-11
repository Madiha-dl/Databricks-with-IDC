# Databricks Learning Journey 🚀  
#DatabricksWithIDC  

This repository documents my daily learning and hands-on practice with Databricks, Spark, and modern data engineering concepts.

---

## 📅 DAY 1 (09/01/26) – Platform Setup & First Steps

### 📘 Topics Learned
- Why Databricks over Pandas & Hadoop
- Lakehouse architecture fundamentals
- Databricks workspace structure
- Industry use cases (Netflix, Shell, Comcast)

### 🛠️ Hands-on Tasks
- Created Databricks Community Edition (free) account
- Explored Workspace, Compute, and Data Explorer
- Created first Databricks notebook
- Executed basic PySpark commands

### 🔑 Key Takeaways
- **Databricks over Pandas & Hadoop:** Databricks addresses limitations of Pandas and Hadoop in following ways:
  
   -Enabling distributed, in-memory processing for large datasets
      
   -Providing faster execution compared to MapReduce
      
   -Supporting multiple languages (Python, SQL, Scala, R)
      
   -Offering an integrated platform for data engineering, analytics, and machine learning
      
   -Simplifying cluster management and collaboration
  
- Lakehouse combines flexibility of data lakes with reliability of warehouses
  
- PySpark enables distributed data processing with minimal setup

### 📝 Practice
Basic PySpark DataFrame creation and filtering.  
📂 Code: `Days Learning/Day 1/Pyspark_practice.ipynb`

### 🔖 Tags
#DatabricksWithIDC  
@Databricks @Codebasics @Indiandataclub

---

## 📅 DAY 2 (10/01/26) – Apache Spark FUndamentals

### 📘 Topics Learned

- **Apache Spark Architecture** - Driver, Executors, Directed Acyclic Graph (DAG)
- **DataFrames vs RDDs**
- **Lazy Evaluation in Spark**
- **Databricks Notebook Magic Commands**- %python, %sql, %f

### 🛠️ Hands-on Tasks

-Uploaded a sample e-commerce CSV dataset

-Read data into a Spark DataFrame

-Performed basic DataFrame operations - select, filter, groupBy, orderBy

-Exported transformed results to storage

### 🔑 Key Takeaways
**Spark Architecture**

-Driver coordinates execution and builds the logical execution plan

-Executors perform distributed task execution and data processing

-DAG represents the optimized execution flow of transformations

**DataFrames vs RDDs**

-DataFrames provide higher-level APIs and are Catalyst-optimized

-RDDs offer low-level control but are less efficient

-Best practice: Prefer DataFrames for most use cases

**Lazy Evaluation**

-Spark delays execution until an action is triggered

-Improves performance through query optimization

-Examples of actions: show(), count(), write()

**Notebook Magic Commands**

%python – Execute PySpark code

%sql – Run Spark SQL queries

%fs – Interact with Databricks File System (DBFS)


### 📝 Practice
Basic Operations
📂 Code: `Days Learning/Day 2/Pyspark_practice.ipynb`

