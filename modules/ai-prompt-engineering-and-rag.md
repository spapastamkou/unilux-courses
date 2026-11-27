---
title: AI - Prompt engineering and RAG
author: Sofia Papastamkou
date: 2026-11-25 
---

## Short introduction

Our topic today is: RAG as Retrieval-augmented generation and prompt engineering. 

Essentially, we will talk about how to best interact with LLMs as historians. 

In what purpose? To efficiently work with our sources. 

## Datasets

We work with one dataset containing texts and one dataset containing images. 

### Dataset 1: articles on the surveys of Computers and the Humanities

5 surveys of the journal Computers and the Humanities from 1971 to 1987 to gather information on the first ever courses introduced in the higher education on use of computers in the humanities. 

Results, data and analysis of each survey available in 5 articles. These five articles, in PDF format, are dataset 1. 

### Dataset 2: corpus of posters of Printemps érable

Dataset: posters of the 2012 student protests in Montréal, Canada. [URL](https://zenodo.org/records/13936156) 

The dataset was extracted from the website Printemps érable archives https://www.printempserable.net/ 

If necessary, consult the Wikipedia article to know more about the context: the 2012 student protests in Montréal known as Printemps érable: https://en.wikipedia.org/wiki/2012_Quebec_student_protests This is not required for the course.  

### Hands on activity 1 - Exploring dataset 1 with a chatbot (CoPilot)

Description:

Download the five articles on the surveys of Computers and the Humanities and make sure you have them on your machine.  

Go to CoPilot or another chatbot. We are going to work with simple zero-shot prompts.


Prompt 1

*To situate what we do in the workflow of historical research: we are in the phase of heuristics (search)*

* Provide information about the surveys of Computers and the Humanities on teaching computers in the humanities (1971-1987).

*Once you get the output: Inspect the answers and evaluate them in terms of precision, clarity, usefulness for a research (heuristics, hermeneutics), grounding (attachment to sources).*  

* Provide a detailed list of your sources.

*Once you get the output. Inspect the answers and evaluate them ADD HERE A FRAMEWORK OF EVALUATION*

* Access the original articles and read the survey data. Count for each year the number of universities that host the departments that report courses. List the countries in which these universities belong to.  

*Once you get the output. Inspect the answer and evaluate it.*

![Access the data output](/assets/images/ai-prompt-engineering-and-rag/copilot-output-access-data.png)

Problem: the content of the scientific articles is behind a paywall, thus not accessible. The data they contain, which are primary sources for my research, are not accessible either. 

The response that I get explains these limits: 
* Says it cannot reliably produce the counts I ask (LLM evaluates the answer and warns about its limits)
* Gives elements of an answer that it can reconstruct with confidence - problem here is: answer is based on reports available in secondary literature and not analyse of the primary data. (==> which is what a historian must NOT do). 
* Guides me as to what I need to do in order for it to do what I want: upload scans of data (dataset)     

![Upload the scans output](/assets/images/ai-prompt-engineering-and-rag/copilot-output-guidance.png)

* New (big) problem: impossible to upload a corpus because of limits of use of the chatbot. 3 out of 5 PDFs uploaded, which makes my effort incomplete: I cannot continue a serious analysis of my sources. 

![Limit uploads](/assets/images/ai-prompt-engineering-and-rag/copilot-input-limit-uploads.png)

In conclusion, what I have here is: specific problems when interacting with LLMs to get responses that fit specific needs, in this case my historical research. The main problems are listed below: 

* I encounter limits due to generic nature LLMs data, restrictions due to their commercial nature, problems due to accessibility of sources, format of source data...
* I need to ground the LLM's answers to specific sources
* I need to connect these sources to the LLM so that it takes them into account in its output
* How to work with bigger data? Scalability problem.  

## RAG

RAG - for Retrieval augmented generation - can be an answer to needs like this. 

### What is RAG? what does it do?  

RAG is a method, framework, solution...

An LLM is based on big quantities of data but these data are generic. What does RAG?  

RAG provides specific, new, and unknpwn data to an LLM so that the user is able to retrieve information that is relevant to the user's given query (prompt, question). In other words, if you wish to obtain information relevant to a historical research, you must provide relevant materials for the LLM to process them. 
What RAG does: it is based on **semantic similarity** search and retrieves text **chunks** based on semantic similarity.

* *Semantic similarity is [how close two terms, sentences, or documents are in meaning](https://en.wikipedia.org/wiki/Semantic_similarity). This is achieved with the use of embeddings and knowledge graphs. 
* *Text chunking is [the process of splitting a text into smaller pieces](https://graphrag.com/guides/chunking/)* 

GraphRAG is an advanced form of RAG designed by researchers affiliated with Microsoft.
GraphRAG is based on knowledge networks. Retrieves information based on connections. (see with Mehrdad).  

(See following section, presentation of Mehrdad Almasi)


### Presentation of Mehrdad Almasi 

[Slides RAG](/assets/data/ai-rag/RAG_.pptx)

### Hands on activity 2 - Exploring dataset 1 with GraphRAG

Explore the [corpus of PDFs GraphRAG](http://10.240.26.115:8055/) 




### Hands on activity 3 - Exploring dataset 2 


Explore the [corpus of posters](http://10.240.26.115:8060/) of the student protests in Québec in 2012


2d clip https://leoimpett.github.io/2dclip/


## Prompting 
"Don't assume the model will infer what you want—state it directly" (from: Be explicit and clear https://claude.com/resources/articles/best-practices-for-prompt-engineering)

Prompt engineering: what is it

References to use: 

Moritz Mähr https://maehr.github.io/critical-ai-literacy-for-historians/en/exercises/prompt-engineering.html#prompt-basics

Best Practices for Prompting for 2026. Claude, 10 November 2025, https://claude.com/fr/resources/articles/best-practices-for-prompt-engineering.





## Reading/viewing suggestions

Moritz Mähr. *Critical AI Literacy for Historians*. https://maehr.github.io/critical-ai-literacy-for-historians/en/. Accessed 25 November 2026.

Best Practices for Prompting for 2026. Claude, 10 November 2025, https://claude.com/fr/resources/articles/best-practices-for-prompt-engineering.

IBM Technology. 7 AI Terms You Need to Know: Agents, RAG, ASI & More. 1st September 2025. YouTube video https://youtu.be/VSFuqMh4hus  

IBM Technology. What is Retrieval-Augmented Generation (RAG)? 23 August 2023. YouTube video. https://youtu.be/T-D1OfcDW1M 