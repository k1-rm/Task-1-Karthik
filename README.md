 #Task-1-Karthik
 
In this task, I performed comprehensive data cleaning and preprocessing on the Titanic dataset. I began by importing essential libraries like pandas, numpy, seaborn, and matplotlib for data manipulation and visualization. I then loaded the dataset directly from a GitHub URL and explored its structure using .head(), .info(), and .isnull().sum() to identify missing values. To handle these, I filled the missing Age values with the median, replaced missing Embarked values with the mode, and dropped the Cabin column due to a high percentage of missing data. For encoding, I converted the Sex column into numeric values and applied one-hot encoding to the Embarked column while avoiding dummy variable traps by dropping the first category. Next, I normalized the numerical features Age and Fare using MinMaxScaler to bring them into a 0–1 range. I visualized outliers in these features using boxplots and removed them using the Interquartile Range (IQR) method to retain only data within acceptable limits. After these preprocessing steps, I displayed a preview of the cleaned data and saved the final dataset as a CSV file named cleaned_titanic.csv. This set the foundation for building robust machine learning models.

Key steps in my Titanic data preprocessing code:

1. Import Libraries – Load tools for data handling and visualization.

2. Load Dataset – Read Titanic data from a GitHub URL.

3. Explore Data – Preview rows, structure, and check for missing values.

4. Handle Missing Values – Fill Age (median), Embarked (mode), drop Cabin.

5. Encode Categorical Data – Convert Sex to 0/1 and apply one-hot encoding to Embarked.

6. Normalize Features – Scale Age and Fare between 0 and 1 using MinMaxScaler.

7. Outlier Detection & Removal – Visualize with boxplots, remove using IQR method.

8. Final Check – Preview cleaned data.

9. Save Dataset – Export cleaned dataset to a CSV file.
 
