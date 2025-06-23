🚢 Titanic Dataset Cleaning
This project focuses on data preprocessing and cleaning of the Titanic dataset. It prepares the dataset for machine learning tasks by handling missing values, encoding categorical variables, standardizing numerical features, and removing outliers.

✅ Steps Performed
Handling Missing Values

Imputed missing entries in features like Age, Cabin, and Embarked.

Encoding Categorical Features

Converted categorical columns such as Sex, Embarked, and Pclass using Label Encoding / One-Hot Encoding.

Standardizing Numerical Columns

Scaled features like Age and Fare using StandardScaler for uniformity.

Outlier Detection & Removal

Used the IQR (Interquartile Range) method to visualize and remove outliers from the dataset.

🛠 Tools & Libraries Used
Python: Core programming language

Pandas: Data loading and preprocessing

NumPy: Numerical operations

Matplotlib & Seaborn: Data visualization

Scikit-learn: Feature scaling with StandardScaler

Google Colab: Cloud-based notebook environment

📂 Dataset Info
Dataset Name: Titanic-Dataset.csv

Description: Information about Titanic passengers such as age, sex, fare, class, and survival status.

Source: Kaggle Titanic Dataset

📥 Input
Raw Dataset: Titanic-Dataset.csv

Characteristics:

Contains missing values

Categorical and numerical data

Some irrelevant columns (e.g., PassengerId, Name, Ticket, Cabin)

📤 Output
Cleaned Dataset: cleaned_titanic.csv

Features:

No missing values

Only relevant features retained

All categorical features encoded

Numerical features scaled

Outliers removed

📊 Sample Visualization
Before and after scaling

Boxplots showing outlier removal

Histograms of feature distributions

