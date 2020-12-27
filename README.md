# PROJECT: Open Information System

### Group 9

Contains the neccesary files to startup our SPARQL endpoint:

- **data.db**: Database containing the induviduals
- **Conference.owl**: The ontology
- **Conference-mappings**: Turtle file containing the mappings
- **configuration.properties**: Properties file


#### Deploying the endpoint:
1.	Clone the GitHub repository to get the necessary files:
https://github.com/killerz224/conference-ontology-endpoint.git

2.	Open the terminal and navigate to the cloned directory

3.	Run the following command to start up the SPARQL endpoint:
ontop endpoint -t Conference.owl -m conference-mapping.ttl -p configuration.properties

4.	The endpoint is available in the following link:
http://localhost:8080/
