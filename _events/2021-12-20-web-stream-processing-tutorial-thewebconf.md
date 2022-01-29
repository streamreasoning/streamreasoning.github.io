---
layout: page
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: tutorial
title: "Web Stream Processing with RSP4J and OntopStream"
date: "2021-12-20"
---


### Abstract

This tutorial provides a comprehensive introduction to Web stream processing, including some fundamental aspects of stream reasoning. Stream reasoning combines the ideas from stream processing with semantic web technologies, in order to process heterogeneous data streams as presented on the web. In particular, RDF Stream Processing (RSP) is a subfield of stream reasoning that focuses on the timely processing of streaming knowledge graphs in RDF format. Central to the tutorial is the recently published RSP4J library, which uniforms the interaction with existing RSP engines. Furthermore, the tutorial will detail OntopStream, a recent tool for Big Data processing of virtual streaming knowledge graphs, part of the Chimera suite library.  
In practice, the tutorial will include (i) a survey on existing research outcomes from Stream Reasoning / RDF Stream Processing area, i.e., continuous querying, reactive reasoning over highly dynamic graph data; (ii) the introduction of the Stream Processing paradigm, for the processing streaming data, (iii) the introduction of Semantic Web technologies, for the integration of web data, (iv) an overview of how Stream Reasoning and RSP solve the challenges of web stream processing and processing of streaming knowledge graphs, (v) an introduction on how to include data that are not represented as knowledge graphs in web stream processing using virtual knowledge graphs, and (vi) the positioning of existing Web stream processing, e.g. RSP4J and OntopStream, to build and maintain Web Stream Processing applications. The tutorial will include several examples and exercises build around a relevant use case.

## Organizers

##### Emanuele Della Valle

Emanuele Della Valle is an associate professor at Politecnico di Milano. He holds a PhD in Computer Science from the Vrije Universiteit Amsterdam and a Master degree in Computer Science and Engineering from Politecnico di Milano. He is an assistant professor at the Department of Electronics, Information and Bioengineering of Politecnico di Milano. In 20 years of research, his research interests covered Big Data, Stream Processing, Semantic technologies, Data Science, Web Information Retrieval, and Service Oriented Architectures. He started the Stream Reasoning research field positioning it at the intersection between Stream Processing and Artificial Intelligence. His work on Stream Reasoning was applied in analysing Social Media, Mobile Telecom and IoT data streams in collaboration with Telecom Italia, IBM, Siemens, Oracle, Indra, and Statoil. With the experience he gained, he started two companies to create data-centric products and services. He co-authored 22 journal articles, 33 conference papers in major conferences, 3 books, and more than 70 other manuscripts including minor conferences, book chapters, workshop papers and posters. He is a member of the editorial board of Journal of Web Semantics.

##### Pieter bonte

Pieter Bonte is a Post-doctoral researcher at the University of Ghent, IMEC, IDLab. He holds a Ph.D. in Computer Science from the University of Ghent. His research focuses on the use of Semantic Web technologies in the IoT, with a speci?c focus on scalable \\& distributed reasoning, stream reasoning, and RDF Stream Processing. He is particularly interested in increasing the expressivity of reasoning over high volatile streams. He has been active in several interdisciplinary projects, in which he was able to leverage his research in an industrial setting. Furthermore, he detailed his research at many international conferences. Pieter's tutorial activities comprise the related tutorial at DEBS 2021 and IEEE Big Data 2021.

##### Marco Balduini

Marco Balduini is the CEO of Quantia Consulting. He holds a Ph.D. in Computer Science from Politecnico di Milano. His know-how includes Big Data, Data Processing, Semantic technologies, Data integration and Data Science. He was actively involved in several European and international research projects. Between 2010 and 2011, within the FP7 LarKC project, he was one of the main contributors of BOTTARI, an innovative Augmented Reality Mobile App for tourists in Seoul powered by semantic, continuous, and predictive social media analysis co-designed by Politecnico di Milano, SIEMENS and Saltlux (the top-1 Natural Language Processing company in Korea). BOTTARI won the Semantic Web Challenge in 2011. Between 2012 and 2018, he contributed as a researcher to the Stream Reasoning research field and as a practitioner to several H2020 projects funded by EIT Digital related to the analysis of streaming heterogeneous urban data in collaboration with Telecom Italia, Olivetti, F-Secure and Siemens. His focus was on the ingestion, analysis and visualization of heterogeneous stream of spatio-temporal data from Social Media, Mobile Telecommunication and IoT. The visual dashboards, which he co-developed with the Density Design Lab of Politecnico di Milano and Telecom Italia, were exhibited to the general public in 2014 during the Milan Design Week and in 2015 as part of the digital signage of Milano EXPO. In 2019 he took a leading role in the foundation of Quantia Consulting, an innovative company devoted to support enterprises and organizations in their data-driven innovation journey.

##### Matteo Belcao

Matteo Belcao is an IT consultant and researcher at Quantia Consulting. He holds a Master's Degree in Computer Science and Engineering from Politecnico di Milano. His research is focused on Semantic Web, Big Data, and Stream Processing technologies, with a particular interest in Ontology-Based Data Access and Stream Reasoning. Matteo's work includes the development of the Chimera suite, a set of open-source tools for performing Knowledge Graph empowered analyses of Spark-managed Big Data Lakes with python notebooks, which has received the Best Paper Award (Resources Track) recognition at ISWC 2021. His current work includes the extension of Chimera to the streaming paradigm, with the development of OntopStream.

## Program

#### Part 1: What is Stream Reasoning?

- Who Are We
- The Web is Big Data
- What is Stream Processing?
- What is the Semantic Web?
    - RDF
    - SPARQL 1.1
    - Virtual Knowledge Graphs
- What is Stream Reasoning?
    - The vision
    - The technologies
        - RDF Streams
        - RSP-QL
        - RSP4J
        - OntopStreams

#### Part 2: Streaming Knowledge Graphs in practice with RSP4J

- RSP engines and their relation to RSP-QL
  - C-SPARQL
  - CQELS
  - YASPER
- RSP4J internals
- RSP4J components
  - Stream-to-Relation
  - Relation-to-Relation
  - Relation-to-Stream
- Demos and Exercises
  - Writing RSP-QL queries
  - Building a custom RSP engine
  - Creating RSP4J components

#### Part 3: Virtual Streaming Knowledge Graphs in practice using OntopStream

- OntopStream internals
- OntopStream components
- Demos and Exercises
  - Virtual Knowledge Graphs
  - Querying Virtual Knowledge Graphs

- Conclusion
  - 10 years later!
  - What comes next?

#### Support

Join the StreamReasoning Slack #RWChallenge Channel

[https://streamreasoningslack.herokuapp.com/](https://streamreasoningslack.herokuapp.com/)
