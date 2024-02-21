# Capstone-Project-20.1-Initial-Report-and-Exploratory-Data-Analysis-EDA-
Using Differnt Regression Models to Predict ASO toxicity

Goal: The goal of this project is to identify more effective algorithms to predict antisense nucleotides (ASO) toxicity based on their sequence features. We will be training several linear regression models without regularization or with regularization (L1 and L2) to predict ASO toxicity based on the linear combination of their sequence features. We will used the new models to identify the features which most effectively enhance the accuracy of predicting whether a ASO is toxic or not.

Data Problem: The data task is to train and tune multiple linear regression models with or without regularization to predict the toxicity score of ASOs based on their sequence features.

Expected Results: The expected results would be several models using linear combination of some selected sequence features from an antisense oligonucleotide (ASO) to predict its toxicity. The prediction results are continuous and not binary, but we can choose different thresholds to define a toxic ASO versus a non-toxic ASO and convert the result to binary labels. Then we can use confusion matrix or receiver operation curve (ROC) to compare the performance of different models. In the original paper, a linear regression model is published for this purpose and my goal is to reproduce the authors’ key results by building a similar or even better models.

Data: The data is a from published literature vy Roche in 2022.

Link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9221153

This paper has a supplementary table which contains 1,800 antisense oligonucleotides sequences and their performance in a calcium assay. Among these 1,800 antisense oligonucleotides, 10% of them were also tested in animal experiment with reported toxicity score.

Importance My research question is important because big pharmaceutical companies like Roche, Biogen, Eli Lilly can spend >100 millions of dollars in developing genetic medicine (e.g. ASO) to treatment human disease. Currently, they rely on animal experiments and empirical evidence to determine the toxicity of an ASO. It is expensive and also time consuming. The capability to design a ASO without potential toxicity can streamline the whole drug development process and can create real values for these pharmaceutical companies. It is super important to figure out the sequence features within an ASO which can predict its toxcity.

Conclusions:
