---
layout: page
description: a project with a background image
img: assets/img/iswc15logo.png
importance: 1
category: workshop
title: "OrdRing 2015"
date: "2016-05-02"
---

# 4th International Workshop on Ordering and Reasoning

**October** ****12th**, 2015  
****Bethlehem, Pennsylvania, US  
Collocated with the 14th International Semantic Web Conference ([ISWC 2015](http://iswc2015.semanticweb.org/))**

[Abstract](#abstract) [Motivation](#objectives) [Topic Of Interest](#topics) [Submissions](#SUBMISSIONS) [Program](#program) [Proceedings](#PROCEEDINGS) [Important Dates](#IMPORTANT%20DATES) [Workshop Chairs](#WORKSHOP%20CHAIRS) [Program Committee](#PC)

## ABSTRACT

More and more applications require real-time processing of massive, dynamically generated, ordered data; where order is often an essential factor reflecting recency, proximity or relevance. Stream and rank-aware data management techniques are progressively providing reactive and reliable query answering over such massive datasets. Key to their success is the use of streaming algorithms that harness the natural or enforceable orders in the data. Semantic technologies can play a relevant role in this setting, exploiting their expressive power to integrate those highly dynamic sources. In the recent years, different work started to push order-related concepts in semantic technologies, such as Stream Reasoning and top-k ontological query answering. The workshop (as its predecessors in [2011](http://ordring2011.search-computing.org/), [2013](events/ordring2013), and [2014](events/ordring2014)) aims at bringing together this growing and very active community interested in in **[integrating ordering with reasoning](http://www.semantic-web-journal.net/sites/default/files/swj246_1.pdf "Emanuele Della Valle, Stefan Schlobach, Markus Krötzsch, Alessandro Bozzon, Stefano Ceri, Ian Horrocks: Order matters! Harnessing a world of orderings for reasoning over massive data. Semantic Web 4(2): 219-231 (2013)")** by using methods inspired by stream and rank-aware data management.

## MOTIVATION

The continuous growth of volume, velocity and variety of data poses new challenge for their processing, especially when it has to be done in real-time or near-real time. It often happens that orders are involved in those processes: the input data can be ordered by some criteria (e.g. recency, proximity), and so the output data (e.g. relevance). In both cases, orders can play a key-role, enabling the design of ad-hoc algorithms and processes that exploit those orders to increase the performance. A relevant example can be found in rank-aware data management, where there are techniques to perform query answering through streaming algorithms that exploit the natural or enforceable orders in the data. Moreover, in stream data management, algorithms are not only designed to be online and streaming, but also any-time: they processes the input data and they produce sequences of valid answers at different time instants.  
The expressive power of Semantic technologies is needed in those applications, but Semantic Technologies risk being unable to address the needs of those applications, because they do not consider ordering as an essential property. Ranking results is often seen as an “added task”, performed after inference, without affecting the inference process, which is order-agnostic. However, we perceive a trend towards order-aware semantic technologies: both researchers and practitioners understand that _order matters in reasoning over massive and highly dynamic data_. The idea of Stream Reasoning is gaining considerable momentum. Some top-k query answering techniques for Linked Data appeared. Several works are considering SPARQL query answering on RDF annotated with labels partially ordered. The Description Logic community is investigating top-k ontological query answering.  
We see this workshop as a further step to stimulate and guide a paradigm shift in semantic technologies. We aim at involving researchers and experts in stream and rank-aware data management to put together their competences and to share them with the community. The final goal of the workshop is to contribute to this young, but very active trend of order-aware data processing.

## TOPICS OF INTEREST

Topics include, but not limited to:

- Inference with streaming algorithms
- Ontological query answering over data streams
- Incremental maintenance of materialization of data streams
- Continuous query answering over data streams
- Ontological top-k query answering over massive ordered data
- Data compression algorithms for data stream processing
- Continuous query answering and top-k query answering for fuzzy logics
- Knowledge Representation for ordered facts
- APIs for data stream exchange
- Topologies for distributed processing of data streams
- Role of parallelization and distribution in order-aware semantic technologies
- Approximation approaches to inference with orderings
- Proposals for and applications of benchmarks
- Applications of stream reasoning and top-k ontological query answering
- Implementation and evaluation experiences

## PROGRAM

- 14:00-14:05 Workshop introduction
- 14:05-14:50 Keynote: _“Models of High-Level Declarative Stream Processing”._, Özgür Özcep.
- 14:50-15:10 _“Performant Event-Driven Rule-Based Reasoning using EYE”._ Ben De Meester, Doerthe Arndt, Pieter Bonte, Jabran Bhatti, Wim Dereuddre, Ruben Verborgh, Femke Ongenae, Filip De Turck, Erik Mannens and Rik Van de Walle.
- 15:10-15:30 _“Running out of Bindings? Integrating Facts and Events in Linked Data Stream Processing”._ Shen Gao, Thomas Scharrenbach, Joerg-Uwe Kietz and Abraham Bernstein.
- 15:30-16:00 Break
- 16:00-16:20 _“Heaven Test Stand: towards comparative research on RSP Engines”._ Riccardo Tommasini, Emanuele Della Valle, Marco Balduini and Daniele Dell'Aglio.
- 16:20-17:05 Keynote: _"Semantic Stream Processing: Navigating the Chasm between the Scylla of Practical Applications and the Charybdis of Theoretical Approaches"_, Avi Bernstein
- 17:05-18:15 Discussion and W3C F2F meeting

## SUBMISSIONS

We will welcome submissions describing ideas, experiments, and application visions originating from requirements for, and efforts aimed at, interleaving ordering and reasoning. We will encourage **short position** and **short demo papers** not exceeding 6 pages as well as longer **technical papers** not exceeding 12 pages. We also invite participants to submit **Expressions of Interest (EoI)** not exceeding two pages, describing expertise, current research interests and relation to the community and ISWC audience in general.

Submissions should be formatted according to the Lecture Notes in Computer Science guidelines for proceedings available at [http://www.springer.com/computer/lncs?SGWID=0-164-7-72376-0](http://www.springer.com/computer/lncs?SGWID=0-164-7-72376-0). Papers should be submitted in PDF format. All submissions will be done electronically via the OrdRing2015 Web submission system ([http://www.easychair.org/conferences/?conf=ordring2015](http://www.easychair.org/conferences/?conf=ordring2015)).

At least one author of each accepted paper must register for the workshop. Information about registration will appear soon on the [ISWC 2015 Web page](http://iswc2015.semanticweb.org/).

## PROCEEDINGS

The Workshop Proceedings are published by CEUR-WS and are available [here](http://ceur-ws.org/Vol-1488/).

## IMPORTANT DATES

- Abstract submission deadline: June 24, 2015 July 8, 2015
- Paper submission: July 1, 2015 July 12, 2015
- Author notifications: July 31, 2015
- Camera ready version due: August 21, 2015

## WORKSHOP CHAIRS

- [Jean-Paul Calbimonte](http://jeanpi.org) (EPFL)
- [Irene Celino](http://iricelino.org/) (CEFRIEL)
- [Emanuele Della Valle](http://emanueledellavalle.org) (Politecnico di Milano)
- [Daniele Dell'Aglio](http://www.dellaglio.org/) (Politecnico di Milano)
- [Markus Krötzsch](http://korrekt.org/) (Technische Universität Dresden)
- [Stefan Schlobach](http://www.few.vu.nl/%7Eschlobac/) (Vrije Universiteit Amsterdam)

## PROGRAM COMMITTEE

- Darko Anicic (Siemens AG)
- Marco Balduini (Politecnico di Milano)
- Alessandro Bozzon (TU Delft)
- Oscar Corcho (Universidad Politécnica de Madrid)
- Soheila Dehghanzadeh (Insight Centre for Data Analytics)
- Shen Gao (University of Zurich)
- Peter Haase (metaphacts)
- Freddy Lecue (IBM Research Ireland)
- Alejandro Llaves (Universidad Politécnica de Madrid)
- Tomas Masopust (TU Dresden)
- Alessandro Margara (University of Lugano)
- Alessandra Mileo (Insight Centre for Data Analytics)
- Jeff Z. Pan (University of Aberdeen)
- Giuseppe Pirrò (University of Koblenz-Landau)
- Umberto Straccia (ISTI-CNR)
- Anni-Yasmin Turhan (TU Dresden)
- Maria Esther Vidal (Universidad Simón Bolívar)
- Haofen Wang (East China University of Science and Technology)
- Kewen Wang (Griffith University)
- Zhe Wu (Oracle)
- Shima Zahmatkesh (Politecnico di Milano)
