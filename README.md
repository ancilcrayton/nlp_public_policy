# Natural Language Processing: An Application in Public Policy

This repository contains the files used for the Natural Language Processing: An Application in Public Policy talk presented at [PyCon Ireland 2018](https://pyconie18.python.ie) by Ancil Crayton.

Slides to the presentation can be found [HERE](https://docs.google.com/presentation/d/1IPLswqilRDggx5I5tXdm0bqTqz39kSBdxq1-o2877Do/edit?usp=sharing).
## Purpose
In this talk, I aim to show an application of NLP to enhance public policy analysis. Specifically, we will focus on using text analysis for analyzing important documents and being able to provide both a qualitative and quantitative analysis.

If you are not familiar with public policy, you may be wondering exactly what I mean by publicy policy. In short, I am referring to any efforts taken by government authorities that may result in action, regulation, or laws related to aspects of societal well-being. From an academic perspective, public policy can nest many fields of the social sciences such as economics, sociology, political economy, and public management. This is the view I take in this talk. Hence, I make references to public policy as studying applications in these fields which can relate to the motivation behind, evolution of, or effectiveness of government policy. 

So, how can we use text analysis to aid in public policy analysis? Here are a few pointers for possible usages:
- Analyze historical government documents
- Understand evolution of ideologies through transcriptions of speeches
- Understand responses to public policy by analyzing social media
- Summarize collection of documents to find the most important topics related to a certain policy 

## What's covered?
In general, I cover basics of text analysis and the relevant tools in Python to perform this analysis. In more detail, we will briefly look at:

_Text preprocessing_: This is where we will clean text of extraneous information.  

_Feature extraction_: Transform raw text into numerical measures to feed into machine learning algorithms and perform regression analysis.  

_Topic modelling_: ML algorithms that can learn to summarize documents into "topics".  

_Regression analysis_: Statistical models that allows us to perform a quantitative policy analysis.  

_Tools_: We will cover basic tools within Python libraries such as gensim, nltk, scikit learn, wordcloud, and statsmodels.

## Requirements
The notebook provided in this repository was written in Python 3.6.

Dependencies can be installed by running the following command in the terminal:
`pip install -r requirements.txt` 
