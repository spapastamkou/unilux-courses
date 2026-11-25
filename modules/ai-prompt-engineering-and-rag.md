---
title: AI - Prompt engineering and RAG
author: Sofia Papastamkou
date: 2026-11-25 
---

## Short introduction

Our topic today is: RAG as Retrieval-augmented generation and prompt engineering. 

Essentially, we will talk about how to best interact with LLMs as historians. 

In what purpose? To efficiently work with our sources. 

### Exploring a small corpus of historical data with a chatbot (CoPilot)

Description: 

Go to CoPilot or another chatbot. 

Prompt 1

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



## RAG


What can be the problems when interacting with LLMs? 

* no source
* outdated response (this is too related with the no source parameter)

### What is RAG 

Retrieval augmented ==> You provide a set of data to an LLM in order to be able to provide better quality responses in relation with a domain of interest. ==> retireve information relevant to a given query
  

## Prompting 
"Don't assume the model will infer what you want—state it directly" (from: Be explicit and clear https://claude.com/resources/articles/best-practices-for-prompt-engineering)

Prompt engineering: what is it

References to use: 







## Reading/viewing suggestions

Moritz Mähr. *Critical AI Literacy for Historians*. https://maehr.github.io/critical-ai-literacy-for-historians/en/. Accessed 25 November 2026.




Best Practices for Prompting for 2026. Claude, 10 November 2025, https://claude.com/fr/resources/articles/best-practices-for-prompt-engineering.