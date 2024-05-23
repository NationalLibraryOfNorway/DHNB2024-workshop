---
subject: DHNB2024 WS5-1 HALF-DAY WORKSHOP (LABS)
description: Abstract
date: 2024-05-29
venue: H-207
authors:
  - name: Digital Humanities Lab
    email: dh-lab@nb.no
    affiliation: National Library of Norway
    url: "https://www.nb.no/dh-lab/"
    github: NationalLibraryOfNorway
export: pdf
label: abstract
---

# Abstract

## Navigating Digital Landscapes: Experiences from A Decade of Engaging with users of Digital Humanities

**Lars G Johnsen, Jana Sverdljuk, Ingerid Løyning Dale, Lars Magne Tungland, Marie Iversdatter Røsok, Jon Carlstedt Tønnessen**

> [Link to description at the official DHNB2024 website](https://dhnb.eu/conferences/dhnb2024/workshops/navigating-digital-landscapes/)

<!-- intro-abstract-start -->
This workshop will explore the evolution of the National Library of Norway's Digital Humanities Laboratory over the past decade. Based on the laboratory's rich history of collaboration and engagement, it will delve into the lessons learned from its interactions with academic institutions, humanities, and social sciences communities, focusing on the main theme: interacting with users.

Workshop participants will reflect on and demonstrate the integration of user-friendly elements in the digital humanities laboratory’s functioning, such as:

1. providing accessibility of data
2. fostering usability of analysis
3. assisting with interpreting results

The elements correspond to the main stages of digital humanities projects, that the laboratory walks along with its users: from bachelor, master and PhD students to academic units and institutions.

<!-- intro-abstract-end -->

<!-- summary-abstract-start -->

The workshop will consist of three parts:

1. By providing preprocessed and easily accessible datasets, the Digital Humanities Laboratory streamlines the initial stages of research for academic communities. Researchers can focus on analysis and interpretation rather than spending significant time on data preprocessing.
2. Creating applications with user-friendly interfaces democratize access to digital humanities tools. Academics without extensive technical expertise can actively engage in digital research, broadening participation across disciplines.
3. The applications are supplemented with descriptions of the methods used to support better understanding of results and initiate reflections on combination of quantitative and qualitative methods. Sufficient explanation of the analysis outcomes encourages engagement of digital humanists in meaningful conversations with scholars from traditional humanities disciplines, fostering a mutually beneficial relationship.
<!-- summary-abstract-end -->

<!-- 01-data-accessibility-start -->
(01-data-accessibility)=
## Infrastructure and accessibility

We will showcase the current methods employed to make data available for users, highlighting text mining and big data analysis.
The National Library of Norway has a large collection of digitized published works, which have gone through an extensive processing pipeline:

* Large scale image scanning of books, magazines, newspapers, and other publications

* Optical Character Recognition

* Text extraction from the resulting files into indexed databases, allowing for fulltext search

* Tokenization, splitting text into word tokens, allowing for quantitative analysis on word level

* Constructing metadata databases, allowing for metadata search and corpus construction

We will connect the showcased techniques to the DH-lab's history, illustrating how they have evolved based on user feedback and engagement. A key point of our interfaces is that we can share and present the data without infringing on copyrights.

* User facing application programming interfaces (API)

* Workshops with researchers and students

* Jupyter Notebooks with python and pandas

* Project collaborations

* Apps

Example datasets: bibliographies

<!-- 01-data-accessibility-end -->

<!-- 02-user-friendly-interfaces-start -->
(02-user-friendly-interfaces)=
## Creating User-Friendly Interfaces and Applications


This session explores the innovative approaches the National Library of Norway has adopted in creating user-friendly interfaces and applications for digital humanities projects.
We'll showcase our DH-lab app development methodology, which incorporates the use of Flask APIs and the dhlab Python library, alongside the integration of Streamlit for interactive, web-friendly applications.
With our indexed databases of digital texts, we have developed a suite of apps for analysing reduced representations of the data:

* Corpus construction: Lists of document IDs and their metadata

* N-gram statistics: Frequency counts of uni-, bi- and trigrams over time

* Concordances: Immediate contexts of specific search terms

* Collocations: Aggregated concordances, ranked by word similarity scores calculated with pointwise mutual information

The session will be a hands-on experience, inviting participants to navigate through these interfaces. This practical exploration aims to provide an immersive understanding of the user-centric design principles we've implemented over the years.
The apps are available from the National Library’s official website: https://www.nb.no/dh-lab/apper/

<!-- 02-user-friendly-interfaces-end -->

<!-- 03-combining-methods-start -->
(03-combining-methods)=
## Combining Quantitative and Qualitative Methods


Showcasing collaborative projects that harmoniously integrate quantitative (text mining, collocation analysis, georeferencing, topic modelling) with qualitative methods (e.g. discourse analysis).

* Analysing examples of papers using quantitative and qualitative methods

* Combining tools for quantitative research and critical discourse analysis

* Reflecting on the evolution of these integrative methodologies, considering insights gained from papers and user involvement in educational and outreach events

* Examples from bachelor students’ involvement with digital humanities tools at the NLN

<!-- 03-combining-methods-end -->
