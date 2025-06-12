# GoInsight---Customer-Churn-Prediction

📊 Customer Churn Analysis
This project explores and visualizes a telecom company's customer data to identify key patterns and factors related to customer churn. Using Python libraries like Pandas, Matplotlib, and Seaborn, the project performs EDA (Exploratory Data Analysis) on categorical features to understand their relationship with churn behavior.

🧠 Objectives
Clean and prepare customer churn data.

Identify and visualize missing values and duplicate records.

Perform univariate and bivariate analysis of categorical features.

Understand churn distribution across various customer segments.

🗂️ Dataset
File: customer.csv

Source: Telecom customer data

Attributes Include:

State

Area code

International plan

Voice mail plan

Churn (target variable)

...and more numeric features not visualized in this version.

🛠️ Tools & Libraries
Python 3.x

Pandas – for data manipulation

Matplotlib – for visualizations

Seaborn – for enhanced statistical plots

🚀 How to Run
Clone this repository.

Make sure customer.csv is in the same directory as customer churn.py.

Update the file path in the code if necessary:

python
Copy
Edit
data = pd.read_csv('customer.csv')
Run the script:

bash
Copy
Edit
python "customer churn.py"
📈 Visualizations Included
Count plots for each categorical feature

Churn distribution by:

State

Area code

International plan

Voice mail plan

Each plot is annotated to show count values and improve interpretability.

✅ Output
Summary of missing values and data types

Number of duplicate rows removed

Descriptive statistics of numerical data

Churn breakdown across different features

🔍 Insights
States and area codes may show different churn tendencies.

Customers on international plans or without voicemail might have distinct churn behaviors (visual evidence).

This analysis lays the groundwork for future churn prediction modeling.

📌 To Do / Next Steps
Add numerical feature analysis

Train a classification model (e.g., logistic regression or random forest)

Evaluate model performance and feature importance

🤝 Author
Prakhar Singh
📫 LinkedIn | 📧 prakharsingh1998@gmail.com
