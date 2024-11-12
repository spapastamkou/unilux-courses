--- 
title: Generative Artificial Intelligence - Assignments for Historians 
author: Sofia Papastamkou
slug: gen-ai-hist
date: 2024-11-
---
<!--
Machine learning: a branch of AI that deals with creating algorithms that learn (= evolve to get more efficient) when applied to (large) corpora of data. What these algorithms do: they predict, based on statistic probabilities sequences of words. This is based on word vectorisation/embedding: strings of text (words) converted into sets of numbers (vectors, embeddings).

An example: web search engines apply this once you enter a query (see screenshot of Google engine)

What is an algorithm: 

GPT for Generative Pre-Trained Transformer: an architecture of machine learning (basically, data and algorithms). It can read and treat all input data at once and gets better when trained with large corpora of data. Improved accuracy of outputs.  

Attention mechanism: a technique that allows the nural network to focus on specific parts of an input sequence. Done by assigning weights to different parts of input sequence. Most important parts = heighest weights 

AM different from sequence to sequence model: 1) passing more data to the decoder through he hidden state, that allow the decoder to have more context 2) add an extra step before producing the output  

Hidden state: input + past inputs (the memory of all inputs)  in a RNN (recurrent neural network)

GPT: an architecture of machine learning (basically, data and algorithms). It can read and treat all input data at once and gets better when trained with large corpora of data. Improved accuracy of outputs. Simply put: it can generate unique text (output data) when it receives a specific query/instruction/prompt. 

-->

The assignments that follow below have vocation to offer a hands-on introduction to the generative pretrained transformers for historians. They should ideally be done in groups of three, or four if necessary.

## Interrogate a national narrative based on a corpus of press articles 

This assignment was inspired by the following lesson of Programming Historian: Brousseau, Chantal. « Interrogating a National Narrative with GPT-2 ». *Programming Historian* 11 (2022), https://doi.org/10.46430/phen0104 

The approach is simplified and adapted to use with an online GPT. For this reason it uses only one small part of the initial data whose size (22.50 MB) proved to be difficult to handle by online GPTs (ChatGPT, for example was unable to charge it despite it being capable to receive files up to 50 MB; MistralAI does not accept files at all and the copied pasted data were not processed). For this reason, this assignment serves as an exploratory exercice for students to work with a set of sources and the results obtained while interrogating the GPT should be taken with caution. 

### Instructions

Work in groups of 3 or 4. Please make sure you already have access to one GPT you can use for free and note that, in some cases, you may have to create a (free) user account. 

Your task is to explore a corpus of historical sources with the help of the GPT your group selected. In our case, the historical sources are articles from the British Press regarding Brexit (2016), the withdrawal of the United Kingdom from the European Union. Details about how the corpus was created are available in the lesson mentioned above. Please assign one of the group members to read them as this information is important for evaluating the source. Sum up and use this information during your group's presentation. Note that you will use only a small part of these data using the file we provide.

If you need additional information about the Brexit, you can consult the [Wikipedia notice on the event](https://en.wikipedia.org/wiki/Brexit); [a comprehensive timeline](https://www.consilium.europa.eu/en/brexit/) on the website of the EU Council and, eventually, [information regarding the technical implications of the UK's withdrawal](https://gouvernement.lu/en/dossiers/2019/brexit.html) on the website of the government of the Grand Duchy of Luxembourg.  

First, [get the file of the data](/assets/data/brexit-articles-small.txt). Depending the GPT you selected, you may either attach the file through the discussion box or have to copy and paste them directly there. You can declare to the GPT that these are your input data and, if you want, provide some context - this will be your first prompt. 

You can then explore the data using prompts. For your prompts: 

- Make sure that you give concise and clear instructions 
- Ask one thing at the time and avoid long and complicated phrases
- Ask informed questions: focs on actors (personalities, political parties...), on specific events that may have been decisive...
- Ask plausible questions and avoid unrealistic scenarios, for example conspirational theories

 It is better of course to know details about the subject! Only then it is possible to gain knowledge on aspects we would not have observed otherwise. But for now, we can use some basic contextual information about the UK and explore the insights we can have with our data. 


Here are some questions that you could ask: 
- How is Brexit defined? 
- What is the perception of the Conservatives? of the Tories?
- How is a given key political personality described? 
- Other question(s) you can think of?

You can also check [this part of the dedicated lesson](https://programminghistorian.org/en/lessons/interrogating-national-narrative-gpt#interrogating-our-model) for inspiration while interrogating the GPT.   

Formulate from three to five questions. Then observe the answers you obtain. 
- Are the answers lengthy? Do they have numbered parts? If yes, how low does the numbering go? 
- Do the answers make sense? Do you find errors or ["hallucinations"](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence))?
- How do you judge the answers (the output data) you obtain? 
	- If you had limited knowledge on Brexit, how do you feel you can build on the information you obtained? 
	- If you had a certain level of knowledge on Brexit, do you have unexpected insights? 
- How do you imagine using this kind of data in your research, for example to further interrogate your sources or while writing an essay

If you have time, reflect on the following extract:   

"In a way, the output of GPT is various interpretations of a singular history being performed, and you are the critic meant to analyze and elucidate each performance. Are these performances completely accurate to their source material? No, but in their “inaccuracy” we can find new perspectives and expositions that differ from our own, which ultimately expands our understanding of the subject at hand." (In Brousseau, *op. cit.*).  



## 
Cite an image generated with AI: 
Instructions following the APA citation style: https://library.senecapolytechnic.ca/apa/artificialintelligence 

