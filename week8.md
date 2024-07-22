---
layout: post
title: Week 8
author: Krystal Foster
---

This week we were tasked with finalizing our corpus. As a group we went through all of the utterances and definintions for the terms that pertain to Trustworthy AI just to make sure that the utterances and what they were asking, actually made sense in relation to the answer given. After finalizing the corpus we then started adding the information from the corpus to our chatbots. Since my framework is Botpress and Botpress works a bit differently (more of a conversational flow) I had to figure out how I wanted the conversation between the end user and TrustBot to flow. I created a flowchart mockup using good notes on my iPad so I could go into creating the flow in Botpress.

I started creating intents and for the different definitions and entering the different utterances for each. This allows for the machine to have a better understanding of the different ways people may ask for one thing. I created a CSV document that had the terms and their definitions and I connected this table to my knowledge base to answer the questions about Trustworthy AI. I ran into some roadblocks along the way where at first when I tested my chatbot and I would ask it questions it would restart each time to the greetings node instead of continuing to the next node. But I realized that I had used the wrong feature( I was using the knowledge agent feature instead of the capture card). After fixing this I have a fully functional chatbot(TrustBot) based on the information it is trained on.


[Back](./)
