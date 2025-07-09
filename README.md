# A "cyber_ontology" to describe the entire cyber perimeter

## Description
This project consists in **developping an ontology of the cyber scope**.


The ambition is to create an ontology that is:
- **intelligible** to ordinary people, **agnostic** of specific technologies and cultures, and **compatible** with important references (international standards, reference texts, knowledge bases, data models, other existing ontologies, etc.) ;
- **useful for specifying new services**: data models, expected form of results from data transformation tools (ETL), etc.;
- a **dictionary and catalog of consumable data**;
- in **continuous improvement**, through the progressive integration of new use cases and ongoing quality adjustments.

## Author
Matthieu GRALL, as part of the DATA VISIONS collective.

## License
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.en).

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