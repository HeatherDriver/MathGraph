# Exploring Transformer Models for Mathematical Knowledge Graphs

**Author**: Heather Driver  
**Institution**: International University of Applied Sciences – Data Science  
**Year**: 2025  
**Repository**: [github.com/HeatherDriver/MathGraph](https://github.com/HeatherDriver/MathGraph)

---

## Overview

This thesis investigated how Transformer models can be applied to construct Mathematical Knowledge Graphs (KGs) from unstructured text data. It adapted an attention-based span classification method which leveraged the distributional hypothesis via the Transformer attention mechanism, with the goal of improving predicate classification in mathematical contexts.

The study addressed shortfalls in traditional knowledge graph construction, for example its reliance on manual or rule-based information extraction (IE), and explored how Large Language Models (LLMs) can enhance this process.

---

## Abstract

An increasing amount of unstructured text data presents a challenge in effectively utilising this to create meaningful knowledge outputs. Knowledge Graphs (KGs) offer a structured approach to organising and extracting meaning from such data, however their construction often relies on labour-intensive methods which struggle to develop a contextual understanding of the data. 

Recent advances in Transformer-based models, particularly Large Language Models (LLMs), have significantly improved Natural Language Processing (NLP) tasks and offer a potential solution in automating Information Extraction (IE). This thesis therefore explores Transformer models and their mechanisms to construct mathematical KGs. 

An attention-based span method from a previous study was adapted to leverage the distributional hypothesis with a Transformer’s attention mechanism, in order to improve predicate classification. Results indicated that this approach improved classification across data with both direct and indirect predicate references. Further, this method also presented a robust solution in addressing low model recall which the previous study had noted. While the model was evaluated as being limited in its ability to distinguish predicate terms, the potential to improve if further trained was also noted. This presents a component of a potentially viable strategy for IE and KG development.

---

## Keywords

- Natural Language Processing (NLP)  
- Information Extraction (IE)  
- Knowledge Graph Development  
- Transformer Models  
- Predicate Classification  
- Span-based Entity Recognition  

---

## Repository Contents

- `README.md` – This file  
- `Data Sources/` – Supporting code for scraping data on mathematical definitions  
- `NER Model/` – Token classification for classifying named entities  
- `Predicate Classification/` – Main focus of thesis - creating span classification model
- `Predicate Data Sources/` – Cleaning and validating data - visualisation of model trained versus untrained using UMAP algorithm
- `Preprocessing/` - Additional cleaning and validation steps

---

## Contact

For questions or collaborations, feel free to reach out via GitHub: [@HeatherDriver](https://github.com/HeatherDriver)

---


