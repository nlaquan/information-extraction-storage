# Introduction

This project develops a system to store and query entities and relationships extracted from news articles.
The system can work smoothly with billions of entities and relationships, based on [Neo4j graph database](https://neo4j.com/).
The Neo4j data model (i.e., Neo4J node, label, relationships, properties) are optimized.

Project Resources (3 projects and documents to adminitrate the system):

**1. neo4j administration** Our main instructions to administrate the system, including (i) Neo4j installation, (ii) data backup, (iii) data restore. Neo4j can either be installed in Mac, Win, and Linux or run in docker. To scale the storage system, we also provide detailed guideline on Neo4j [Causal Cluster](https://neo4j.com/docs/operations-manual/current/clustering/) deployment.

**2. storage-api** A Node.js project that provides developers with APIs (i.e., Restful services) to interact with the storage system. There have been ** services that allows developers to store and query data on entities and relationships

**3. storage-api-docs** A ReactJS Project provides web-based documents to use the services provided in the **storage-api** project. Developers and/or anybody can easily test the services visually in a web interface.

**4. storage-data-simulation** A Node.js Project to generate simulation data. Data is generated in CSV files, based on our desired configuration of entities and relationships. Those CSV files can be imported into Neo4J database. This method allows us to generate a huge amount of data in a small amount of time. The data can then be used in performance testings.

# How to use the projects
Step 1: Read our **neo4j administration** instructions to install Neo4j

Step 2: Install **storage-api** to establish services to store and query entities and relationships extracted from news articles

Step 3: Install **storage-api-docs** to learn and practice the services

Step 4: Use **storage-data-simulation** to generage a huge amount of data for performance testing

# Technologies
[Neo4j](https://neo4j.com/)<br>
[Node.js](https://nodejs.org/en/)<br>
[ReactJS](https://reactjs.org/)<br>
