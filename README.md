# RAG by Ingesting Excel File into a Graph Database

This project demonstrates the integration of a Neo4j graph database with a large language model (LLM) for dynamic query generation and information retrieval. The process begins by ingesting data from an Excel file into the Neo4j graph database using Cypher queries. The core functionality is enhanced by utilizing prompt engineering techniques, specifically few-shot prompting, to allow the LLM to effectively communicate with the graph database.

Using detailed examples, the LLM learns to generate precise Cypher queries based on user inputs, retrieving relevant data from the graph database to answer specific questions. The model is tuned with a few examples of questions and their corresponding Cypher queries, allowing it to understand the structure of the data and generate accurate queries on the fly when new questions are asked.

## Workflow: 
- Data Ingestion: Importing data from Excel into Neo4j using Cypher queries.
- Prompt Engineering: Using few-shot prompting to enable the LLM to generate Cypher queries based on natural language user inputs.
- Graph-based Information Retrieval: Efficiently querying the graph database and retrieving the most relevant information to answer user queries.
- Dynamic Query Generation: The LLM adapts to a variety of user questions by generating custom Cypher queries in real-time.

This repository provides a solid foundation for building intelligent systems that leverage graph databases and natural language interfaces, enabling users to easily extract insights and interact with complex relational data.
