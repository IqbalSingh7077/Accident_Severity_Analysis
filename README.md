# Accident_Severity_Analysis
This project aims to use historical data to predict the severity of an accident.


# Problem Understanding
Motor vehicle accidents can happen quite suddenly, and all too often lead to fatal results. They can involve cars, trucks, motorcycles, and single or multiple vehicles. Some of these deaths occur at the scene of an accident, while others cause injuries that lead to fatalities after the victims receive medical care.
Now, wouldn't it be great if there is something in place that could warn you, given the weather and the road conditions about the possibility of you getting into a car accident and how severe it would be, so that you would drive more carefully or even change your travel if you are able to.

# Target Audience
These analyses can be quite beneficial to the following- 
1. Daily commuter's in saving time. 
2. Road Traffic control department for making policies & understanding traffic in different areas. 
3. Government for making useful policies to reduce chances of accidents.

# Data sources
For the purpose analysis, Data used in this **"IBM Data Science Professional Certificate** capstone project was provided by IBM.

# Data Cleaning
There were several problems with this data that needed to be fixed.
• The dataset has so many missing values in some of the attributes.
• There is a duplicate column of “SEVERITYCODE” as “SEVERITYCODE1”.
• Datatype of several attributes is not correct.
• Several attributes are not useful in building a machine learning model.
• Dependent variable “SEVERITYCODE” has unbalanced data, this can make our model biased.
• There are some inconsistent values in ‘UNDERINFL’.

# Modeling
The problem at hand was of classification, hence We chose two famous classification algorithm’s, Logistic Regression and Decision tree to make a ML model.

# Evaluation
Both models performed well with over 70% accuracy, but Decision Tree was better among both with 72.8% accuracy.
