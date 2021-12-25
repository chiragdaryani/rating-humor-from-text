## Code Files

* `Models_bow_features.ipynb` : All Machine learning models built on Bag of Words (BoW) features.

* `Models_tfidf_features.ipynb` : All Machine learning models built on TF-IDF features.

* `Models_word2vec_features.ipynb` : All Machine learning models built on Word2vec features.

**All the jupyter notebooks mentioned above were created on Google Colab.**


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


**Note:** Since we created these code files on Google Colab, we were provided by a lot of these machine learning libraries by default. So if you are executing the code on Colab, you won't need to install these libraries. Any additional library that is not present in colab's default environment, code for installing such libraries has been added in the notebook itself. For e.g. `gensim` package is not provided by default. So we have added the code to install gensim, e.g. `!pip install gensim` in the notebook itself.


## Instructions

* To run this code on Google Colab:

1. Download the repository as a zip file.
2. Extract the zip to get the project folder.
3. Upload the 3 ipynb files to google colab
4. Upload the dataset to your google drive in a folder called "dataset"
5. Execute the notebook cell by cell.

Note: If you face any path error while executing a cell, it may be because your "dataset" folder is not in the path "gdrive/My Drive" . So please keep the folder in this base path or change the path in the notebook cell accordingly.


## References

https://stackoverflow.com/questions/14007545/python-regex-instantly-replace-groups

https://stackoverflow.com/a/5843547/4084039

https://stackoverflow.com/a/47091490/4084039

https://towardsdatascience.com/xgboost-fine-tune-and-optimize-your-model-23d996fab663

https://github.com/n-hossain/semeval-2020-task-7-humicroedit

https://github.com/cooper62498/SI630_Final/blob/master/cselig_si630_final_humor_detection.ipynb

https://github.com/JackyLin97/2020_NLP_Funniness_Estimation-PyTorch/blob/master/subtask-1/code/Funniness_Estimation.ipynb

https://github.com/leahannah/uniTuebingenCL/blob/master/humor_regression.py
