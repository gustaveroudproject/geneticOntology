# geneticOntology

This is the development repo of GENO, an OWL2 ontology for the field of genetic criticism and genetic editing.

For a human-readable version of the latest version of GENO, click [here](https://w3id.org/lode/owlapi/https://raw.githubusercontent.com/gustaveroudproject/geneticOntology/master/onto/geneticOntology_0-2.ttl) (powered by [LODE](http://www.essepuntato.it/lode)).


### Repo structure

This repo contains

- onto. A folder with the ontology (check latest version)
- data. A folder where are collected data samples for testing purpose
- docs. A folder containing documentation about the ontology, including the motivating scenario and some competency questions with related sparql queries

---

### Attention!

**GENO is under development and the URI are not resolvable yet!**

If you are interested in the development, want to give your feedback and/or contribution, have a look at .... and get in touch! Or open an issue here!

---

### Test (e.g. with GraphDB)

1. download or clone the repo
2. create a repository in the DB
2. import from rdf:
	- select the ontology (.ttl), upload, when asked insert as Base URI and as Context http://example.org/geneticOntology/onto
	- select the data sample (.ttl), upload, when asked insert as Base URI and as Context http://example.org/geneticOntology/data
	(This way you can delete all the data, without touching at the ontology)
3. Now you can explore and query the data. Examples of sparql queries are available [here](docs/competencyQuestions_sparqlQueries.md).



