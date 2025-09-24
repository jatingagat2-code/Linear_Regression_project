Linear Regression Model for Customer Spending Prediction
📌 Project Overview

This project demonstrates how Linear Regression can be used to predict Yearly Amount Spent by customers based on their usage behavior and membership details.
It includes Exploratory Data Analysis (EDA), model building, and evaluation using Python libraries such as Pandas, Seaborn, Matplotlib, and Scikit-learn.

🚀 Features

Data exploration and visualization (pairplots, scatterplots, correlation analysis).

Model training using Linear Regression.

Evaluation using MAE, MSE, RMSE.

Clear insights into which features impact customer spending the most.

Visual comparison of predicted vs. actual values.
├── data/
│   └── linear_dataset.csv          # Dataset file
├── notebooks/
│   └── Linear_Regression_Project.ipynb   # Jupyter Notebook with code
├── report/
│   └── Minor_Project_Report.docx   # Detailed project report
├── README.md                       # Project documentation
└── requirements.txt                # Python dependencies
Tech Stack

Python

Pandas – Data manipulation

Matplotlib / Seaborn – Data visualization

Scikit-learn – Machine learning (Linear Regression, train-test split, evaluation)

📊 Dataset Description

The dataset contains the following features:

Avg. Session Length – Average time spent in a session.

Time on App – Time spent on the mobile app.

Time on Website – Time spent on the website.

Length of Membership – How long the customer has been a member.

Yearly Amount Spent (Target) – Total yearly spending.

🔎 Exploratory Data Analysis

Some insights from EDA:

📈 Length of Membership is the strongest predictor of spending.

📱 Time on App has a higher impact than Time on Website.

🌐 Website usage is less influential on yearly spending.

(Visualizations include pairplots, scatterplots, and regression plots).

⚙️ Methodology

Load and preprocess dataset.

Perform EDA using Seaborn and Matplotlib.

Train-test split (70% - 30%).

Train a Linear Regression model with Scikit-learn.

Evaluate the model with error metrics (MAE, MSE, RMSE).

Visualize results with predicted vs. actual values.

📈 Results

Strong correlation found between Length of Membership and Yearly Amount Spent.

Regression model produced low errors, showing good predictive performance.

Scatterplot of predicted vs. actual values confirms alignment.
# Clone the repository
git clone https://github.com/your-username/linear-regression-customer-spending.git

# Navigate to project folder
cd linear-regression-customer-spending

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook notebooks/Linear_Regression_Project.ipynb
References

Scikit-learn Documentation

Seaborn Documentation

Pandas Documentation# Linear_Regression_project
