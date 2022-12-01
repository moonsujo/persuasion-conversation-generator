# ACGenV: Automated Conversation Generation & Evaluation

This repository stores all code used for our project in CS544 Fall 2022. 

There are two main elements: 
 - conversation-generator*
 - conversation-analyzer

*the model(s) used in the conversation-generator were not able to be uploaded entirely to GitHub due to their large size and can be made available through a Google Drive link upon request.

There are also two evaluation models:
 - Perplexity
 - BLEU Score

BLEU scores are generated wrt subsets of the original PSG dataset, and are compared to both of our generative conversational models' output. Details of the implementation can be found in the bleu_scores folder.