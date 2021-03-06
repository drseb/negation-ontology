
<!-- [![Build Status](https://travis-ci.org/drseb/negation-ontology.svg?branch=master)](https://travis-ci.org/drseb/negation-ontology) -->

<!-- [![DOI](https://zenodo.org/badge/13996/drseb/negation-ontology.svg)](https://zenodo.org/badge/latestdoi/13996/drseb/negation-ontology) -->


# negation-ontology

This ontology will be used to represent negated associations between any biomedical items (knockout-mice, diseases, patients, morpholinos, ...) and phenotype ontology classes.

Associations between a gene or a disease with terms from phenotype ontologies or gene ontologies are sometimes negated. This means the intended meaning is that this association is actually NOT seen. 
Currently we only used the keyword “NOT”. But as discussed on previous calls, there are different semantics of this “NOT”. This ontology should be a first pass at representing this for annotation files in different species.

## Versions

### Stable release versions

The latest version of the ontology can always be found at:

http://purl.obolibrary.org/obo/not.owl

(note this will not show up until the request has been approved by obofoundry.org)

### Editors' version

Editors of this ontology should use the edit version, [src/ontology/not-edit.owl](src/ontology/not-edit.owl)

## Contact

Please use this GitHub repository's [Issue tracker](https://github.com/drseb/negation-ontology/issues) to request new terms/classes or report errors or specific concerns related to the ontology.

## Acknowledgements

This ontology repository was created using the [ontology starter kit](https://github.com/INCATools/ontology-starter-kit)
