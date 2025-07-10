# An ontology to describe the entire cyber perimeter

## Description
This project consists in **developping an ontology of the cyber scope**.


The ambition is to create an ontology that is:
- **intelligible** to ordinary people, **agnostic** of specific technologies and cultures, and **compatible** with important references (international standards, reference texts, knowledge bases, data models, other existing ontologies, etc.) ;
- **useful for specifying new services**: data models, expected form of results from data transformation tools (ETL), etc.;
- a **dictionary and catalog of consumable data**;
- in **continuous improvement**, through the progressive integration of new use cases and ongoing quality adjustments.

## Versions
| <center>**Version**</center> | <center>**Modifications**</center> | <center>**Author**</center> | 
| --- | --- | --- | 
| 03/12/2024 (v0.1) | Create the ontology and add a simple information systems management usecase | Matthieu GRALL | 
| 07/12/2024 (v0.2) | Enrich the information systems management usecase | Matthieu GRALL | 
| 17/04/2025 (v0.3) | Develop classes and relations necessary to the main other cyber usecases, in a structure based on the cyberspace layers | Matthieu GRALL | 
| 09/07/2025 (v0.4) | Improve the existing classes and relations and develop the proprties | Matthieu GRALL | 
| 10/07/2025 (v0.5) | Improve the existing objects and add those necessary to make the link between usecases (as subclasses of data processings) and classes that are processed by them | Matthieu GRALL | 

## Further information
1. The .owl ontology uses the RDF/XML Syntax.

2. It is composed by:
- **classes**:
	- unique identifier (_IRI_);
	- labels in French and English (_rdfs:label_);
	- definitions in French and English (_rdfs:isDefinedBy_);
	- version information in French (_owl:versionInfo_);
- **relations** (_Object properties_):
	- IRI;
	- labels in French and English (_rdfs:label_);
	- version information in French (_owl:versionInfo_);
	- domains;
	- ranges;
- **properties** (_Data properties_):
	- IRI;
	- labels in French and English (_rdfs:label_);
	- naming rules in French and English (_rdfs:comments_);
	- version information in French (_owl:versionInfo_);
	- domains;
	- ranges.