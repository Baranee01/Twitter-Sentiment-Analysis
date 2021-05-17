# Twitter Sentiment Analysis

### INSTALLATION

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](http://seaborn.pydata.org/)
- [nltk](http://www.nltk.org/)
- [spacy](https://spacy.io/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/index.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

##
### EXECUTION

In a terminal or command window, navigate to the top-level project directory `Twitter-Sentiment-Analysis/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook Twitter Airline Sentiment Analysis.ipynb
```
or
```bash
ipython notebook Twitter Airline Sentiment Analysis.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser. You can also use [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) for easy access as it already has all the packages installed.

##
### ABOUT THE DATASET
Twitter data that was scraped from February of 2015 where there are tweets from various airlines and they are classified into three categories: - positive, negative and neutral. There are 14,641 tweets which are trained with the help of machine learning techniques and natural language processing. Each tweet is only 280 characters which allow people to use many shortcuts and are not in proper language processing.

Source : Kaggle

Link : https://www.kaggle.com/crowdflower/twitter-airline-sentiment

##
### SAMPLE DATASET
![image](https://user-images.githubusercontent.com/80042740/117542865-10b6ba80-b038-11eb-8087-a5bd6178aac8.png)

##
### FLOW OF THE PROJECT
- **Data Loading** : US Twitter Airlines Dataset is imported.
- **Data Exploration** : Exploring the data and the variables present to have better understanding  of the data.
- **Data Cleaning** : NLP techniques like Removing links, hashtags and mentions, special characters, stop words, Stemming and Lemmatization are used.
- **Model Building** : Dataset is split into training and test set. Decision Tree, Random Forest and Support Vector Machines models are implemented for training the dataset.
- **Results and Analysis** : Accuracy and Classification report for both the models are generated. They are compared and best model is obtained.
