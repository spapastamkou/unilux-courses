---
author: Sofia Papastamkou 
date: 2024-12-04
title: Distant reading - an introduction
---

The session offers a theoretical introduction to the concept and the practice of distant reading based on Franco Moretti's articles. 

Then the students are invited to explore texts with the help of [Voyant Tools](https://voyant-tools.org/), a web-based reading and analysis application for digital texts. It is also possible to expriment with Communalytic (see assignments below).  

## Assignment 1 - Distant reading a speech with Voyant Tools 

You are going to work with the following text: 

Winston Churchill, ["The Sinews of Peace" ('Iron Curtain' Speech)](https://www.nationalchurchillmuseum.org/sinews-of-peace-iron-curtain-speech.html), 5 March 1946. 

The link below points to the source text. Your group will work directly with the text data that are provided in two files.

[File 1 of the 'Iron Curtain' Speech](/assets/data/churchill-19460305-v0.txt)

[File 2 of the 'Iron Curtain' Speech](/assets/data/churchill-19460305-v1.txt)

Half of the group will work with file 1 and half with file 2. Each sub-group, please go to [Voyant Tools](https://voyant-tools.org/). Copy paste the data as suggested in the interface and reveal. 

First explore the visualizations and try to understand what they show you (in sub-groups). 

1. Explore the word cloud (cirrus), the list of terms, and the links (on top left). What do you notice about the insights you obtain and how would you interpret them? Can you think of ways of using this kind of visualizations and lists?

2. Explore the contexts and collocations (on the bottom right). What do you notice about the insights you obtain and how would you interpret them? Can you think of ways of using this kind of visualizations and lists? 

Then, the whole group compare the word clouds that each sub-group obteined following the data file it used. Do you notice any differences?

Finally, please note your impressions about deconstructing and distant reading the text of the speech. Focus on three main ideas and try to imagine how you could use such type of reading in your own work.     


## Assignment 2 - Distant reading press articles on Brexit with Voyant Tools

You are going to work with the following corpus: 

Selected articles from the British Press regarding Brexit (2016), the withdrawal of the United Kingdom from the European Union. [Details about how the corpus was created are available in the lesson of Programming Historian](https://programminghistorian.org/en/lessons/interrogating-national-narrative-gpt#dataset) that we already used in a previous course on generative artificial intelligence. The file available below contains only part of the initial data.  

[File of Brexit articles data](/assets/data/brexit-articles-small.txt)

Please go to [Voyant Tools](https://voyant-tools.org/). Copy paste the data as suggested in the interface and reveal. 

1. Explore the word cloud (cirrus), the list of terms, and the links (on top left). What do you notice about the insights you obtain and how would you interpret them? Can you think of ways of using this kind of visualizations and lists?

2. Explore the contexts and collocations (on the bottom right). What do you notice about the insights you obtain and how would you interpret them? Can you think of ways of using this kind of visualizations and lists? 

Finally, please note your impressions about deconstructing and distant reading the corpus of articles. Focus on three main ideas and try to imagine how you could use such type of reading in your own work.

## Assignment 3 - Exploring social media (YouTube) data with Voyant Tools

Your group will work with comments extracted from the following audiovisual resource available on YouTube: 

Deutsche Welle Documentary. "Luxembourg: Poverty in Europe's wealthiest country". YouTube Video. 28:25 minutes. 30 April 2024. [https://youtu.be/d_XVU7VsG4Y](https://youtu.be/d_XVU7VsG4Y)     

[File of YouTube comments data](/assets/data/DW-documentary-poverty-luxembourg.txt)

Please go to [Voyant Tools](https://voyant-tools.org/). Copy paste the data as suggested in the interface and reveal. 

1. Explore the word cloud (cirrus), the list of terms, and the links (on top left). What do you notice about the insights you obtain and how would you interpret them? Can you think of ways of using this kind of visualizations and lists?

2. Explore the contexts and collocations (on the bottom right). What do you notice about the insights you obtain and how would you interpret them? Can you think of ways of using this kind of visualizations and lists? 

Finally, please note your impressions about deconstructing and distant reading the corpus of articles. Focus on three main ideas and try to imagine how you could use such type of reading in your own work. 

## Assignment 4 - Exploring social media (YouTube) data with Communalytic

Your group will work with the following audiovisual resource available on YouTube: 

Deutsche Welle Documentary. "Luxembourg: Poverty in Europe's wealthiest country". YouTube Video. 28:25 minutes. 30 April 2024. https://youtu.be/d_XVU7VsG4Y 

This short documentary on poverty in Luxembourg and available on the online social network YouTube has gathered more than 2 000 comments. Imagine that you are interested in working on the transnational perceptions of the poverty in Luxembourg, and that comments posted on online social networks are sources to you. You have the possibility, and the tools (specialized software or a programming language), to collect these comments in form of structured data, and apply various methods of analysis, including quantitative. 

### Alternative 1 - Collect the comment data yourself

For this exercice you can use [Communalytic](https://communalytic.org/), an easy-to-use online service even for total beginners. At least one member of your group should open a (free) account of EDU type (for teaching and learning). For this, you need to have a Gmail user account. Once you have signed-in, go to [My Datasets](https://edu.communalytic.org/datasets/) and click on the box YouTube/Comments. Let yourself be guided by the instructions that are displayed to start collecting the data. This involves naming your dataset and informing the URL of the video in the dialogue box. Launch the collect process. Once your dataset is ready, you get notified by email. Download your dataset as .csv file. Open it and inspect the data and metadata. 

Focus on tasks 3 and 4 of the following list. The task 4 focuses on distant reading the dataset with the help of the interface of Communalytic. 

1. Describe briefly the operation: source (the video), interest in collective sensibilities expressed in the comments, data collection using dedicated software 
2. Name the software you used, explain what it does and what its main features are
3. Explore the dataset you obtained (the .csv file with the exported data): what do the data look like, which categories of data you obtained, how you imagine using them?  
4. Explore the Dataset Overview, and browse the other types of analysis that are embedded in Communalytic: (Toxicity, Sentiment, Topic, Network Analysis). You can pick one or two to have time to inspect the results in detail. Explain the most important findings in your own words and describe in what ways these results are visualized and what they tell us.  

### Alternative 2 - Use the data file available in this repository

[Deutsche Welle Documentary YouTube Comments](/assets/data/DW-documentary-poverty-luxembourg.csv)

In this case, you still need to use Communalytic but instead of collecting the data, you are going to import them. 

Focus on tasks 3 and 4 of the following list. The task 4 focuses on distant reading the dataset with the help of the interface of Communalytic. 

1. Describe briefly the operation: source (the video), interest in collective sensibilities expressed in the comments, data collection using dedicated software 
2. Name the software you used, explain what it does and what its main features are
3. Explore the dataset you obtained (the .csv file with the exported data): what do the data look like, which categories of data you obtained, how you imagine using them?  
4. Explore the Dataset Overview, and browse the other types of analysis that are embedded in Communalytic: (Toxicity, Sentiment, Topic, Network Analysis). You can pick one or two to have time to inspect the results in detail. Explain the most important findings in your own words and describe in what ways these results are visualized and what they tell us. 






