#Titnic survival prediction
## Project Overview
This project predicts whether a passenger survived the Titanic disaster using machine learning techniques.

The goal is to perform:
- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Hyperparameter Tuning
- Model Evaluation

## Dataset
The dataset was collected from Kaggle(Titanic Dataset).


Data includes Features like:
- Passenger Class (Pclass)
- Sex
- Age
- Fare
- SibSp
- Parch
- Embarked

Target Variable:
- Survived (0 = No, 1 = Yes)
## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Project Workflow

### 1. Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Feature scaling where necessary

### 2. Exploratory Data Analysis
- Survival distribution
- Age analysis
- Gender-based survival analysis
- Passenger class analysis

### 3. Feature Engineering
- Created useful features
- Selected important variables

### 4. Model Training
Models experimented with:
- Logistic Regression
- Decision Tree
- Random Forest

### 5. Hyperparameter Tuning
Used:
- RandomizedSearchCV

### 6. Evaluation Metrics
- Accuracy
- f1 score
##Key learnings through EDA analysis:

• Most passengers were in the age groups 20–30 and 30–40, while there were fewer people in the 70–80 age group compared to the other groups.

• More than half of the passengers belonged to Pclass 3, i.e., greater than 50%.

• The majority of the passengers were men, accounting for more than 50% of the dataset.

• The majority of passengers boarded at Embarkation S, with significantly fewer people boarding at C and Q.

• Pclass 1 has the highest median fare, while Pclass 3 has the lowest median fare.

• Pclass 1 has a larger box compared to Pclass 2 and Pclass 3, which indicates that Pclass 1 fares are more varied, whereas fares for Pclass 2 and Pclass 3 are more consistent.

• Pclass 1 and Pclass 3 have a higher number of outliers.

• From the plot, there are long upper whiskers for all classes, implying that the fare distribution is right-skewed.

• Most Titanic passengers embarked at S. At C, the maximum number of passengers belonged to Pclass 1, while at Q, the maximum number belonged to Pclass 3.

• Children below the age of 10 had higher survival rates compared to non-survivors in the same age group.

• The 25–35 age group had the highest number of survivors among all age groups, but the number of non-survivors was also very high in the same age group.

• Females had a higher chance of survival, while males had a higher chance of not surviving, with a large margin between the two.

• Passengers who paid higher fares had a higher survival rate, whereas passengers with lower fares had a higher rate of non-survival.

• The majority of survivors were from Pclass 1, while the majority of non-survivors were from Pclass 3.
## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 79% |
| Random Forest | 80% |
