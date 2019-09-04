# geneticOntology

This is the development repo of OGEN, an OWL-based top-level model the field of genetic criticism and genetic editing.


### Repo structure

The repo contains

- onto. A folder with the ontology (check latest version) and materials for the ontology development. These include the motivating scenario and competency questions with related sparql queries
- data. A folder where are collected data samples for testing purpose.
- images. A folder containing images, mainly used for documenting the ontology.

---

### Attention!

**OGEN is in development and the URI are not resolvable yet!**

If you are interested in the development, want to give your feedback and/or contribution, have a look at .... and get in touch! Or open an issue here!

---

### Test with GraphDB

1. create a repository
2. import from rdf:
	- select the ontology (file .ttl), upload, when asked insert as Base URI and as Context http://example.org/geneticOntology/onto
	- select the data sample, upload, when asked insert as Base URI and as Context http://example.org/geneticOntology/data
	(This way you can delete all the data, without touching at the ontology)
3. Now you can explore and query the data. Examples of sparql queries are available [here](onto/ontoDevelopment/competencyQuestions_sparqlQueries.md).



