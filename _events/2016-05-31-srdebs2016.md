---
layout: page
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: tutorial
title: "SRT@DEBS2016"
date: "2016-05-31"
---

# Tutorial on Stream Reasoning: Managing Velocity and Variety in Big Data at DEBS 2016

**June 20th, 2016  
****Irvine, California, US**  
**Co-located with the 10th International Conference on Distributed and Event-Based Systems ([DEBS 2016](http://www.debs2016.org/))**

[Abstract](#abstract) [Program](#program) [Prerequisite knowledge](#pre) [Tutorial paper](#paper) [The team of presenters](#team)

## Abstract

Many “big data” applications must process large volumes of heterogeneous data in real-time or near real-time to create new knowledge. The research on Semantic Web has focused on the variety of data, devising data representation and processing techniques that promote the integration and reasoning on available data to produce new knowledge. On the other hand, the community working on event and stream processing has focused on the velocity of data, producing systems that efficiently operate on streams of data on-the-fly according to pre-deployed processing rules or queries.

Several recent works explore the synergy between stream processing and reasoning to fully capture the requirements of modern data intensive applications. This gave birth to the research domain of stream reasoning. This tutorial offers a detailed presentation of the theoretical and technological achievements in stream reasoning, highlighting the key benefits and limitations of existing approaches, and discussing the open issues and opportunities for future research.

The tutorial is conceived for an audience that is familiar with the models and systems for event and stream processing. It aims to further promote the integration of reasoning and event and stream processing in two ways: (i) it presents an active research domain, where researchers on event and stream processing can apply their expertise; (ii) it overviews reasoning techniques and technologies that can help advancing the state of the art in event and stream processing.

## Program

### First part: Introduction to RDF Stream Processing and Reasoning - 13.30 - 15.00 \[[slides](/slides/2016/06/srt2016_stream_reasoning_part_1.pdf)\]

#### Introduction to Stream Reasoning (30 min)

The first session gives an overview of the Stream Reasoning research area, covering:

- Challenges, and how existing systems (DSMS/CEP, Semantic Web) address them
- Scope of Stream Reasoning research area
- Existing Systems (quick introduction and high-level comparison)

#### Semantic Web Technologies (30 min)

This session covers:

- Introduction to the W3C Semantic Web Stack
- Overview of the RDF model
- Overview of the SPARQL query language
- Overview on reasoning (in particular in the context of query answering)

#### Stream Reasoning: Naive Approaches (30 min)

This session covers:

- Problem definition and challenges
- Full goal drive approaches on each snapshot
- Materialization of each snapshot in a stream
- Query rewriting based approaches
- the DReD approach for incremental maintenance of materialisations

### Coffee Break: 15:00 - 15:30

### Second part: Stream Reasoning - 15:30 - 17:00 \[[slides](/slides/2016/06/srt2016_stream_reasoning_part_2.pdf)\]

#### Stream Reasoning: Advanced Approaches (60 min)

This session covers:

- DynamiTE
- TrOWL
- IMaRS
- Sparkwave
- RDF Stream Reasoning with GPUs
- ETALIS and EP-SPARQL
- Stream Reasoning with ASP
- STARQL
- LARS

#### Wrap-up and conclusions (30 min)

This session covers:

- Achievements of existing approaches w.r.t. Stream Reasoning Challenges
- Open problems and a revised Stream Reasoning research agenda
- Open Q/A

## Prerequisite knowledge

We do not assume prior knowledge of Semantic Web technologies and we dedicate the first part of the tutorial to introduce the terminology and concepts in the domain of Semantic Web and reasoning. We assume the audience to be familiar with the fundamental models and technologies for event and stream processing.

The last part of the tutorial will investigate the similarities and differences between stream reasoning and event and stream processing. This is intended to stimulate the discussion on the open issues in the fields and on the opportunities for integration. We will specifically address open problems that fit in the domain of expertise of the DEBS attendees, such as parallel and distributed processing of streaming data.

## Tutorial Paper

A tutorial [paper](https://dl.acm.org/citation.cfm?id=2933539&CFID=800410691&CFTOKEN=37340458) with a summary of the tutorial can be found in the DEBS proceedings.

## The team of presenters

- [Emanuele Della Valle](http://emanueledellavalle.org/) (Politecnico di Milano)
- [Daniele Dell'Aglio](http://www.dellaglio.org/) (Politecnico di Milano)
- [Alessandro Margara](#) (Politecnico di Milano)
