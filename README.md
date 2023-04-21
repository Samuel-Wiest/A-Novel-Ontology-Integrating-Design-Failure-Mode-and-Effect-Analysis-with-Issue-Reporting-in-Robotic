# A Novel Ontology Integrating Design Failure Mode and Effect Analysis with Issue Reporting in Robotics

## Abstract

Ensuring reliability is an important aspect of robotics development, requiring reliability analysis. Reliability analysis is performed theoretically during design using design failure modes and effects analysis (DFMEA) and practically during testing with the creation of issue reports. The resulting documentation, in the form of spreadsheets and text files, contains similar information but requires manual knowledge extraction and inferencing. This paper proposes an ontology that automates these processes by serving as a framework for containing reliability and failure knowledge derived from DFMEA and testing. The new ontology is based on existing DFMEA ontologies and the IEEE standard robotics ontologies, CORA and CORAX. Development followed the Methontology and OntoClean methodologies. The ontology was first formalized using Prot\'eg\'e and the Web Ontology Language (OWL). The ontology was then imported into Neo4j where Cypher queries could be used to fully replace the existing failure documentation with a searchable, inferential graph database. As a case study, DFMEA worksheets and issue reports from the development of a commercial robot were then instantiated into the OWL ontology and the graph database.

## Ontology
The ontology is contained in an RDF file. This file also includes the translations of SUMO and CORA into OWL, available here: https://github.com/srfiorini/IEEE1872-owl. Please refer to the respective copyrights and bibliography there. 

## Methontology documents
All of the documents created during the Methontology process are located in the Methontology folder. The names correspond to those found in Fig. 6 of the paper "Methontology coneptual documents", with the exception of the integration document.

## OntoClean result
OntoClean Diagram.png contains the assignments of properties to each class in the ontology. This is the final result of applying OntoClean. 
