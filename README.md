# IMDB-sentiment-annalysis
word2vec 

For this project,especially in the python script, I am going to build a machine learning model, Naive Bayes for prediction on sentiment of movie reviews when I'm using Bag of words technique. On the other hand, I'm using Word2Vec to build up a vocabulary with simliarity between words, and by using Gradient Boosting Classifier, the model output the review as 1/0 for a postivie and negative review.

## Getting Started

data sets:
labeledTrainData.tsv : 25,000 reviews with labels of “1” or “0” ( positive /negative reviews)
testData.tsv: 25,000 reviews need to be predicted
unlabeledTrainData.tsv : 50,000 reviews without labels


### Prerequisites
some packages have to be installed before running the code ( Machine learning packages, word2vec,etc)


### Installing

for installtion of packages, just simply type " import packagename" on jupyternotebook, which are already included in the py notebook.
if the packages are not ready, you would need to use your computer's terminal command by typing 

conda install packagename

for example, the package of gensim for word2vec could be installed by typing 

conda install gensim


## Acknowledgments

Visualize word vector with t-SNE : Jeff Delany , 2017 https://www.kaggle.com/jeffd23/visualizing-word-vectors-with-t-sne
