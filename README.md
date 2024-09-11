### Chicago Food Safety Inspection Analysis
This project is part of the UChicago Applied Data Science program and focuses on promoting food safety in Chicago by analyzing failed food inspection data. It consists of three main parts:

**Part A: Identifying Top-10 Causes of Failed Food Inspections**

The goal is to identify the top-10 most frequent causes of failed food inspections and present the findings clearly. The dataset is sourced from the City of Chicago’s Health and Human Services.

**Steps:**
* Data selection and cleaning
* Parsing violation descriptions
* Visualizing the top-10 most frequent causes of failed inspections
* Trend analysis over 10+ years

**Part B: Token-Based Analysis of Violations**
Building on Part A, the focus is to identify specific tokens that lead to failed food inspections using various text processing techniques.

**Approach:**
* Tokenize the violation descriptions and inspector comments
* Remove stopwords, punctuation, and perform stemming and lemmatization
* Compare the top-10 tokens obtained through different text-cleaning techniques (Porter stemming, Lancaster stemming, lemmatization)
* Plot the most common tokens over time using the most effective technique

**Part C: Predicting Inspection Outcomes with a Classification Model**
In this part, we build a classification model that predicts the outcome of food safety inspections based on inspectors' comments.

**Approach:**
* Extract free-form text comments from the dataset
* Preprocess the text data using the most effective technique identified in Part B
* Build and compare at least two text classification models (binary or multinomial)
* Visualize and evaluate the model's performance
