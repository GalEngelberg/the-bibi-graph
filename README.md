# the-bibi-graph
The Bibi Graph is a social network analysis of leaders' autobiography via NER,language models, and graph algorithms <br>
Gal Engelberg, January, 2023 <br> <br>

Run the Jupyter Notebook for the full analysis
1. Set up the neo4j environment & create the graph
2. Please assign the following variables: DB_URL for Neo4J bolt connection, USER, PASSWORD, GRAPH_CREATE_CYPHER_PATH for create_graph.cypher path <br>
3. You might need to increase the heap size in Neo4J configuration: <br>
dbms.memory.heap.initial_size=1G <br>
dbms.memory.heap.max_size=16G <br>
4. Requirements: <br>
python packages: pandas, py2neo <br>
Neo4J instance version 4.4.11 Graph Data Science (GDS) Library version 2.1.12
