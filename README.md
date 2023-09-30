# Titanic Exploratory Data Analysis (EDA)   

![image](banner.jpg) 
This project focuses on conducting data cleaning and exploratory data analysis (EDA) on the Titanic dataset.The Titanic dataset is a well-known dataset that provides insights into the demographics and survival rates of passengers aboard the Titanic. 

## DATA UNDERSTANDING  

The datasets is obtained from Kaggle: [Titanic](https://www.kaggle.com/c/titanic/data)   
 
The dataset contains 891 rows (entries) and 12 columns    
The columns are:       

``PassengerId``: Unique identifier for each passenger.    
``Survived``: Binary variable indicating survival (1 = Survived, 0 = Did Not Survive).    
``Pclass``: Ticket class (1st, 2nd, 3rd class).     
``Name``: Passenger's name.    
``Sex``: Gender of the passenger.      
``Age``: Age of the passenger.     
``SibSp``: Number of siblings/spouses aboard.     
``Parch``: Number of parents/children aboard.     
``Ticket``: Ticket number.    
``Fare``: Passenger fare.    
``Cabin``: Cabin number.        
``Embarked``: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)       

## EXPLORATORY DATA ANALYSIS 
### Univariate Analysis
Univariate analysis is a data analysis technique that focuses on examining and describing the characteristics and distribution of a single variable in a dataset. In this project, I performed univariate analysis on various variables in the Titanic dataset, including:

* Histograms for age distribution.
* Bar plots for passenger class distribution.
* Pie chart for survival rate.

### Bivariate Analysis
Bivariate analysis explores relationships between two variables in the dataset. In this project,I  investigate relationships such as:

* Scatter plots for age vs. fare.
* Bar plots comparing the number of survivors by passenger class.
* Box plots comparing fares by passenger class.
* Correlation heatmap between age and fare
### Multivariate Analysis
Multivariate analysis extends the exploration to multiple variables simultaneously.I used techniques like parallel coordinates plots to visualize relationships between multiple variables and survival.  
## Insights and Conclusions
* $59.4$ % of people did not survive while $40.6$ % percent survived.
*  There is a relatively smaller number of children (around 5-15 years old) and elderly passengers (above 60 years old) on the Titanic
* Passengers in Class 1 had a higher chance of survival compared to those in Class 2 and Class 3. This suggests that the passenger class might have influenced the survival rate
* Class 3 had the highest number of passengers but the lowest survival rate, indicating a potential class-based hierarchy in rescue efforts
* Survived and Fare: There is a positive correlation between "Survived" and "Fare," suggesting that passengers who paid higher fares had a higher chance of survival.
* Age vs. Survived: there might be a slight concentration of younger survivors.

AUTHOR:          
marwa Osman: marwaosman9975@gmail.com    

👉 [LinkedIn](https://www.linkedin.com/in/marwa-osman-00190b222/)

👉 [GitHub](https://github.com/marwa9975)