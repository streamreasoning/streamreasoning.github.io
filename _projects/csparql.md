---
layout: page
title: C-SPARQL Engine
description: a project with no image
img:
importance: 4
category: software
---


# Continuous SPARQL (C-SPARQL)

C-SPARQL is a new language for continuous queries over streams of RDF data. C-SPARQL queries consider windows, i.e., the most recent triples of such streams, observed while data is continuously flowing. Supporting streams in RDF format guarantees interoperability and opens up important applications, in which reasoners can deal with knowledge evolving over time. Examples of such application domains include real-time reasoning over sensors, urban computing, and social semantic data. Hereafter you can download a "ready to go pack" to start using C-SPARQL yourself.

## Download

- [CSPARQL-ReadyToGoPack-0.9.6](/larkc/csparql/CSPARQL-ReadyToGoPack-0.9.6.zip) released on 23.11.2015

Older versions:

- [CSPARQL-ReadyToGoPack-0.9](/larkc/csparql/CSPARQL-ReadyToGoPack-0.9.zip) released on 5.5.2013
- [CSPARQL-ReadyToGoPack-0.8](/larkc/csparql/CSPARQL-ReadyToGoPack-0.8.zip) released on 30.3.2013
- [CSPARQL-ReadyToGoPack-0.7.4](/larkc/csparql/CSPARQL-ReadyToGoPack-0.7.4.zip) released on 9.5.2012
- [CSPARQL-ReadyToGoPack-0.7.3](/larkc/csparql/CSPARQL-ReadyToGoPack-0.7.3.zip) released on 18.10.2011
- [CSPARQL-ReadyToGoPack-0.7.1](/larkc/csparql/CSPARQL-ReadyToGoPack-0.7.1.zip) released on 9.6.2011
- [CSPARQL-ReadyToGoPack-0.7](/larkc/csparql/CSPARQL-ReadyToGoPack-0.7.zip) released on 30.5.2011

## Prerequisite

C-SPARQL Engine is written in Java 1.6. The "ready to go pack" is an Eclipse project

## Start Using

1. Download the zip
2. Unzip in your Eclipse workspace
3. Import the project in your Eclipse
4. Try to understand the HelloWorldCSPARQL.java class

## Known Limitation

The following features are not supported in this package:

- FROM NAMED clauses
- COMPUTE EVERY clause
- timestamp function on named graphs
- reasoning support (i.e., only simple RDF entailment is supported)

## Known Bugs

Open bugs in version 0.9:

- anonymous nodes are not correctly handled
- tuple-based windows are not correctly handled

The following bugs where reported on version 0.7, 0.7.1, 0.7.3 and were fixed in version 0.7.4:

- type of typed literals disappear when processed by C-SPARQL **FIXED**
- some IRIs used to identify streams result in a parse error **FIXED**
- queries with multiple FROM STREAM clauses rise an exception **FIXED**
- missing classes exceptions **FIXED**

## Getting Support

For more information on C-SPARQL language see the Stream Reasoning for Linked Data tutorial that we gave at [ESWC 2011](events/sr4ld2011) and [SemTech 2011](http://www.abdn.ac.uk/%7Ecsc280/tutorial/semtech2011/) or contact emanuele.dellavalle-at-polimi.it for more.

## Source Code

The source code of the C-SPARQL Engine and of the ready to go pack are available on github:

- [https://github.com/streamreasoning/CSPARQL-engine](https://github.com/streamreasoning/CSPARQL-engine)
- [https://github.com/streamreasoning/CSPARQL-ReadyToGoPack](https://github.com/streamreasoning/CSPARQL-ReadyToGoPack)

## Licence

The C-SPARQL Engine and the "ready to go pack" are distributed under [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html) in the hope that it will be useful, but without any warranty; without even the implied warranty of merchantability or fitness for a particular purpose. Permissions beyond the scope of this license may be available writing to [emanuele.dellavalle@polimi.it](mailto:emanuele.dellavalle@polimi.it).

## Acknowledgements

This work was partially supported by the European projects [LarKC](http://www.larkc.eu/) (FP7-215535), and [ModaClouds](http://www.modaclouds.eu/) (FP7-ICT-2011-8-318484), and by the [IBM faculty ward 2013](http://www.research.ibm.com/university/pdfs/2013_faculty_award_recipients.pdf) grated to prof. Emanuele Della Valle
