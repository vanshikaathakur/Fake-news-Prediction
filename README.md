📰 Fake News Prediction

This project is a machine learning pipeline that uses various classifiers to predict whether a given news article is "real" or "fake." The model is built and tested within a Jupyter Notebook.

🚀 Getting Started

Follow these steps to get the project up and running on your local machine.

Prerequisites

You'll need the following Python libraries installed. You can install them with pip:

pip install pandas numpy scikit-learn matplotlib seaborn

How to Run

Open the Fake News Prediction.ipynb notebook in your preferred Jupyter environment (e.g., Jupyter Notebook, JupyterLab, or VS Code).

Ensure you have the required dataset files (Fake.csv.zip and True.csv.zip) in the same directory as the notebook.

Run all the cells sequentially to perform the data cleaning, model training, and prediction.

🧠 Models Used

The notebook trains and evaluates several popular classification algorithms to determine the best performer:

Logistic Regression

Decision Tree Classifier

Gradient Boosting Classifier

Random Forest Classifier

📈 Project Workflow

The notebook guides you through the entire machine learning process:

Data Loading & Exploration: Loads the dataset and provides initial insights into the data.

Text Preprocessing: Cleans and tokenizes the news text to prepare it for analysis.

Feature Extraction: Converts the text data into numerical features using TfidfVectorizer.

Model Training & Evaluation: Splits the data, trains each model, and evaluates their performance.

Manual Testing: A final function is included to test new, user-provided news articles.

I hope this helps you get your project ready for GitHub!
