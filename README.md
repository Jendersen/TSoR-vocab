# TSoR-vocab
This document is a vocabulary for describing compound measures, i.e. measures with several metrics or items organized along several dimensions. The description of such a measure is based on a Tree-Structure of Requirement (TSoR): a set of requirements structured hierarchically with analysis elements. A TSoR represents the main measure. Several pieces of information can be added to explicitly indicate how the overall score of the measure should be calculated based on the hierarchy, the relative importance of the nodes of the hierarchy, and an aggregation function. The measure can be completely and unambiguously described from organization to requirements to implementation.

The vocabulary is defined as follows.
[![Vocabulary illustration](illustration.svg)](illustration.svg)

To see the human readable version of this vocabulary, [click here](https://w3id.org/lode/owlapi/https://raw.githubusercontent.com/Jendersen/TSoR-vocab/main/cmd_vocab.xml).
The vocabulary is available in two formats: [RDF/XML](cmd_vocab.xml) or [Turtle](cmd_vocab.ttl).

## To go further
[SHACL shapes](cmd_shacl.ttl) are defined to ensure that the TSoR defined with the vocabulary is well-formed, i.e. it actually forms a tree structure. It also checks that the TSoR satisfies some recommendations.
The file [example.ttl](example.ttl) provides an example of a TSoR defined with the given vocabulary. It represents a measure of accountability, as described [here](https://github.com/Jendersen/KG_accountability/tree/main).
