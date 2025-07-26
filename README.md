task 2 

Summary - SkillCraftTechnology 

• Task: Perform data cleaning and exploratory data analiysis on a dataset. Exlore the relationshipbetween variables and identify patterns and trends in the data.


Steps followed:

1. Importing Libraries
Loads essential libraries like: pandas for data manipulation, numpy for numerical operations, matplotlib.pyplot and seaborn for data visualization.
2. Loading the Dataset
This dataset contains details of Titanic passengers such as age, sex, class, and whether they survived.
3. Exploring the Data
To understand the structure and contents of the dataset.
 Helps identify potential issues like missing values and data types.


4. Checking and Handling Missing Values

 Checks for null values and handles them by:
Dropping columns like Cabin (too many missing values),
Filling missing values in Age with the median,Filling Embarked with the most common value.

5. Feature Engineering
Converts Sex and Embarked into numeric using LabelEncoder.Create useful features that may have predictive power. Enhances model understanding and improves analysis.


6. Exploratory Data Analysis (EDA)
 Uses bar plots, histograms, and count plots to explore survival relationships:
By Gender: Higher survival rate for females.
By Passenger Class (Pclass): Higher class = higher survival.
By Age Group: Children had better survival chances.
By Family Size: Small families had better survival odds.
By Embarkation Point: Some differences in survival by port.
 Visual insights show which features may influence survival.


7. Correlation Analysis
Uses a heatmap to show correlation values between numerical features and the Survived column.
 Gender, Pclass, and FamilySize show some correlation with survival.
