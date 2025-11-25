---
title: Introduction to digital history - games and Twine
author: Sofia Papastamkou
date: 2025-11-24
---


## Learn to use Twine 

[Twine](https://twinery.org) is an open source interactive game creato software. 

*Programming Historian* lesson
Gabi Kirilloff, "Interactive Fiction in the Humanities Classroom: How to Create Interactive Text Games Using Twine," Programming Historian 10 (2021), https://doi.org/10.46430/phen0095

Video tutorial: 
Mel Frances / Modern Art Oxford. "Twine for Beginners: How to create an interactive story online". YouTube video. 11 March 2022. https://youtu.be/lhn39SPETMM?si=_cH6ORMgE25GApAt

## Assignment - hands on with Twine

Use the online version of Twine available here: [https://twinery.org](https://twinery.org/). 

Choose `Use in your browser`.

Go to the website: [Minett Stories. Remixing Industrial Pasts in the Digital Age](https://minett-stories.lu/). The project focuses on the industrial history of Luxembourg through a micro-history of the Minett region. Among the historical materials and sources, you will find four graphic novels. You can use the scientific texts that accompany the graphic novels, written by historians, to build a scenario for a game with the help of a generative pretrained transformer. 

* Irene Portas Vázquez. When Italian communists inhabited the Minett. Minett Stories. https://minett-stories.lu/en/story/when-italian-communists-inhabited-the-minett 

* Jens van de Maele. Steel, smoke and dust. Minett Stories. https://minett-stories.lu/en/story/history-of-air-pollution 

* Jens van de Maele. Dr Musel looks at dusty skies. Minett Stories. https://minett-stories.lu/en/story/history-of-air-pollution-2 

* Julia Harnoncourt. Brothers in exile. Minett Stories. https://minett-stories.lu/en/story/brothers-in-exile  

Pick a generative pretrained transformer of your choice. It is better if you work connected to a personal account. 

You might need to copy paste the text of the web page using the dialog box of the gpt or provide (attach) a file with the copy pasted text.

Use the following prompt:  

- Read the attached text
- Draft a storyboard for a game of 30 minutes
- The storyboard must be built around 3 questions based on this text. Each question should offer 2 choices. Conceive these questions as paths to go further in the game. 


You will obtain a scenario for a game as output. If you are happy with it, use it to build a game on Twinery following the instructions you found in the Programming Historian lesson or the video tutorial. 

### Example of output from Claude AI

Input text: Irene Portas Vázquez. When Italian communists inhabited the Minett. Minett Stories. https://minett-stories.lu/en/story/when-italian-communists-inhabited-the-minett 

#### **Twine Storyboard: "Crossing Borders - A Communist Courier in the Minett, 1929"**

#### **Setup:**
Player role: Luigi, an Italian migrant worker and communist sympathizer in the Minett region, 1929

#### **PASSAGE MAP (10 nodes total):**


**NODE 1: START - "The Package"**
*Text:* 
"Esch-sur-Alzette, March 1929. You're Luigi, an Italian worker at the Rodange factory. Your comrade hands you a package wrapped in oilcloth—copies of *Il Riscatto* smuggled from Brussels. 'These need to reach our cell in Villerupt tonight,' he whispers. 'Police patrols have increased.' Your shift ended an hour ago. You're exhausted, but the newspapers must get through."

**QUESTION 1: How will you transport the newspapers across the border?**
- **Choice A:** "Through the mine galleries" → GO TO NODE 2
- **Choice B:** "Through the forest path near Rumelange" → GO TO NODE 3



**NODE 2: "Underground Route"**
*Text:*
"You descend into the Heintzenberg mine after hours. The interconnected galleries cross beneath the border—iron ore and ideas travel the same paths. The air is damp and cold. Halfway through, you hear voices echoing. Are they miners working late or police conducting a search?"

**QUESTION 2: What do you do?**
- **Choice A:** "Hide the package and pretend to be a lost worker" → GO TO NODE 4
- **Choice B:** "Push forward quickly through a side gallery" → GO TO NODE 5



**NODE 3: "Forest Meeting"**
*Text:*
"You take the woodland path where the cell holds secret meetings. The March evening is cold. As you approach the border marker hidden among the trees, you spot two figures ahead—are they comrades or police informants? The fascist associations have spies everywhere."

**QUESTION 2: What do you do?**
- **Choice A:** "Whistle the recognition signal" → GO TO NODE 6
- **Choice B:** "Wait and observe from the shadows" → GO TO NODE 7



**NODE 4: "ENDING - Detained"**
*Text:*
"The voices belong to Luxembourg police officers. They find *Il Riscatto* hidden in your jacket. Within a week, you receive an expulsion order. Like 252 other Italians in 1929, you must leave Luxembourg. Your family stays behind. The network continues without you, but your role in it ends here."

*Historical note: Immigration laws were used extensively to expel communist militants.*



**NODE 5: "ENDING - Successful Delivery"**
*Text:*
"You emerge on the French side. Your contact in Villerupt receives the newspapers—they'll be distributed at the factory tomorrow. 'The proletarian strength resides in its organisation,' he reminds you. You've kept the network alive for another week, but you know the risks grow daily."

*Historical note: Cross-border mine galleries were crucial for smuggling communist propaganda.*



**NODE 6: "Recognition"**
*Text:*
"Your whistle is answered correctly. The figures are comrades from the Longwy cell. They've brought funding collected by the International Red Aid for families of expelled militants. Together, you cross into France safely."

**QUESTION 3: At the Villerupt meeting, what do you discuss?**
- **Choice A:** "Organizing a May Day demonstration despite the ban" → GO TO NODE 8
- **Choice B:** "Creating more clandestine cells inside the factories" → GO TO NODE 9



**NODE 7: "ENDING - Close Call"**
*Text:*
"From the shadows, you recognize one figure—a fascist spy from Caffé Piccioni in Esch. The second is a French gendarme. You retreat silently, taking a longer route. The newspapers reach Villerupt by dawn, delivered through another comrade's mine route. You've survived, but the Opera Bonomelli's cooperation with police grows stronger."

*Historical note: Fascist organizations collaborated with Luxembourg authorities to monitor communists.*



**NODE 8: "ENDING - The Demonstration"**
*Text:*
"May 1st, 1931: Despite the ban, 200 workers march through Esch carrying banners reading 'Higher Wages' and 'Against the Immigration Law.' Police block the route, but the demonstration makes the front page of *Il Riscatto*. Some comrades receive expulsion orders, but the movement gains visibility. You've chosen open resistance over secrecy."

*Historical note: Communist May Day demonstrations did occur despite government bans.*



**NODE 9: "ENDING - Building the Network"**
*Text:*
"Over the following months, new cells emerge in Dudelange's rolling mill and Collart mine. When the 1929 crisis hits and factories cut to four-day weeks, your network is ready. You distribute tracts condemning 'mass expulsions' and wage cuts. The long arm of the law eventually catches up—but not before the seeds are planted."

*Historical note: The 1929 crisis led to partial unemployment and mass expulsions of foreign workers.*


**STRUCTURE SUMMARY:**
- **3 Questions** with binary choices
- **6 possible endings** (nodes 4, 5, 7, 8, 9)
- **10 total passages**
- **Average playthrough:** 4-5 nodes
- **Build time:** 30 minutes (simple linking, minimal formatting needed)

**Learning Objectives Met:**
✓ Non-linear narrative (multiple paths)
✓ Meaningful choices with historical consequences
✓ Different endings based on decisions
✓ Practice creating links between passages


## Final class assignment

This assignment was conceived by Eliane Schmid. 


Create a game that has an educational value: 
-	Your audience/ the players should learn something about a historical event
-	Your audience/ the players should be challenged to think critically when they choose different paths in your game
-	Your audience/ the players should be able to recognize an argument/ a research question 

Your game should be based on:
-	at least 5 primary sources (newspaper articles, photos, primary literature, etc.)
-	at least 3 secondary sources (at least one about the theory of games, and 2 about the topic you are narrating in your game)

AI/ LLMs:
-	You are allowed to use an LLM of your choice to write the storyboard but you do not have to. 
-	Double check that the facts which you researched are not distorted when you use the LLM for narration purposes. 
-	Take a screenshot of the questions you asked the LLM to help build your storyboard.
-	Disclose what LLM you used and how you used it for the purpose of your game creation process. 

Citations:
-	As in any paper or assignment you are writing in history, properly cite your sources (any citation style is fine, as long as you are consistent)
-	For practical purposes, apply in-text citations in your games. 


Formal Aspects:
-	Your game should have between 10-15 branches
-	Each branch should contain information about your topic in full sentences (min. 100 words)
-	Please write full sentences for your links/ questions/ choices


Grading Criteria:
-	Formal aspects adhered to
-	Proper citations
-	Min. 5 primary sources and min. 3 secondary sources of good scientifically sound quality – sound research
-	Clear argument
-	Creativity
-	Educational value – Have you thought about your audience?

