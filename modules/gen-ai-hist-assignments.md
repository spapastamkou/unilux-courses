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

## Interrogate a corpus of press articles on Brexit with the help of a GPT 

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
- Ask informed questions: focus on actors (personalities, political parties...), on specific events that may have been decisive...
- Ask plausible questions and avoid unrealistic scenarios, for example conspirational theories

 It is better of course to know details about the subject! Only then it is possible to gain knowledge on aspects we would not have observed otherwise. But for now, we can use some basic contextual information about the UK and explore the insights we can have with our data. 


Here are some questions that you could ask: 
- How is Brexit defined? 
- What is the perception of the Conservatives? of the Tories?
- How is a given key political personality described? 
- Other question(s) you can think of? About international events, inter- or supra-national organizations... 

You can also check [this part of the dedicated lesson](https://programminghistorian.org/en/lessons/interrogating-national-narrative-gpt#interrogating-our-model) for inspiration while interrogating the GPT.   

Formulate from three to five questions. Then observe the answers you obtain. 
- Are the answers lengthy? Do they have numbered parts? If yes, how low does the numbering go? 
- Do the answers make sense? Do you find errors or ["hallucinations"](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence))?
- How do you judge the answers (the output data) you obtain? 
	- If you had limited knowledge on Brexit, how do you feel you can build on the information you obtained? 
	- If you had a certain level of knowledge on Brexit, do you have unexpected insights? 
- How do you imagine using this kind of data in your research, for example to further interrogate your sources or while writing an essay
- Do you think you would have the same quality of results if your corpus was composed by transcriptions of ancient Roman epigraphies or articles of Chinese newspapers on Brexit?  

If you have time, reflect on the following extract:   

"In a way, the output of GPT is various interpretations of a singular history being performed, and you are the critic meant to analyze and elucidate each performance. Are these performances completely accurate to their source material? No, but in their “inaccuracy” we can find new perspectives and expositions that differ from our own, which ultimately expands our understanding of the subject at hand." (In Brousseau, *op. cit.*). 

Please prepare a short presentation (5-7 minutes for the rest of the class) and discuss your findings. 

## Learn how to interrogate a large corpus of sources with a GPT

Please use the following lesson of Programming Historian: Brousseau, Chantal. « Interrogating a National Narrative with GPT-2 ». *Programming Historian* 11 (2022), https://doi.org/10.46430/phen0104 

Your task is to use a GPT your group selected as a tutor for helping you to understand the value of a given method - in this case, use a GPT for interrogating a corpus of historical sources - and the technical components you are likely to completely, or almost, ignore for the moment, but that you are likely to need to master in some time from now. Why you might need to do this? Because if you have a large corpus of sources you might find restrictions to use effectively GPTs available online (data size, cost of use etc). 

In the limited time of this assignment, please: 

- Ask to obtain a summary of the lesson. Don't by shy to specify that you are a beginner (if it is the case!) and that you may need a summary without a lot of technical terms.   
- Focus on specific aspects to ask further clarification: 
	- You can start by asking about things you are more familiar with or more curious about: how can you use a GPT for working with historical sources? 
	- Explore technical specifications and requirements that are necessary for configurating your own environment (this is the object of the lesson)
	- Ask for further explanations about things you might ignore or not have insufficient knowledge of. Technical terms are one such domain. A GPT could help you clarify things that a lesson cannot necessarily cover, since it focuses on one domain. 
	- Ask how you should prepare your corpus (format etc): these things can be frequently overlooked or taken for granted, but now you have a GPT ready to answer all your questions.   

For your prompts: 

- Make sure that you give concise and clear instructions 
- Ask one thing at the time and avoid long and complicated phrases

Ask a maximum of five questions (for this assignment) so that you have time to process the answers. What do you observe? 
- Did you find the information you were looking for? 
- How do you judge the value of the answers? 
	- if you did not know a lot when you started, do you feel empowered to go further? 
	- if you had some knowledge about GPTs, do you feel you learned something useful that you might be able to apply?     

## Apply digital source criticism to images generated with AI  

Photos generated with the prompt: "historienne qui travaille avec des sources historiques" on the 29th of April 2024 using the service [Picsart](https://picsart.com/create) but in French. 

Cite an image generated with AI: 
Instructions following the APA citation style: [https://library.senecapolytechnic.ca/apa/artificialintelligence](https://library.senecapolytechnic.ca/apa/artificialintelligence) 

