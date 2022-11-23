##Angry Tweeter
Name of Project: Anger Classification Project...
Purpose of Project: To train an emotion classifier to identify different levels of anger. There will be 4 to 6 levels of anger. 
Data sources for training stage: "Gutenberg" - a corpus of 2000 books we extracted from project Gutenberg
Data sources for inference: Twitter extrated via Twint - as we want to identify engagement metrics... 

Main project questions (or hypotheses if appropriate) 
1a) Does Twitter amplify anger? 
1b) More specifically? What is the relationship between engagement metrics and anger while controlling for other variables... 
  - 
  
#High Level Project Workflow
1) Generate an anger classification dataset using NLTK - store in X folder... 
2) Train emotion classifier on text dataset extracted from Gutenberg books (2000 book corpus) 
3) Save model to folder 
4) Extract tweets using Twint - dataset will have two purposes: inference for classifier - engagement ML workflow  
5) Clean dataset (english only tweets) - generate features from Twint output 
6) Load angry classifier -> run on tweets extracted from Twint
7) Generate tweet dataset with anger score (two variables: tweet and anger score) 
8) Merge tweet and anger score dataset back with Twint output (engagement ML workflow) 
9) Use ML workflow to understand the contribution (or not) of anger to engagement metrics

Definitions 
ML workflow: Workbook uses various machine learning techniques on a binary variable response rate 
Gutenberg: A series of datasets we extracted from "Project Gutenberg" - there are two main data extractions a 1000 book repository and a 2000 book repository.

