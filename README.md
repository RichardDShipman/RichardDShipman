# Hi there 👋

<!--
**RichardDShipman/RichardDShipman** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

I am a bioinformatician with a background in applied science, with a concentration in biochemistry and molecular biology. Throughout my life, I’ve been tinkering with computers, which naturally led me to support the projects I pursue. Past experiences involved developing computational proteomics tools that enable the discovery and application of novel phosphopeptides and glycopeptides with desired properties.  I am currently enrolled as a Master student in Omics Data Analysis at the University of Vic - Central University of Catalonia (UVic-UCC). I enjoy exploring the intersection of different omics fields with the aid of computational tools. For my Final Master's Project, I am researching at the University of Valencia on the glycovirology of rotaviruses. The projects listed below highlight some of those adventures.

## Recent Projects

Here is a list of recent projects I have been toying with on my free time.

1. Glycopeptide Sequence Finder 
- A script for hunting (protease-digested) N/O/C-linked glycopeptides in protein/proteome FASTA files based on sequon (motif). It includes a library of digested glycopeptides from various model organisms, common livestock & crops, sea critters and a host of fungus & viral pathogens. [Glycopeptide_Sequence_Finder](https://github.com/RichardDShipman/Glycopeptide_Sequence_Finder)
2. Glycoproteomics Graph Tool 
- Neo4j based graph knowledge base for storing glycoproteomics records in context to the central dogma of molecular biology. [Glycoproteomics_Graph_Tool](https://github.com/RichardDShipman/Glycoproteomics_Graph_Tool)
3.  Glycopeptide Proteoform Generator 
- A script to generate proteoforms by reading glycopeptide data from a CSV file, with limits on the number of proteoforms, saving results in both CSV and text file formats for each protein. [Glycopeptide_Proteoform_Generator](https://github.com/RichardDShipman/Glycopeptide_Proteoform_Generator)

## Machine Learning, Deep Learning and AI in Glycobiology and Proteomics Computional Research

Over the years, I’ve been experimenting with various machine learning and AI methods to tackle research problems and enhance my coding skills. This includes delving into the processes of software development in scientific research. Many of the tools I’ve utilized, particularly ChatGPT and its related tools, have been instrumental in generating code and solutions to my challenges. However, these tools often lead to incorrect processes and require significant adjustments to achieve functionality. Consequently, I’ve spent considerable time debugging and refining their code. Despite these efforts, some bugs persist, and there are instances of odd coding practices.

One notable observation is the substantial improvement in AI coding tools since their release over the past few years. I intend to leverage these tools and integrate them further into my projects. One of the tools I’ve begun with is a RAG (retrieval augmented generation) system using Chroma DB as a vector database to store content from glycobiology papers. This approach has significantly enhanced the performance of the system when answering questions related to glycobiology and proteomics.

One of my initial projects involved the use of local LLMs with Ollama, as linked below. I’m committed to exploring and developing local LLMs that process or generate data based on user inputs. In the future, I plan to release a tool that can translate CSV documents from one language to another. These experiments aim to improve accessibility of scientific data to our language-speaking community, thereby removing barriers in science that stem from language barriers.

Deep learning, an intriguing topic to explore and apply, heavily relies on input data, posing a significant challenge due to the sheer complexity of biology and chemistry in the real world. Much biochemical research generates data focused on humans, mice, or other commonly used model organisms, hindering the application of deep learning tools across the tree of life and uncovering new biochemical functions beyond human or standard model organism use. This prompted me to explore other species and lesser-annotated species to determine how these tools can be more effectively applied to all the creatures on Earth. As with all AI topics, the field is rapidly advancing at an unprecedented pace, so I am confident that as their methods expand, we will witness improved applications in this area.

- TEXT_RAG [Link](https://github.com/RichardDShipman/TEXT_RAG) - A RAG that constructs a ChomaDB vector database for LLM querying of PDFs, HTMLs, and TXT files.

## Past Projects

Here is a list of past projects I have worked on, with links to related GitHub repositories if they are available. 

1.	Glycoproteomics Knowledge Database Development 
- Developed a Neo4j graph database for glycomics, integrating public multi-omics data.
2.	Glycoproteomics Mass Spectrometry Deep Learning Pipeline 
- Optimized a Python-based machine learning pipeline for glycoproteomics mass spectrometry, improving the accuracy of N-glycopeptide identification using deep learning models to analyze fragmentation patterns. [Link](https://github.com/Vennbiosciences/D-Va-GlycoML)
3.	N-Linked Glycoform Categorization 
- Developed R scripts for categorizing glycoforms based on mass spectrometry data, contributing to the analysis of glycosylation patterns in diseases. [Link](10.1016/j.mcpro.2021.100081)
4. O-Linked Glycoproteomics of Alzhiemer's Disease Progression
- Monitored changes in the O-glycoproteome in the CSF of patients with progressing stages of AD. [LINK](https://pubmed.ncbi.nlm.nih.gov/34964596/)

## Technical Skills

- Languages: Python, R, Bash
- Data Management: SQL, Neo4j - Cypher
- Data Visualization: R Shiny, Neodash, ggplot2
- Bioinformatics: Omics Data Analysis, Mass Spectrometry, Proteomics, Glycomics, Glycoproteomics
