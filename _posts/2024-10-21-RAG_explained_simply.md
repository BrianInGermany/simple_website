---
layout: post
title:  "RAG: A Pictorial Explanation"
description: "Augment your model with company data"
---
What is Retrieval Augmented Generation? Allow me to broadly generalize and paint a picture on the virtual whiteboard:

![](/assets/images/rag_pres.gif)

### Case One
"Why is the sky blue?", our fictitious GenAI user asks. She submits her prompt to the AI model and is provided with a satisfactory answer shortly thereafter. Everybody's happy.

### Case Two
This time, you try yourself: "What is our process for onboarding a customer?". You submit your request to the same pre-trained model, but are disappointed to hear the model has "no idea" what you're talking about. Quite literally, the model, trained in 2022, has never heard of your nascent company, let alone your onboarding process. Bummer.

#### Enter RAG
Retrieval Augemented Generation means we are extending, or "augmenting" the generation the model is capable of by giving it additional information on which to execute its language skills. That extra information could be PDF files, but it could also be a connection to a company database or document management.

Voilá, "no idea" is history as the model flexes its muscles on the additional inputs provided. Final result: Acme Ltd.'s onboarding procedures are summarized to a tee, just the way you wanted.