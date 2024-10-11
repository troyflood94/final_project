# final_project
Group 5 Final Project
In this project we set out to test which type of machine learning model was best for predicting loan defaults.  Here we sourced banking data from Kaggle (see referenced link) and converted it into a Pandas Dataframe.  From there we created our training and testing data sets as well as applied a standard scaler to the data.  We evaluated the performance of 4 variations of machine learning models.  The models here are Random Forest, KNN, Kerras deep learning, and Logistic Regression Models. All four results yielded about 91% accuracy overall but were giving us a lot False Negatives.  
The accuracy being uniform seemed strange, we looked deeper and noticed that in our data about 91% of the target results were 0. From there we were able to conclude our model was predicting 0 everytime and 
Data Source-"https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter?select=application_data.csv"
