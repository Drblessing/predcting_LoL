# predcting_LoL
 
 © 2021, Daniel Blessing, All rights reserved.
 
 League of Legends is the world's most popular Esport, with billions of dollars gambled on it per year. 
 
 How well can we predict League of Legends games before they happen with machine learning?
 
 This is clearly an important topic to help tune prediction markets as well as focus coaches time on the most important features. 
 
 An investigation on this topic by me, Daniel Blessing, a data science masters student at the [University of San Francisco](https://www.usfca.edu/)
 
 ## Data
 
 [League of Legends Data](https://www.kaggle.com/chuckephron/leagueoflegends)
 
 The data used was all League of Legends competitive matches between 2015-2017. 
 
 Many features are present, including red champs, blue champs, minute resolution gold difference, bans, players, teams, etc.
 
 There are approximately 7620 competitive matches in the dataset. 
 
 ## Project 
 
 ### EDA
 - Blue team has won 54% of the games
 - The number of bans has changes from 3 to 5 
 
 ### Feature Cleaning
 - String cleaning of categorical variables
 
 ### Algorithms & hyperparameter search
 - Random Forest Classifier
 - Logistic Regression

### Evaluation Metrics 
- Accuracy
- f1_score

### Results
- Able to predict the next game with 52% accuracy not including teams

 
