---
layout: page
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: tutorial
title: "Engineering a Web Stream Processing Application"
date: "2018-06-07"
---

### Abstract

The goal of the tutorial is to outline how to develop and deploy a stream processing application in a web environment in a reproducible way. To this extent, we intend to (1) survey existing research outcomes from the Stream Reasoning /RDF Stream Processing that arise in querying and reasoning on a variety of highly dynamic data, (2) introduce stream reasoning techniques as powerful tools to use when addressing a data-centric problem characterised both by variety and velocity (such as those typically found on the modern Web), (3) present a relevant Web-centric use-case that requires to address simultaneously data velocity and variety, and (4) guide the participants through the development of a Web stream processing application.

### Introduction

More and more streams of information are becoming available on the Web. A variety of sources give origin to data streams including social networks, mobile phones, smart homes, healthcare devices and other modern infrastructures. A significant portion of these data belongs to the Web-of-Services and to the Web-of-Things ecosystems where data is published and consumed using Web standards and technologies. From new opportunities arise new challenges. A common problem in the scenarios illustrated above is how to integrate such data and how to enable the creation of new knowledge. Reasoning techniques are a possible solution. However, while reasoners scale up in the classical, static domain of ontological knowledge, reasoning upon rapidly changing information has received attention only very recently. The combination of reasoning techniques with data streams gives rise to Stream Reasoning. i.e., reasoning on highly dynamic flows of information. This is a high impact research area that has already started to produce.

**Learning Goals**: The contents of this tutorial can be relevant for ICWE attendees as it focuses on the engineering aspects of developing and deploying applications that use streaming data to create new knowledge. This tutorial aims at introducing different existing approaches for querying and reasoning over data streams and providing guidelines to develop and deploy Stream Reasoning applications. In particular, the tutorial offers to the audience: (i) an overview of the use cases and the scenarios where Stream Reasoning can be used (with the advantages it brings); (ii) an overview of the current state of the art in this emerging area, with techniques and tools developed by several research groups (including but not limited to presenters ones); (iii) a focus on a subset of the technologies to perform complex reasoning over dynamic data.

**Related Events**: The tutorial follows from the Stream Reasoning for Linked Data (SR4LD) tutorial series, successfully held at ESWC 2011, SemTech 2011, ISWC 2013, ISWC 2014, ISWC 2015; the RDF Stream Processing (RSP) tutorial series at ESWC 2014 and ISWC 2016; the Stream Reasoning: Managing Velocity and Variety in Big Data tutorial at DEBS 2016; and the tutorial on How to Build a Stream Reasoning Application co-located with ISWC 20171 . Technologies are now mature and reliable enough to make a step further and build a tutorial with a stronger focus on hands-on sessions. Therefore, this tutorial not only will survey existing research outcomes and introduce existing tools, but it will also present a relevant Web-centric use-case and guide the participants through application development of a Web stream processing application.

**Audience**: The event targets researchers and practitioners interested in approaching the topic of web stream processing (both querying and reasoning) and who want to understand the current state of the art as well as the future directions. For this reason, the expected background knowledge is on basic concepts of RDF and SPARQL. The technologies and topics on this tutorial are relevant for people from IoT and sensor communities, as well as social media, pervasive health, oil industry, etc., who produce massive amounts of streaming data.

### Course Program Materials

1. Introduction to Web Stream Processing \[[ppt](https://drive.google.com/open?id=1bN0yZlFACadI8AtLJzrSUPv4_si61085)\]
2. Crash Course on Semantic Web \[[ppt](https://drive.google.com/open?id=1rdBsDPimgfVtJPLOYClPGmZKs3l-597a)\]
3. WASP: Web Stream Processing Application \[[ppt](https://drive.google.com/open?id=1enWXdrqIJHP3SAvqAqu1y-x6N8SZpYt-)\] \[[vocals paper](https://drive.google.com/open?id=1DIZv8DFyD8mnrJi4oYcxoUn8tniEVmr0)\] \[[vocals](https://github.com/ysedira/vocals/wiki)\]
4. RDF Stream Processing \[[ppt](https://drive.google.com/open?id=1gx6vDDfb2P1LaSQA43Rjwgwjzp82hgAG)\]
5. Demo & Conclusion \[[ppt](https://drive.google.com/open?id=1aD0Z9xZ6oePzdg-sxBuukcIok7wkL5Aq)\] \[[notebooks](https://github.com/riccardotommasini/rsp-kernel/tree/dev/icwe)\]

### Course Extras

- [BOTTARI](https://www.sciencedirect.com/science/article/pii/S157082681200073X)
- C-SPARQL \[[paper](https://scholar.google.it/scholar?hl=it&as_sdt=0%2C5&q=c-sparql&btnG=)\] \[[code](https://github.com/streamreasoning/CSPARQL-engine)\]
- YASPER \[[code](https://github.com/streamreasoning/yasper/)\]

### Organizers

**![](images/emanuele.jpg)Emanuele Della Valle** is an Assistant Professor of Software Project Management at the Department of Electronics and Information of the Politecnico di Milano. He tries to perform research that is justified and guided by business needs. His major interest is in translating research results into business opportunities. In more than a decade of research, his research interests covered Semantic Web, Web Services, Service Oriented Architectures, Search Engines and, more recently on Stream Management Systems and Rank-aware Databases. His education activities include lecturing: Software Project Management at Politecnico di Milano; Knowledge Engineering at Universita dell Insubria; the RDF stream Processing tutorial at ESWC 2014, the Stream Reasoning for Linked Data tutorial series at SemTech 2011, ESWC 2011, ISWC 2013, ISWC 2014, ISWC 2015 the LarKC Early Adopters Tutorial Series at ISWC 2009, and ESWC 2010; a tutorial about Realizing Semantic Web Applications at BIS 2008, ISWC 2008, and ICWE 2010; and several industrial short courses for CEFRIEL centered on future evolution of the Web. In 2008 he was an author of the first Italian Semantic Web book. Between 2004 and 2007, he was lecturer of Advanced Information Systems at Politecnico di Milano.

**![](images/andrea.jpg)Andrea Mauri** is a PostDoc Researcher at the Faculty of Architecture and the Built Environment, Department of Management in Built Environment in the Research Group of Urban Development Management. He works in the context of the BOLD Cities project, which aims to use big data research to help find solutions for urban problems. His main research interests include smart city sensing and social content analysis. In particular, he is interested in applying data science techniques for integrating data coming from different sources in order to get insight about the urban environment.

![](images/riccardo.jpg)

**Riccardo Tommasini** is a Ph.D. student at the Department of Electronics and Information of the Politecnico di Milano. He enrolled in November 2015, focusing on how to realize an efficient yet Expressive stream reasoning approach. His research interest comprises Reasoning and Ontology-Based Data Access, Stream Processing and Complex Event Processing, Temporal Logics and Benchmarking. Riccardo's teaching activities comprise (i) a Big Data Tutorial with practical classes on Esper and C-SPARQL during his visiting at Kno.e.sis Center at Wright State University, Dayton, Ohio. (ii) He is a teaching assistant at Politecnico di Milano for the courses: Interoperability and Semantic Web Technologies (15-16) and Principles of Programming Languages (16-217, 17-18).

**![](images/marco.jpg)Marco Balduini** is a Ph.D. student at the Dipartimento di Elettronica, Informazione e Bioingegneria (DEIB) of the Politecnico di Milano. His research work focuses on data integration, data processing, and semantic web. His major interest is the management of heterogeneous stream of spatio-temporal data. He developed Natron, a general-purpose system for stream processing. He is actively involved in the development of the C-SPARQL Engine and in the W3C Community Group on RDF Stream Processing (RSP). He participated in the research activities of the EU FP7 projects LarKC and ModaClouds and in the EIT projects City Data Fusion for Event Management, Crowd Insights, and Welcome. He is also a co-founder of Fluxedo, a start-up that exploits cutting-edge technology in the field of big data management and analysis.
