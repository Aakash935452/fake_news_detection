Fake News Detection using Machine Learning 📰🤖
Project Overview
This project aims to detect fake news using machine learning techniques.
It involves data preprocessing, TF-IDF feature extraction, model training using the Passive Aggressive Classifier, and performance evaluation.
The solution is built using Python libraries such as pandas, scikit-learn, and numpy inside a Jupyter Notebook.

Features
Load and explore a real-world dataset of news articles.

Preprocess the data for training and testing.

Apply TF-IDF Vectorization for feature extraction.

Train a Passive Aggressive Classifier to distinguish between real and fake news.

Evaluate the model using Accuracy Score and Confusion Matrix.

Requirements
Python 3.x

pandas

numpy

scikit-learn

Jupyter Notebook

You can install the dependencies using:

bash
Copy
Edit
pip install pandas numpy scikit-learn notebook
How to Run
Clone the repository.

Open the Fake_News_Detection_ML.ipynb file using Jupyter Notebook.

Make sure the dataset (CSV file) is available in the same directory.

Run all the cells step-by-step to train and test the model.

Dataset
The project uses a news dataset containing two columns:

text: the content of the news article

label: 'REAL' or 'FAKE' indicating the news type

(Note: You can also replace the dataset with any other labeled news dataset for experimentation.)

Results
The model achieves a high accuracy score and outputs a confusion matrix that helps visualize correct and incorrect classifications.

Author
Developed by Aakash

