---
layout: page
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: tutorial
title: "Continuous Analytics of Linked Data Streams"
date: "2018-12-17"
---

### Abstract

The goal of the tutorial is to outline how to develop and deploy a stream processing application in a web environment in a reproducible way. To this extent, we intend to (1) survey existing research outcomes from the Stream Reasoning /RDF Stream Processing that arise in querying and reasoning on a variety of highly dynamic data, (2) introduce stream reasoning techniques as powerful tools to use when addressing a data-centric problem characterised both by variety and velocity (such as those typically found on the modern Web), (3) present a relevant Web-centric use-case that requires to address simultaneously data velocity and variety, and (4) guide the participants through the development of a Web stream processing application.

### Introduction

Data streams are increasingly becoming available on the Web. A variety of sources give origin to data streams, including social networks, mobile phones, smart homes, healthcare devices, and parts of the modern infrastructure. From new opportunities arise new challenges. A common problem in scenarios involving data streams on the Web is how data can be integrated to enable the creation of new knowledge. Reasoning techniques are a possible solution to help with this integration. However, while modern reasoners scale up in the static domain of ontological knowledge, reasoning upon rapidly changing information has received attention only in the last decade \[1\]. The combination of reasoning techniques with data streams has given rise to the new research area of Stream Reasoning. i.e., reasoning on highly dynamic flows of information \[2\]. Stream Reasoning research area that has started to produce impactful results relevant to both the Semantic Web \[3\] and stream processing communities \[4\].

**Objectives**: The goal of the tutorial is to provide the fundamental notion of reasoning over streams, provide an overview of current challenges and state of the art, describe the process of publication and description of data streams on the Web, showcase different techniques and technologies for processing Web streams, and outline the process of developing and deploying stream processing applications in a Web environment.

**Relevance**: The contents of this tutorial is highly relevant for ESWC 2019 attendees, as it focuses on practical aspects of developing and deploying applications that publish, produce, and process streaming (or rapidly changing) RDF data.

**Scope**: Stream reasoning technologies are now mature and reliable enough to build a tutorial with a stronger focus on hands-on sessions. Therefore, this tutorial not only surveys existing research outcomes and describes existing tools, but it also presents a Web-centric use-case and guides the participants through the development of a Web stream processing application.

**Learning objectives**: This full-day tutorial aims at introducing different existing approaches for querying, analyzing, and reasoning over data streams. It also provides guidelines for developing and deploying Stream Reasoning applications. In particular, the tutorial offers to the audience:

- an overview of the use-cases and scenarios where Stream Reasoning provides valuable advantages;
- an overview of the current state-of-the-art in this emerging area, with techniques and tools developed by several research groups (including but not limited to presenters’ ones);
- a focused description of a subset of these technologies to reason over dynamic data;
- practical experience through hands-on sessions were the audience can interact with existing tools.

**Target audience**. The tutorial targets researchers, knowledge workers, and practitioners interested in approaching the topic of web stream processing (both querying and reasoning) and who want to understand the current state-of-the-art as well as the future directions. The technologies and topics on this tutorial are relevant for people from IoT and sensor communities, as well as social media, pervasive health, oil industry, etc., who have to analyze in real-time massive amounts of streaming data.

### Program \[Tentative\]

We include links to teaching material, including slides and hands-on resources, that will be used and adapted for this tutorial. All the exercises make use of Jupyter Notebooks, which allows us to provide the infrastructure necessary for the tutorial exercises while hiding some of the underlying complexities for the users. Jupyter Notebooks is one of the most popular tools for data science in both academia and industry and the winner of 2017 ACM Software System Award.

9:00-10:30

- Introduction
    1. (instructions to download sources, colorwave) \[[slide](https://www.dropbox.com/s/vwxeqiwdslzodbx/01%20-%20Introduction.key?dl=0)\]
- Motivation \[[slide](https://www.dropbox.com/s/2g8p7pzj13gjgin/02%20-%20Motivation.key?dl=0)\]
    - The Stream Reasoning research question
    - Taming Data Variety and Velocity
- Background
    1. RDF & SPARQL in a nutshell \[[slides](https://www.dropbox.com/s/2nezp5h8q8syr6o/03%20-%20Background%20SW.key?dl=0)\]
    2. Stream processing 101 \[[slides](https://www.dropbox.com/s/4jqm74byov93tvt/04%20-%20Background%20SP.key?dl=0)\]
        - Time-based windows
        - Continuous Semantics
- RDF Stream Processing Processing \[[slide](https://www.dropbox.com/s/nq5t8mvq1u6rvtp/05%20-%20RDF%20Stream%20Processing.key?dl=0)\]
    1. Overview of RSP languages: [C-SPARQL](https://github.com/riccardotommasini/csparql2), CQELS-QL, SPARQLstream, RSP-QL.
    2. **Demo**: RSP-QL query conversion using SPIN
    3. VOCALS: A vocabulary for streams

10:30-11:00 Coffee break

11:00-12:30

- Semantic Complex Event Processing: RSEP-QL, DOTR, OBEP \[[slide](https://www.dropbox.com/s/ec3hwb2q1dg203b/06%20-%20SCEP.key?dl=0)\]
- Work in Progress for Inductive Stream Reasoning \[[slide](https://www.dropbox.com/s/p22anjq0mhvhbda/07%20-%20Inductive.key?dl=0)\]

12:30-14:00 Lunch

14:00-15:30

- RDF Stream Publishing \[[slide](https://www.dropbox.com/s/6rssakn9att73uj/05b%20-%20RDF%20Stream%20Publishing.key?dl=0)\] \[[code](https://github.com/riccardotommasini/webstreams)\]
- **Hands-on**: Designing the application: COLORWAVE
    - **Exercises**: Data visualisation and anomaly detection
    - **Exercises**: Stream exploration and reasoning
    - **Exercises**: Using [VoCaLS](https://github.com/ysedira/vocals/wiki) to create a catalog of streams

15:30-16:00 Coffee break

16:00-16:30:

- Hands-on (continue)
- 16:30- Wrap up and Discussion \[[slide](https://www.dropbox.com/s/0liv6kmvzl6vk3r/08%20-%20Conclusion.key?dl=0)\]

 

### Organizers

 **![Image result for jean-paul calbimonte](images/jeanpaul.jpg) Jean-Paul Calbimonte** is a senior researcher at HES-SO Valais-Wallis, Switzerland. His work focuses on data integration and Semantic Web, applied to streaming sensor data sources. He has worked on ontology-based access for streaming data, resulting in the SPARQLStream language and the Morph-streams evaluator. He also helps to coordinate the W

3C Community Group on RDF Stream Processing (RSP). He has previously presented in the ISWC 2013 and ISWC 2014 Stream Reasoning for Linked Data Tutorial, the ISWC 2016 RDF Stream Processing tutorial, and the ESWC 2014 RDF Stream Processing (RSP) tutorial. He has also presented a tutorial on Linked Stream Data at the Winter School on Knowledge Technologies for Complex Business Environments (2011) and a tutorial on Semantic Sensor Web at the Extended Semantic Web Conference (ESWC 2011).

![](images/riccardo.jpg)

**Riccardo Tommasini** is a Ph.D. student at the Department of Electronics and Information of the Politecnico di Milano. He enrolled in November 2015, focusing on how to realize an efficient yet Expressive stream reasoning approach. His research interest comprises Reasoning and Ontology-Based Data Access, Stream Processing and Complex Event Processing, Temporal Logics and Benchmarking. Riccardo's teaching activities comprise (i) a Big Data Tutorial with practical classes on Esper and C-SPARQL during his visiting at Kno.e.sis Center at Wright State University, Dayton, Ohio. (ii) He is a teaching assistant at Politecnico di Milano for the courses: Interoperability and Semantic Web Technologies (15-16) and Principles of Programming Languages (16-217, 17-18).

**[![](images/Robin_Keskisarkka.jpeg)](http://streamreasoning.org/wp-content/uploads/2018/12/Robin_Keskisarkka.jpeg)Robin Keskisärkkä** is PhD student at the Department of Computer and Information Science at Link¨oping University. His research focus is primarily on using Semantic Web technologies for Complex Event Processing, and on approaches for managing and propagating uncertainty in the context of streaming data. He is a member of the W3C Community Group on RDF Stream Processing (RSP).

![](images/eva_blomqvist-298x300.jpg)

**Eva Blomqvist** is an Assistant Professor in the Department of Computer and Information Science at Link¨oping University. Her research focus is on ontologies an ontology engineering, and she was one of the researchers who initially proposed the notion of Ontology Design Patterns (ODPs). During her PhD she worked on semi-automatic ontology development, so-called ontology learning. Eva has also been actively involved in the development, refinement and evaluation of the eXtreme Design ontology engineering methodology, which was the first agile ontology engineering methodology when it was proposed in 2009. More recently Eva has been involved in several projects applying ontologies in various contexts, e.g. in decision support systems, and using ontologies and other Semantic Web technologies to perform semantic Complex Event Processing to make sense of streaming data.

![](images/emanuele.jpg)**Emanuele Della Valle** is an Assistant Professor of Software Project Management at the Department of Electronics and Information of the Politecnico di Milano. He tries to perform research that is justified and guided by business needs. His major interest is in translating research results into business opportunities. In more than a decade of research, his research interests covered Semantic Web, Web Services, Service Oriented Architectures, Search Engines and, more recently on Stream Management Systems and Rank-aware Databases. His education activities include lecturing: Software Project Management at Politecnico di Milano; Knowledge Engineering at Universita dell Insubria; the RDF stream Processing tutorial at ESWC 2014, the Stream Reasoning for Linked Data tutorial series at SemTech 2011, ESWC 2011, ISWC 2013, ISWC 2014, ISWC 2015 the LarKC Early Adopters Tutorial Series at ISWC 2009, and ESWC 2010; a tutorial about Realizing Semantic Web Applications at BIS 2008, ISWC 2008, and ICWE 2010; and several industrial short courses for CEFRIEL centered on

future evolution of the Web. In 2008 he was an author of the first Italian Semantic Web book. Between 2004 and 2007, he was lecturer of Advanced Information Systems at Politecnico di Milano.

 

References 1. D. Dell’Aglio, E. Della Valle, F. van Harmelen, and A. Bernstein, “Stream reasoning: A survey and outlook,” Data Science, vol. 1, no. 1-2, pp. 59–83, 2017. 2. E. Della Valle, S. Ceri, F. van Harmelen, and D. Fensel, “It’s a streaming world! reasoning upon rapidly changing information,” IEEE Intelligent Systems, vol. 24, no. 6, pp. 83–89. 3. A. Margara, J. Urbani, F. van Harmelen, and H. E. Bal, “Streaming the web: Reasoning over dynamic data,” J. Web Sem., vol. 25, pp. 24–44, 2014. 4. E. Della Valle, D. Dell’Aglio, and A. Margara, “Taming velocity and variety simultaneously in big data with stream reasoning: tutorial,” in DEBS, pp. 394–401, ACM, 2016. 5. D. Dell’Aglio, E. Della Valle, J. Calbimonte, and O. Corcho, “RSP-QL semantics: A unifying ´ query model to explain heterogeneity of RDF stream processing systems,” Int. J. Semantic Web Inf. Syst., vol. 10, no. 4, pp. 17–44. 6. D. F. Barbieri, D. Braga, S. Ceri, E. Della Valle, and M. Grossniklaus, “C-SPARQL: a continuous query language for RDF data streams,” Int. J. Semantic Computing, vol. 4, no. 1, pp. 3–25. 7. D. L. Phuoc, M. Dao-Tran, J. X. Parreira, and M. Hauswirth, “A native and adaptive approach for unified processing of linked streams and linked data,” in The Semantic Web - ISWC 2011 - 10th International Semantic Web Conference, Bonn, Germany, October 23-27, 2011, Proceedings, Part I. 8. J. Calbimonte, O. Corcho, and A. J. G. Gray, “Enabling ontology-based access to streaming ´ data sources,” in The Semantic Web - ISWC 2010 - 9th International Semantic Web Conference, ISWC 2010, Shanghai, China, November 7-11, 2010, Revised Selected Papers, Part I, pp. 96–111. 9. R. Tommasini, E. Della Valle, M. Balduini, and D. Dell’Aglio, “Heaven: a framework for systematic comparative research approach for rsp engines,” in 13th Extended Semantic Web Conference, ESWC 2016, Heraklion, Crete, Greece, pp. 87–92.
