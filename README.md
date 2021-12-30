# Towards an Automated System for Rating Humor Content in Textual Documents

## Task Description:

We are attempting the SemEval-2020 Task 7 (Assessing Humor in Edited News Headlines) Subtask 1 . 

In this task, we try to predict the mean humor rating for news articles that were edited by replacing a word in their original content. Our aim would be to develop a sentence-pair regression model that takes both the original news headline and the edited news headline as input and then outputs a prediction of a mean funniness rating in the range of 0 to 3 for each edited news article. The predicted real-valued scores would represent the humor content as following:
0 representing “Not Funny”, 1 representing “Slightly Funny”, 2 representing “Moderately Funny” and 3 representing “Very Funny”.

https://competitions.codalab.org/competitions/20970#learn_the_details-overview

## Description about the Dataset

We will be using the dataset called **Humicroedit** which was provided by the competition organizers. It was created by taking news headlines and making micro-edits i.e. replacing one or two words in the headline text in order to introduce humor in the news content. 

There are about 5,000 distinct news headlines, each having 3 edited versions, thus totaling about 15,000 records. The data is partitioned into 3 subsets, the Train Dataset with about 64% records, the Dev Dataset with about 16% records, and the Test Dataset with 20% of the records. 

The training data can be found in the file [train.csv](train.csv), the dev dataset file is named [dev.csv](dev.csv), and the test data with truth labels can be found in the file [truth_task_1.csv](truth_task_1.csv).

This complete dataset for the task can be downloaded from [this website](https://cs.rochester.edu/u/nhossain/humicroedit.html). 

## Code Files

* `Models_bow_features.ipynb` : All Machine learning models built on Bag of Words (BoW) features.

* `Models_tfidf_features.ipynb` : All Machine learning models built on TF-IDF features.

* `Models_word2vec_features.ipynb` : All Machine learning models built on Word2vec features.



## Dependencies

We have used the following 3rd party libraries in our code:

* `numpy`
* `pandas`
* `scikit-learn`
* `matplotlib`
* `seaborn`
* `nltk`
* `gensim 4.1.2`
* `xgboost`
* `scipy`


## Instructions

* To run this code on Google Colab:

1. Download the repository as a zip file.
2. Extract the zip to get the project folder.
3. Upload the 3 ipynb files to google colab
4. Upload the dataset to your google drive in a folder called "dataset"
5. Execute the notebook cell by cell.
