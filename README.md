# Neo4j-graph-database

##  Overview
This project demonstrates how to build and interact with a **Neo4j Graph Database** using **Cypher queries and Python**. The database models entities and relationships, allowing efficient graph-based data querying and visualization.

---

##  Features
- **Graph-based data representation** using **nodes** and **relationships**.
- **Cypher query execution** for data creation, retrieval, and manipulation.
- **Integration with Python** via the **Neo4j Python driver**.
- **CRUD operations** (Create, Read, Update, Delete) on graph data.
- **Exporting and saving the database** for backups and future use.

---

##  Installation & Setup

### **1️ Install Neo4j**
Download and install **Neo4j Desktop** or **Neo4j Community Edition** from:  
🔗 [Neo4j Official Website](https://neo4j.com/download/)

Start a new **local database instance** in Neo4j Desktop.

---

### **2️ Install Required Python Packages**
pip install neo4j pandas

## Project Structure 
neo4j_project/
│-- config.py           # Stores Neo4j credentials
│-- neo4j_connection.py # Connects to Neo4j
│-- queries.py          # Contains Cypher queries
│-- export_data.py      # Saves data to CSV/JSON
│-- README.md           # Project documentation
