# Loading with Python

The following notebook contains the code to illustrate how to load and interact with Neo4j using Python. For the connection to the database we use the Neo4j Python Driver. Documentation can be found here: [Python Driver Neo4j](https://neo4j.com/docs/api/python-driver/current/).

The notebook is making use of the [LOAD CSV](https://neo4j.com/docs/cypher-manual/current/clauses/load-csv/) import. 

The notebook can be divided into three steps: 
1. Read and Transform the data. This can be done in Python libraries as [Pandas](https://pandas.pydata.org/docs/). 
2. Copy the data to the Import directory of Neo4j. You can store CSV files on the database server and then access them by using a file:/// URL. By default, paths are resolved relative to the Neo4j import directory.
3. Load the data using a query ran by the [Python Driver Neo4j](https://neo4j.com/docs/api/python-driver/current/) that is running [LOAD CSV](https://neo4j.com/docs/cypher-manual/current/clauses/load-csv/). 
