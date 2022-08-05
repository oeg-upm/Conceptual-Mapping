# Conceptual Mapping 

## Purpose and scope

The Conceptual Mapping aims to gather the expressiveness of declarative mapping languages that describe the transformation of heterogeneous data sources into RDF. This ontology-based language settles on the assumption that all mapping languages, being used for the basic same purpose of describing data sources in terms of an ontology to create RDF, must have some basic patterns and inherent shared characteristics across all languages. The Conceptual Mapping's model is designed to represent and articulate these core features.

The scope of the vocabulary is to represent features based on declarative languages for describing data sources, their access, mapping rules for RDF transformation and functions. It is out of the scope representing the entire expressivenes of "procedural" languages based on SPARQL, such as SPARQL-Generate of Facade-X.

## Vocabulary development
This ontology is developed following the guidelines provided by the [LOT methodology](https://lot.linkeddata.es/). 

### Requirements
The requirements of the Conceptual Mapping are extracted from two sources: (1) the analysis of current mapping languages, and (2) the limitations of current languages identified by the community. These limitations are referred to as [Mapping Challenges](https://w3id.org/kg-construct/workshop/2021/challenges.html), and are proposed by the [W3C Knowledge Graph Construction Community Group](https://www.w3.org/community/kg-construct/).

The requirements can be found [here](https://github.com/oeg-upm/Conceptual-Mapping/blob/main/requirements/Requirements%20-%20conceptual%20mapping.xlsx), and are specified with an identifier, its provenance and related ontology construct. They can be also visualized [here](https://oeg-upm.github.io/Conceptual-Mapping/requirements/requirements-core.html).

### Ontology model

The following diagram shows a general overview of the classes and properties of the Conceptual Mapping vocabulary. This diagram follows the [Chowlk notation](https://chowlk.linkeddata.es/notation.html). For a complete description of the ontology constructs, see the [documentation](http://vocab.linkeddata.es/def/conceptual-mapping/index-en.html).

<p align="center"> 
 <img src="https://github.com/anaigmo/Conceptual-Mapping-Ontology/blob/main/OnToology/ontology/conceptual-mapping-ontology.owl/documentation/resources/images/cm_diagram.png?raw=true" alt="schema" width="950"/> 
</p>

### Ontology (OWL)
The encoded core ontology in OWL can be found [here](https://github.com/oeg-upm/Conceptual-Mapping/blob/main/ontology/conceptual-mapping.owl). It has associated two SKOS lists, for [Protocols](http://vocab.linkeddata.es/def/conceptual-mapping/kos/protocols-list) and [Functions](http://vocab.linkeddata.es/def/conceptual-mapping/kos/functions-list).

### Shapes
To check that a mapping written with the Conceptual Mapping is correct, shapes in ShEx and SHACL are provided in the [shapes folder](https://github.com/oeg-upm/Conceptual-Mapping/tree/main/shapes). Special thanks to José Emilio Labra Gayo ([@labra](https://github.com/labra)) for providing the ShEx shapes.

### Examples
Some examples of how the language can be used to describe data for RDF transformation is shown in the [examples folder](https://github.com/oeg-upm/Conceptual-Mapping/tree/main/examples).

## Contribute
The management of issues and improvements suggested for this vocabulary is done by addressing [issues](https://github.com/oeg-upm/Conceptual-Mapping/issues) in the repository. If you are interested in collaborate with us in a new version of the language, send us an email or open a new issue or discussion!

## Authors
* Ana Iglesias-Molina - [ana.iglesiasm@upm.es](mailto:ana.iglesiasm@upm.es)
* Andrea Cimmino
* Edna Ruckhaus
* David Chaves-Fraga
* Raúl García-Castro
* Oscar Corcho

Ontology Engineering Group, September 2021 - Present
