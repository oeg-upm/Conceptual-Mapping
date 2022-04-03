# Conceptual Mapping 

## Purpose and scope

The Conceptual Mapping aims to gather the expressiveness of current mapping languages that describe the transformation of heterogeneous data sources into RDF. This language was born from the assumption that all mapping languages, being used for the basic same purpose of describing data sources in terms of an ontology to create RDF, must have some basic patterns and inherent shared characteristics across all languages. The Conceptual Mapping's model is designed to represent and articulate these core features, which are extracted from two sources: (1) the analysis of current mapping languages, and (2) the limitations of current languages identified by the community. These limitations are referred to as Mapping Challenges, and are proposed by the W3C Knowledge Graph Construction Community Group.

The scope of the vocabulary is to represent features based on declarative languages for describing data sources, their access, mapping rules for RDF transformation and functions. It is out of the scope representing the entire expressivenes of procedural languages based on SPARQL, such as SPARQL-Generate of Facade-X.

## Vocabulary development
### Requirements
The requirements of this vocabulary are specified [here](https://github.com/oeg-upm/Conceptual-Mapping/blob/main/requirements/Requirements%20-%20conceptual%20mapping.xlsx).

### Ontology model

The following diagram shows a general overview of the classes and properties of the Conceptual Mapping vocabulary. This diagram follows the [Chowlk notation](https://chowlk.linkeddata.es/notation.html).

<p align="center"> 
 <img src="https://github.com/anaigmo/Conceptual-Mapping-Ontology/blob/main/OnToology/ontology/conceptual-mapping-ontology.owl/documentation/resources/images/cm_diagram.png?raw=true" alt="schema" width="950"/> 
</p>

### Ontology (OWL)
The encoded ontology in OWL can be found [here](https://github.com/oeg-upm/Conceptual-Mapping/blob/main/ontology/conceptual-mapping.owl). 

## Maintenance
The management of issues and improvements suggested for this vocabulary is done by addressing [issues](https://github.com/oeg-upm/Conceptual-Mapping/issues) in the repository.

## Examples
Some examples of how the language can be used to describe data for RDF transformation is shown in the [examples folder](https://github.com/oeg-upm/Conceptual-Mapping/tree/main/examples).
