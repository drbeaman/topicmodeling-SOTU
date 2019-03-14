# NLP Topic Modeling the State of the Union

## Overview
This is a Natural Language Processing (NLP) Topic Modeling exercise intended to visualize the most relevant words and topics on every U.S. State of the Union speech from George Washington in 1790 to Donald Trump in 2019.  Original data can be found on [Kaggle]:(https://www.kaggle.com/tathor/state-of-the-union-address-texts/version/1).  Using Python pandas, numpy and other modules, I brought the data in to Jupyter Noteook, inserted the text into a dataframe for data analysis later, and then converted the text column of all documents merged together, into a list.  The list of 224 documents, known as the "corpus" is the format necessary for the topic modeling algorithms to run.  
All topic modeling algorithms are similar in that they need to convert the entire corpus into numbers.  Since I wanted to run different algorithms, I chose the sklearn module, whose visualizations can be a little more basic, but it offered multiple algorithms for me to try.  I used the Latent Dirichlet Alloction [LDA]: , Non-Negative Matrix Factorization [NMF], and Singular Value Decomposition [SVD]: (https://en.wikipedia.org/wiki/Singular_value_decomposition) packages, in order to see what the initial results looked like.  The algorithms train and fit the data automatically, so the immediately output renders the results two word count and word frequency.  The probabilities assigned Each algorithm weights word count and word frequency differently, returning results that favor one model over another.  In this case, since there are only 224 documents, the data size is relatively small, which means the NMF model produced better results than its more common counterpart, LDA.  I also ran an SVD model using Bokeh
NLP Topic Modeling on took the 224 text files of each State of the Union speech from 1790-2019, and 

* Data Preparation: Python modules: pandas, numpy and regular expression packages.

* Import a dataframe and keep the header, see the hint below.

* This time, return a count of vowels in each line of the poem.

* There are hints and starter code to help, but consult the [docs](https://spark.apache.org/docs/2.1.0/ml-features.html) when needed.

## DATA SOURCE
INSERT KAGGLE LINK.
* * This [stackoverlow post](https://stackoverflow.com/questions/29704333/spark-load-csv-file-as-dataframe) explains how to import a CSV file with a header.
# topicmodeling-SOTU
