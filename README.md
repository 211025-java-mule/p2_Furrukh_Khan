# p2 Furrukh Khan

This project was part of the walkthrough of mulesoft certified developer course. In this project, the mule anypoint studio was used to create an esb to integrate different apis of airlines. REST APIs of American and United Airlines were integrated with the SOAP based API of Delta airlines to easily get resources from different platforms. Then process APIs were made to retrieve data from all 3 System APIs simultaneously or individually depending on the call using scatter gather functions. Error handling was also done. The american airline API was designed from scratch using RAML in anypoint platform. The API was deployed in the platform as well. Dataweave was used to change formats of resources for ease on integration. 

## Technologies Used


```bash
Mulesoft 
MySQl
Maven
REST Connectors
RAML
Dataweave
```

## How to run


- Simply deploy the project in a localhost using anypoint studio.
- Or export the jar to a mule runtime in anypoint platform with all source files and dependencies included. 