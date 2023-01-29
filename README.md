# KDD
# Introduction

In this experiment, we have applied  the  pre-trained zero-shot model (https://joeddav.github.io/blog/2020/05/29/ZSL.html), and the supervised alogorithms such as Support Vector Machine, Naive Bayes, Random Forest, and Decision trees in the context of topic prediction for the digital forensic data. We have applied cluster based approach to preprocess the input data in order to improve the performance of the zero-shot model. The zero-shot is robust against the unseen class and the unseen text because it can predict the topics in unseen data without any training.  The API of the zero-shot is publicly avaible at : https://huggingface.co/zero-shot/ 



# Packages need to be installed


!pip install -U sentence-transformers!


!pip install sentence_transformers

!pip install transformers

!pip install datasets

!pip install stop_words

!pip install scipy 

!pip install https://github.com/scikit-learn-contrib/scikit-learn-extra/archive/master.zip


# Data 

1. Reuters News Group Data is available in huggingface datasets https://huggingface.co/datasets/reuters21578 

2. Yahoo-Answers-Topic Data is available in  huggingface datasets https://huggingface.co/datasets/yahoo_answers_topics

3. Forensic Data: 
    Gmail: For the Gmail text we have used Android Gmail Conversations.csv file which is available at: 
    
    https://drive.google.com/drive/folders/16mKUq5BWX_hWTl2hHmEeMChwweVnYrmg
    
    
    
    
    Facebook: Here we have used Facebook Posts.csv file which is available at:
    
    https://drive.google.com/drive/folders/1g0pVIlNti1eVoG4AEC4Qr8ADWC69ChZq
    
    
    
    Twitter: Here we have used Twitter Tweets.csv and Twitter Direct Messages.csv files that are available at:
    
    https://drive.google.com/drive/folders/1g0pVIlNti1eVoG4AEC4Qr8ADWC69ChZq


# Code:


Supervised Algorithm Comparison Application: To exceute for Reuter data in Code folder please run the notebook named Zero-Shot_vs_Supervised_Reuters_Data.ipynb, and to exceute for Yahoo-Answers-Topic data in Code folder please run the notebook named Zer-Shot_vs_Supervised_Yahoo_Data.ipynbnb. In the notebook, to run the application execute the cells in ordert.  

The codes can be accessed using the Google Colab Link.

Google Colab Link Reuters : https://colab.research.google.com/drive/1Hqae1Ytk5OepoxOgzlfCZiHf2vXyD7xz?usp=sharing

Google Colab Link Yahoo-Answers-Topic : https://colab.research.google.com/drive/19ulDvFEdwjvB3xfxaVwmwI7SILc4gmsE?usp=sharing



Reuter Data based Cluster Application: To execute the code using Reuters in Code folder please run the notebook named Zero_Shot_Reuters_Data_Appliccation_.ipynb. In the notebook, to run the application execute the cells in ordert.  

The code can be accessed using the Google Colab Link. Google Colab Link: https://colab.research.google.com/drive/1kdwkfij05ZxN50v6eOTiWGjUyavR0--0?usp=sharing


Yahoo-Answers-Topic Data based Cluster Application: To execute the code using Yahoo-Answers-Topic in Code folder please run the notebook named Zero_Shot_yahoo_answers_topic_Data_Appliccation_.ipynb. In the notebook, to run the application execute the cells in ordert.  

The code can be accessed using the Google Colab Link. Google Colab Link: https://colab.research.google.com/drive/1-nvlGVyfZH5tQDS-mXPKWejJU2Ts4v9h?usp=sharing


The code of the Unsupervised Text Classification can be accessed: https://colab.research.google.com/drive/1rJ9HazsH34RbPKcSKqZFuDx2ASiTb35I?usp=sharing





