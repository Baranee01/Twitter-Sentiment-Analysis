# Twitter Sentiment Analysis

Language Used : Python 3.8

Packages Used : numpy, pandas, seaborn, matplotlib, sklearn, nltk

##
### ABOUT THE DATASET
Twitter data that was scraped from February of 2015 where there are tweets from various airlines and they are classified into three categories: - positive, negative and neutral. There are 14,641 tweets which are trained with the help of machine learning techniques and natural language processing. Each tweet is only 280 characters which allow people to use many shortcuts and are not in proper language processing.

##
### SAMPLE DATASET
![image](https://user-images.githubusercontent.com/80042740/117542865-10b6ba80-b038-11eb-8087-a5bd6178aac8.png)

##
### FLOW OF THE PROJECT
1) **Data Loading** : US Twitter Airlines Dataset is imported.

2) **Data Exploration** : Exploring the data and the variables present to have better understanding  of the data.

3) **Data Cleaning** : NLP techniques like Removing links, hashtags and mentions, special characters, stop words, Stemming and Lemmatization are used.

4) **Model Building** : Dataset is split into training and test set. Decision Tree, Random Forest and Support Vector Machines models are implemented for training the dataset.

5) **Results and Analysis** : Accuracy and Classification report for both the models are generated. They are compared and best model is obtained.

##
### EXPLORATORY DATA ANALYSIS
![image](https://user-images.githubusercontent.com/80042740/117543030-bd913780-b038-11eb-9e10-c891741a25d8.png)

The tweets are classified as positive, negative and neutral where most of the tweets are negative (ie) People who travel in the airlines mostly had negative experience.

![image](https://user-images.githubusercontent.com/80042740/117543516-d4388e00-b03a-11eb-9a58-49879e674692.png)

Total number of tweets in each airline company are displayed. Here people mostly travelled in United Airlines and less travelled in Virgin America Airlines.

![image](https://user-images.githubusercontent.com/80042740/117543047-cb46bd00-b038-11eb-8fbe-672eb83a3687.png)

The tweets are classified into positive, negative and neutral for each airline company. In all the airlines, people mostly had negative experience.

##
### MODELS
Here models are built to predict the sentiment of people travelling in the airlines.

### Decision Tree
![image](https://user-images.githubusercontent.com/80042740/117543663-6345a600-b03b-11eb-9b7d-71b1f4bd5836.png)

Decision Tree model has predicted the results with an accuracy of 69%.

### Random Forest
![image](https://user-images.githubusercontent.com/80042740/117543671-6b054a80-b03b-11eb-9a85-88296880c7ee.png)

Random Forest model has predicted the results with an accuracy of 75%.

### Support Vector Machines
![image](https://user-images.githubusercontent.com/80042740/117543677-722c5880-b03b-11eb-9d77-d783e87d69fb.png)

Support Vector Machines model has predicted the results with an accuracy of 76%.

##
### RESULTS AND ANALYSIS
![image](https://user-images.githubusercontent.com/80042740/117543130-1d87de00-b039-11eb-85f2-7bdf50804fe6.png)

By comparing all the models, Support Vector Machines has performed well with an accuracy of 76%.

From all the above analysis we can conclude that, people mostly had negative experience during the travel. So based on the tweets, all the Airline companies must improve their customer experience.
