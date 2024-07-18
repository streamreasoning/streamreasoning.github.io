---
layout: page
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: tutorial
title: "Streaming Linked Data Tutorial"
date: "2024-07-18"
---

### Abstract

This tutorial provides a comprehensive introduction to Streaming Linked Data, including some fundamental aspects of Stream Processing and Stream Reasoning. Moreover, the tutorial covers all the stages of Streaming Linked Data lifecycle. Central to the tutorial is the recently published book "Streaming Linked Data: From Vision to Practice"~\cite{tommasini2023streaming} and the RDF4J library, 
which uniforms the interaction with existing Streaming Linked Data engines.

In practice, the tutorial will include
   * a survey on existing research outcomes from Stream Reasoning and Streaming Linked Data, i.e., continuous querying, reactive reasoning over highly dynamic graph data; 
  * the introduction of the Streaming Linked Data lifecycle for modelling, publishing, serving, and processing streaming data
  * The positioning of existing Streaming Linked Data engines to build and maintain Streaming Linked Data applications.
The tutorial will include several examples and exercises built around a relevant use case. Moreover, we plan to release the material together with a number of exercises for the attendees.


## Organizers

#### Riccardo Tommasini

He is an associated professor at INSA Lyon, France and Member of the DB Team at LIRIS. Prior to joining INSA Lyon, Riccardo was an assistant professor at the University of Tartu, Estonia. 
Riccardo holds a Ph.D. from the Department of Electronics and Information of the Politecnico di Milano. His thesis, titled ``Velocity on the Web,'' investigates the velocity aspects that concern the Web environment. His research interests span Stream Processing, Knowledge Graphs, Query and Programming Languages.
Riccardo's tutorial activities comprise Big Data Tutorial at Kno.e.sis Center Wright State University, Dayton, Ohio (2015), Stream Reasoning Tutorial at ISWC 2017, ICWE 2018, ESWC 2019, DEBS 2019,  TheWebConf 2019, EDBT 2020 and DEBS 2021. His teaching activities include the courses Interoperability and Semantic Web Technologies and Principles of Programming Languages, Middleware Technologies, and Knowledge Engineering at  Politecnico di Milano. 


#### Pieter Bonte

He is an assistant professor at KU Leuven, Belgium. Before joining KU Leuven, Pieter was a postdoc at Ghent University - imec, Belgium.
He holds a Ph.D. in Computer Science from the Ghent University. His research focuses on the use of Semantic Web technologies in the IoT, with a speciﬁc focus on scalable and distributed reasoning,  stream reasoning, and Streaming Linked Data. He is particularly interested in increasing the expressivity of reasoning over highly volatile streams. He has been active in several interdisciplinary projects in which he was able to leverage his research in an industrial setting. Furthermore, he detailed his research at many international conferences. Pieter's tutorial activities comprise the related tutorial at DEBS 2021, IEEE Big Data 2021, TheWebConf 2022.
His is teaching the courses Declarative Languages, Operating Systems and Computer Architecture at KU Leuven.

## Program

1. **Streaming Linked Data: An Introduction** [15m] [*slides*](https://drive.google.com/open?id=1enWXdrqIJHP3SAvqAqu1y-x6N8SZpYt-)
    1. The Stream Reasoning research question
    2. Taming data variety and velocity on the web
    3. Use-cases & applications
2. **Background on Streaming Data** [45m]
    1. Stream Processing 101 [*slides*](https://drive.google.com/open?id=1zphiaJFxirmrPcxDPXzZNCRyyk4-6Pjy)
        1. Paradigm shift to continuous semantics [*slides*](https://drive.google.com/open?id=1bN0yZlFACadI8AtLJzrSUPv4_si61085)
        2. Stream processing languages and architectures [*slides*](https://drive.google.com/open?id=1gx6vDDfb2P1LaSQA43Rjwgwjzp82hgAG)
        3. Streaming Machine Learning
3. **The Streaming Linked Data Lifecycle** [cf Figure 1 (1-5)] [40m]
    1. Naming and modelling: an introduction to ontology modelling for SLD
    2. Shaping and annotating web streams (briefly)
    3. Exercise 1: Modeling web stream processing services with VoCaLS
    4. Describing and serving streams on the web
        1. Streams on the Web: publication challenges
        2. A vocabularies and tools for publishing web streams
        3. Demo 1: Converting Wikimedia Changes with [*RSP4J*](https://github.com/streamreasoning/RSP4J)
4. **Querying and processing Linked Streams** [cf Figure 1 (6)] [85m] [*slides*](https://drive.google.com/open?id=1gx6vDDfb2P1LaSQA43Rjwgwjzp82hgAG)
    1. RSP-QL and RSP Dialects
    2. Demo 2: representative RSP dialects and engines: [*C-SPARQL*](https://github.com/streamreasoning/CSPARQL-engine)
    3. Exercise 2: Building an SLD Application with [*RSP4J*](https://github.com/streamreasoning/RSP4J)
    4. Exercise 3: Fast Prototyping with [*RSP4J*](https://github.com/streamreasoning/RSP4J)
5. **Wrap-up and discussion** [15m]
    1. On-going research trends, real-world deployments
    2. Open problems and future directions


#### Support

Join the StreamReasoning Slack #ISWC2024 Channel

[https://streamreasoningslack.herokuapp.com/](https://streamreasoningslack.herokuapp.com/)