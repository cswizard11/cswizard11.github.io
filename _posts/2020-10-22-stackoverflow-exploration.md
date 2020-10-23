---
layout: post
title: Stackoverflow Exploration
subtitle: An eploration of a Stackoverflow data dump
cover-img: /assets/img/stackoverflow.jpg
thumbnail-img: /assets/img/qa.png
share-img: /assets/img/qa.png
---

##### For my project, I found this great little data set from Stackoverflow. It's a data dump of 250,000 answers to questions, with 11 different variables about those answers. One of those is the number of upvotes the answer got. Looking at that, I came up with an intriguing and useful research question.



# Research question:
### Is there a relationship between any of these vairables and the answer score? If so, what can I change about my question to increase my chances of getting a better answer?

Looking at the variables availible, the one that stands out to me the most is the score of the question. It would make sense that a question with a lot of upvotes would get an answer with a lot of upvotes. But does the data agree that there is a relationship between the two? Here's a graph to answer that question.

![Graph 1](/assets/img/qa.png)

So, is there a relationship here? Well maybe, but certainly not a linear one. The line of best fit bewteen these points is nearly flat, and the model I made shows it only accounts for 4.5% of the variability in the data. So it would seem my initial assumtion was wrong. However, I wanted to know if there was a realtionship between any of these variables, not just the question score. So I ran through every combination variables to find the best model. And what I found was very disappointing. The model incorporated 6 different variables, yet only accounted for 6.3% of the variability. To answer my research question, it would seem there is not a relationship, at least a linear one, between any combination of variables and the answer score.

Well I'd hate to come up with nothing from this data set, so I took a look to see if any two variables were related. And the answer is kind of.

![Graph 2](/assets/img/qvqs.png)
