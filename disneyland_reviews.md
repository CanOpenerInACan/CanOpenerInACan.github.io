# Disneyland Reviews 

---

This project used several different approaches to try to predict the rating tied to a review of one of three Disneyland resorts. The dataset included 42,000 reviews spread across the three different resorts, and had the rating given with the review (1-5 stars). There were several different methods used to try to predict the rating while using the review as an input to the model, and we wanted to find the best model for predicting the score, along with building the best model for predicting these scores in the future. Rather than just using one model and assuming it was the best, I wanted to test more methods and compare them to each other.


In trying to come up with the best way to predict the ratings, there are plenty of model types and ways of interpreting the data based on what you want to accomplish with the ratings. The models that I chose to try were sentiment analysis, using a tf-idf vectorizer to build a logistic regression model, a multinomial Naïve Bayes classifier, a decision tree and then a random forest. The most successful model that I built was surprisingly the logistic regression model, which returned an accuracy of 61%. 


The interesting aspect of this project was trying to figure out how exactly a company like Disney would be able to use this model and make decisions based on it. I discussed some interest in limiting the model into predicting a pass/fail system instead of a 1-5 star system, which would group 4-5 star reviews into passes, and anything less into fails. When employing this methodology, as expected the models performed a lot better and could easily group together the fails to figure out fixes to the problems and group together passes to make sure the good aspects stay good. 


This project provided a ton of insights into how a company can use data to both predict reviews as well as use and explore a set of data to its advantage. A lot of the business world can use reviews to explore strengths and weaknesses, as well as narrow down the reviews and find the information it needs to find for almost any situation. A lot of the value in reviews lies in the exploratory stage of the data and filtering the data down to the reviews you are interested in learning about and making decisions based on that segment of the dataset.


For the full write-up and code for this project, click <a href="https://github.com/CanOpenerInACan/DSC_Projects/tree/main/Disneyland%20Reviews">here</a>.
