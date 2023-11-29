# NBA_Game_Winner

# Overview
Welcome to the NBA Game Winner Prediction project! This project aims to predict the winner of NBA games using a combination of data science techniques, including web scraping, machine learning, and data modeling. The project is implemented in Python and organized as a Jupyter Notebook.

# Prerequisites
Before running the notebook, ensure that you have the following dependencies installed:

Python 3.11.6
Jupyter Notebook
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, BeautifulSoup (for web scraping)
You can install the required libraries using the following command:
pip install pandas numpy scikit-learn matplotlib seaborn beautifulsoup4

# Project Structure
The project is organized into the following sections:

1. Data Collection (Web Scraping): The notebook starts by collecting data from various sources, including NBA statistics websites. BeautifulSoup is used for web scraping, and the collected data is stored in a pandas DataFrame.
2. Data Preprocessing: This section involves cleaning and preprocessing the collected data. This step ensures that the data is in a suitable format for machine 3/ learning.
3. Exploratory Data Analysis (EDA): Explore the dataset to gain insights into the features and relationships between variables. Visualizations using matplotlib and seaborn are included to assist in understanding the data.
4. Feature Engineering: Create new features or transform existing ones to improve the model's predictive power.
5. Machine Learning Model: Train a machine learning model using scikit-learn. Various algorithms such as Random Forest, Support Vector Machines, or Logistic Regression can be experimented with to find the best-performing model.
6. Model Evaluation: Evaluate the model's performance using appropriate metrics such as accuracy, precision, recall, and F1 score. This section also includes visualizations to interpret the results.
7. Deployment: If desired, deploy the trained model for real-time predictions.

# How to Run
Run in order. Will not run if ran in different order.

1. Run each shell in the get_data.ipynb
2. Run each shell in the parse_data.ipynb
3. Run each shell in the predict.ipynb

