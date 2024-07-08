# General Formal Ontology (GFO)

[![Test ontology](https://github.com/Onto-Med/GFO/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/Onto-Med/GFO/actions/workflows/test.yml)
[![DOI](https://zenodo.org/badge/220933953.svg)](https://zenodo.org/badge/latestdoi/220933953)

## Introduction
The General Formal Ontology is a [top-level ontology](http://en.wikipedia.org/wiki/Upper_ontology_%28computer_science%29) for conceptual modeling, which is being constantly further developed by Onto-Med. It includes elaborations of categories like objects, processes, time and space, properties, relations, roles, functions, facts, and situations. Moreover, we are working on an integration with the notion of *levels of reality* in order to more appropriately capture entities in the material, mental, and social areas. Outstanding features of GFO are:

* coherent integration of objects and processes (based on a novel category of *persistants*)
* time and space entities as entities sui generis, and the relation of *coincidence*
* a category of *situoids*, comprehensible wholes of the most independent character
* elaborate accounts of functions and roles
* openness regarding philosophical positions such as realism, conceptualism, or nominalism by the provision of different kinds of categories as universals, concepts, or symbolic structures

## How to Use
The entire GFO ontology can be imported via IRI https://w3id.org/gfo. GFO is divided into modules, which are stored in separate OWL files under [modules/](modules/). Modules of interest can be imported into your ontology via their IRI (e.g., https://w3id.org/gfo/base).

**GFO-light** is a simplified view of the entire GFO. It does not build on single modules but combines all basic concepts and simplified axioms of the GFO. It is primarily intended to found domain or application ontologies and can be imported via IRI https://w3id.org/gfo/light.

## Brief History
Work on GFO has started in 1999 in the context of the GOL project (General Ontological Language). Meanwhile, several directions of research have been recognized and divided the initial project, such that GFO is now one component of a larger framework. Work on GFO remains in progress, because the development of top-level ontologies is a long-term research effort.

## Axiomatizations and Implementations
The "native" formalization language for GFO is [first-order logic (FOL)](https://en.wikipedia.org/wiki/First-order_logic). Partial axiomatizations of GFO in FOL exist in report working drafts, but are not yet available to the public.

### Release Strategy
[modules/gfo-base.owl](modules/gfo-base.owl) forms the core module of GFO. We are going to continually provide further modules/extensions, dedicated to several of our research domains, like time, space, processes, etc. There may be parallel extensions for these domains, and not all extensions will be consistent with each other. All module files are provided with their own namespaces (e.g., https://w3id.org/gfo/time) and can be used separately. A selection of those modules will be unified in the next version of [gfo.owl](gfo.owl) (under the namespace https://w3id.org/gfo).

All versions of GFO and it's modules are available via `owl:versionIRI`. e.g.: https://w3id.org/gfo/release/2024-07-05

### Release History
Work on the OWL version of GFO started in early 2006 in the context of the [GFO-Bio](http://www.onto-med.de/ontologies/gfo-bio/index.jsp) project, resulting in the 1.0 release of [gfo.owl](gfo.owl).

## Documentation and Publications
### Onto-Med Report Series on GFO
The major descriptive source for GFO is a series of Onto-Med Reports. As this work progresses continuously and in irregular intervals, draft versions are also provided. These may exhibit some technical deficiencies (e.g., few missing references, "empty sections" indicating areas under research). Nevertheless, they best reflect the continuing development of GFO during report releases.

The series comprises reports with respect to three components: Part I (Basic Principles) sets forth the logical and philosophical basic assumptions and methods, and presents a conceptual account of the General Formal Ontology (GFO) in some detail. Part II (Axiomatics and Ontology Languages) presents a full axiomatization of GFO, as well as a library of ontology languages, and several tools for meta-logical analyses of formal axioms. In Part III (Applications) several applications of GFO are collected and presented. So far, only Part I is available, whereas Part II and III are under development.

The following is the general form of citation for Part I, where the corresponding version and, for releases, the number in the series should be added.

> **Herre H, Heller B, Burek P, Hoehndorf R, Loebe F, Michalek H**. General Formal Ontology (GFO): A Foundational Ontology Integrating Objects and Processes. Part I: Basic Principles. Research Group Ontologies in Medicine (Onto-Med), University of Leipzig.

#### Latest Revisions
* Latest intermediate revision: Version 1.0.1, Draft, 14.02.2007 [PDF](https://www.onto-med.de/sites/www.onto-med.de/files/files/uploads/Publications/2007/gfo-part1-v1-0-1.pdf) (changes: primarily sect. 2.3, 3.5, 3.6, 8 and 16)
* Latest released revision: Version 1.0, Onto-Med Report Nr. 8, 01.07.2006 [PDF](https://www.onto-med.de/sites/www.onto-med.de/files/files/uploads/Publications/2006/om-report-no8.pdf)

### Other Publications Exclusively Presenting GFO
> **Loebe F, Burek P, Herre H**. GFO: The General Formal Ontology. AO 2022;17:71–106. https://doi.org/10.3233/AO-220264.

> **Burek P, Loebe F, Herre H**. Towards GFO 2.0: Architecture, Modules and Applications. In: Brodaric B, Neuhaus F, editors. Frontiers in Artificial Intelligence and Applications, IOS Press; 2020. https://doi.org/10.3233/FAIA200658.

> **Herre H**. General Formal Ontology (GFO): A Foundational Ontology for Conceptual Modelling. In: Poli R, Healy M, Kameas A, editors. Theory and Applications of Ontology: Computer Applications, Dordrecht: Springer Netherlands; 2010, p. 297–345. https://doi.org/10.1007/978-90-481-8847-5_14.

> **Heller B, Herre H**. Ontological Categories in GOL. Axiomathes 2004;14:57–76. https://doi.org/10.1023/B:AXIO.0000006788.44025.49.

> **Heller B, Herre H**. Formal Ontology and Principles of GOL. Onto-Med Report Nr. 1. Research Group Ontologies in Medicine (Onto-Med), University of Leipzig.

### Further Documentation
Apart from the GFO reports, we have not yet completed the work on more introductory or tutorial material. This is going to happen in the nearer future. Currently, the easiest way to access the basic categories of GFO is to view the file [gfo-light.owl] in an ontology editor (e.g. [Protégé](https://protege.stanford.edu)). In particular, that file provides short descriptions for each category.
