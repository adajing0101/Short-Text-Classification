# Short-Text-Classification

[![School](https://img.shields.io/badge/UChicago-MSCA-red)]() [![Course](https://img.shields.io/badge/Course-MachineLearning-lightgray)]()  [![Contributors](https://img.shields.io/badge/Contributors-3-green)]()

Short-form text classification for Twitter data.

This is the repository for the final project for the Master's level Machine Learning course at The University of Chicago. 

## Project scope
Build a binary classifier that categorize a given Tweet based on whether or not it is referring to a real-life disaster event.

## Project motivation
The field of NLP has evolved rapidly in the past few years, leading to innovations across the analysis pipeline. Through this project, we aim to examine the improvement of these new techniques in applicatoin to a classic NLP dataset, disaster tweets.

## Anaysis framework

1. Data Source

[Kaggle Disaster Tweet Classification](https://www.kaggle.com/c/nlp-getting-started/overview)

2. Data Exploration

We used LDA topic modeling to cluster and identify key features of the disaster vs. non-disaster tweets.

2. Embedding

We explore the following embedding techniques:

    1. TF-IDF
    2. GloVe
    3. BERT sentence-level embedding
    
3. Modeling

We tested the following modeling options:

    1. Naive Bayes (baseline)
    2. SVM with linear/non-linear kernal (baseline)
    3. CNN
    4. Simple RNN
    5. RNN with LSTM
    6. Bert with max pooling layer
   
4. Fine-Tuning

For CNN and RNN arthitectures, we employed the strategies to find the optimized hyper-parameters:

    1. Random Search
    2. Hyperband
    3. Baysian
    
5. Conclusion

Overall, we found that the embedding in particular provided the highest performance boost with the lowest cost in efficiency. 


## Project members

Ada Jing [Github](https://github.com/adajing0101) ; [LinkedIn](https://www.linkedin.com/in/ada-jing/)

Dylan Zhang [Github](https://github.com/tb448479829); [LinkedIn](https://www.linkedin.com/in/bo-zhang-9180b912a/)

Rohit Satishchandra [LinkedIn](https://www.linkedin.com/in/rohit-satishchandra/)


