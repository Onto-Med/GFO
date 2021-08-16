# General Formal Ontology (GFO)

[![DOI](https://zenodo.org/badge/220933953.svg)](https://zenodo.org/badge/latestdoi/220933953)

## Introduction
The General Formal Ontology is a [top-level ontology](http://en.wikipedia.org/wiki/Upper_ontology_%28computer_science%29) for conceptual modeling, which is being constantly further developed by Onto-Med. It includes elaborations of categories like objects, processes, time and space, properties, relations, roles, functions, facts, and situations. Moreover, we are working on an integration with the notion of *levels of reality* in order to more appropriately capture entities in the material, mental, and social areas. Outstanding features of GFO are:

* coherent integration of objects and processes (based on a novel category of *persistants*)
* time and space entities as entities sui generis, and the relation of *coincidence*
* a category of *situoids*, comprehensible wholes of the most independent character
* elaborate accounts of functions and roles
* openness regarding philosophical positions such as realism, conceptualism, or nominalism by the provision of different kinds of categories as universals, concepts, or symbolic structures

## Brief History
Work on GFO has started in 1999 in the context of the GOL project (General Ontological Language). Meanwhile, several directions of research have been recognized and divided the initial project, such that GFO is now one component of a larger framework. Work on GFO remains in progress, because the development of top-level ontologies is a long-term research effort.

## Axiomatizations and Implementations
The "native" formalization language for GFO is [first-order logic (FOL)](https://en.wikipedia.org/wiki/First-order_logic). Partial axiomatizations of GFO in FOL exist in report working drafts, but are not yet available to the public.

### OWL
There is an [OWL](http://en.wikipedia.org/wiki/Web_Ontology_Language) version of GFO, which currently comprises a stable core called *gfo-basic.owl* and a more extensive version called *gfo.owl*.

### Release Strategy
*gfo-basic.owl* forms the core of the coming releases. We are going to continually provide several extensions to *gfo-basic.owl*, dedicated to several of our research domains, like time, space, processes, etc. There may be parallel extensions for these domains, and not all extensions will be consistent with each other. All files are provided with the GFO namespace, http://www.onto-med.de/ontologies/gfo as their base namespace. All extensions should import *gfo-basic.owl*. Eventually, a selection of those extensions will be unified in the next version of *gfo.owl*. Note that the latter has not yet been adapted to *gfo-basic.owl*.

### Release History
Work on the OWL version of GFO started in early 2006 in the context of the [GFO-Bio](http://www.onto-med.de/ontologies/gfo-bio/index.jsp) project, resulting in the 1.0 release of *gfo.owl*. The renewed release strategy in 2008 lead to *gfo-basic.owl*, a corrected and slightly simplified version.

## Documentation and Publications
### Onto-Med Report Series on GFO
The major descriptive source for GFO is a series of Onto-Med Reports. As this work progresses continuously and in irregular intervals, draft versions are also provided. These may exhibit some technical deficiencies (e.g., few missing references, "empty sections" indicating areas under research). Nevertheless, they best reflect the continuing development of GFO during report releases.

The series comprises reports with respect to three components: Part I (Basic Principles) sets forth the logical and philosophical basic assumptions and methods, and presents a conceptual account of the General Formal Ontology (GFO) in some detail. Part II (Axiomatics and Ontology Languages) presents a full axiomatization of GFO, as well as a library of ontology languages, and several tools for meta-logical analyses of formal axioms. In Part III (Applications) several applications of GFO are collected and presented. So far, only Part I is available, whereas Part II and III are under development.

The following is the general form of citation for Part I, where the corresponding version and, for releases, the number in the series should be added.

> **Herre, H.; Heller, B.; Burek, P.; Hoehndorf, R.; Loebe, F. & Michalek, H.**. General Formal Ontology (GFO): A Foundational Ontology Integrating Objects and Processes. Part I: Basic Principles. Research Group Ontologies in Medicine (Onto-Med), University of Leipzig.

#### Latest Revisions
* Latest intermediate revision: Version 1.0.1, Draft, 14.02.2007 [PDF](http://www.onto-med.de/Archiv/ontomed2002/en/theories/gfo/part1-drafts/gfo-part1-v1-0-1.pdf) (changes: primarily sect. 2.3, 3.5, 3.6, 8 and 16)
* Latest released revision: Version 1.0, Onto-Med Report Nr. 8, 01.07.2006 [PDF](http://www.onto-med.de/Archiv/ontomed2002/en/publications/scientific-reports/om-report-no8.pdf) [HTML](http://www.onto-med.de/Archiv/ontomed2002/en/theories/gfo/part1/index.html)

### Other Publications Exclusively Presenting GFO
> **Herre, H. 2010**. General Formal Ontology (GFO): A Foundational Ontology for Conceptual Modelling. *Theory and Applications of Ontology: Computer Applications*. Springer, Dordrecht. https://doi.org/10.1007/978-90-481-8847-5_14

> **Heller, B. & Herre, H. 2004**. Ontological Categories in GOL. *Axiomathes* 14(1):57-76 Kluwer Academic Publishers. https://doi.org/10.1023/B:AXIO.0000006788.44025.49

> **Heller, B. & Herre, H. 2003**. Formal Ontology and Principles of GOL. *Onto-Med Report Nr. 1*. Research Group Ontologies in Medicine (Onto-Med), University of Leipzig. http://www.onto-med.de/publications/2003/heller-b-2003-a.pdf

### Further Documentation
Apart from the GFO reports, we have not yet completed the work on more introductory or tutorial material. This is going to happen in the nearer future. Currently, the easiest way to access the basic categories of GFO is to view the file *gfo-basic.owl* in an ontology editor (e.g. [OwlSight](https://www.w3.org/2001/sw/wiki/OWLSight) or [Protégé](https://protege.stanford.edu)). In particular, that file provides short descriptions for each category.
