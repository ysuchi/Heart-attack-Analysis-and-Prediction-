# Heart-attack-Analysis-and-Prediction-
This project focuses on analyzing heart disease risk factors and predicting heart attack likelihood using data analysis techniques. The dataset was cleaned, explored, and visualized to identify key health indicators affecting heart disease

**Key Highlights:**
**Data Preprocessing**: Removed duplicates, checked for missing values, and ensured data quality.
**Exploratory Data Analysis (EDA)**: Used pandas, matplotlib, and seaborn to visualize trends in chest pain, blood sugar, cholesterol, and other health parameters.
**Insights**: Identified critical risk factors such as chest pain type and fasting blood sugar levels.
**Future Scope**: Implementation of machine learning models to improve heart attack prediction accuracy.

**1. Data Handling & Preprocessing**
Imported necessary libraries: numpy, pandas, matplotlib, seaborn.
Loaded the dataset (heart.csv) and displayed key statistics (df.head(), df.describe(), df.info()).
Checked for missing values (df.isnull().sum()) – found no null data.
Identified and removed duplicate entries (df.drop_duplicates(inplace=True)).

**2. Exploratory Data Analysis (EDA)**
Chest Pain Type (cp) Analysis:
Visualized using sns.countplot().
Non-anginal pain type is more associated with heart attacks.
Fasting Blood Sugar (fbs) Analysis:
Analyzed distribution of fasting blood sugar levels.
Higher risk for individuals with fasting blood sugar levels below 120.

**3. Further Data Visualization**
The dataset was explored using various matplotlib and seaborn visualizations.
Different health parameters were analyzed to determine their correlation with heart attack risk.

**Conclusion from Heart Attack Analysis and Prediction
Key Risk Factors Identified:**

**Chest Pain Type (cp)**: Individuals experiencing non-anginal chest pain have a higher risk of heart attack.
**Fasting Blood Sugar (fbs):** People with fasting blood sugar below 120 mg/dL are more likely to have heart disease.
Other factors such as cholesterol levels, age, blood pressure, and ECG readings likely play a significant role in predicting heart attack risks.

**2. Data Cleaning & Processing:**
No missing values were found in the dataset.
Duplicate entries were removed to ensure data quality.

**3.Visualization & Insights:**

Data visualization helped in identifying trends and correlations between different health parameters and heart attack occurrences.
The use of seaborn and matplotlib enabled better understanding through graphical analysis.

**4.Next Steps (Potential Future Work):**

Implement machine learning models for accurate heart attack prediction.
Explore other important features such as lifestyle habits, family history, and stress levels to improve predictive accuracy.
Validate findings with a larger and more diverse dataset for better generalization.
