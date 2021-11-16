# MurderProject


## Project Summary
This project was created using a self-collected dataset via a Google Docs form. The main objective of my analysis was to answer the question: "Can you predict if office workers will want to return to the office after the COVID pandemic has subsided based on external factors?". The modeling I chose for this project was logistic regression in R utilizing R Studio.

## Data Cleaning Methods
This project required several things be changed in order to begin using the machine learning model:
* Updated column headers for clarity and ease
* Removed the timestamp column that Google automatically assigned as key values for each row
* Removed the UserID column as it was only relevant for the survey payment information



## Programs Used


## Modeling Techniques
Logistic Regression was used in this project as the data is all categorical. A combination of gbmImp, the marsModel and glm were utilized for feature selection. I additionally explored the Naieve Bayes method and a Decision Tree model but added the decision tree to my next steps of this project were I to take one.

## Analysis Methods
For the analysis, I utilized tabled confision matrix to show the number of accurately vs. inaccurately predicted categories. I also utilized a precision/recall graph for each model, I also utilized the precision, recall, f1 score and specificity to access all 3 versions of the model I showcased in my presentation.

![alt text](https://user-images.githubusercontent.com/50388830/123482298-3d139f80-d5c2-11eb-962b-e20addbc850c.png)




## References
Forte, R. M. (2015). Mastering predictive analytics with R. Packt Publishing Ltd.

