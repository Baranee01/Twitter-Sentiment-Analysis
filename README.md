# Twitter Sentiment Analysis

#### Language Used : Python 3.8
#### Packages Used : numpy, pandas, seaborn, matplotlib, sklearn, nltk

##
### ABOUT THE DATASET
Twitter data that was scraped from February of 2015 where there are tweets from various airlines and they are classified into three categories: - positive, negative and neutral. There are 14,641 tweets which are trained with the help of machine learning techniques and natural language processing. Each tweet is only 280 characters which allow people to use many shortcuts and are not in proper language processing.

![image](https://user-images.githubusercontent.com/80042740/117542865-10b6ba80-b038-11eb-8087-a5bd6178aac8.png)

##
### FLOW OF THE PROJECT
**Data Loading** : US Twitter Airlines Dataset is imported.

**Data Exploration** : Exploring the data and the variables present to have better understanding  of the data.

**Data Cleaning** : NLP techniques like Removing links, hashtags and mentions, special characters, stop words, Stemming and Lemmatization are used.

**Model Building** : Dataset is split into training and test set. Decision Tree, Random Forest and Support Vector Machines models are implemented for training the dataset.

**Results and Analysis** : Accuracy and Classification report for both the models are generated. They are compared and best model is obtained.

##
### EXPLORATORY DATA ANALYSIS
![image](https://user-images.githubusercontent.com/80042740/117543030-bd913780-b038-11eb-9e10-c891741a25d8.png)

![image](https://user-images.githubusercontent.com/80042740/117543036-c255eb80-b038-11eb-818b-73d47e2981dc.png)

![image](https://user-images.githubusercontent.com/80042740/117543047-cb46bd00-b038-11eb-8fbe-672eb83a3687.png)

##
### MODELS
### Decision Tree
![image](https://user-images.githubusercontent.com/80042740/117543183-5c1d9880-b039-11eb-8b0c-7de440b4035d.png)

### Random Forest
![image](https://user-images.githubusercontent.com/80042740/117543094-fe894c00-b038-11eb-8c42-d3d835a38216.png)

### Support Vector Machines
![image](https://user-images.githubusercontent.com/80042740/117543106-0a750e00-b039-11eb-8689-109842efe0df.png)

##
### RESULTS AND ANALYSIS
![image](https://user-images.githubusercontent.com/80042740/117543130-1d87de00-b039-11eb-85f2-7bdf50804fe6.png)

By comparing all the models, Support Vector Machines has performed well with an accuracy of 76%.
