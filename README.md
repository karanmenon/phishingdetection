# Phishing Detection by Karan Menon

## Background

Malicious URLs are a common vector for cyberattacks, causing billions of dollars of losses each year through phishing, malware, spam, and other types of attacks. 
My goal with this project was to see if I could develop a machine learning algorithm to predict URLs were malicious. I used the Malicious URLs dataset from Kaggle
(https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset?resource=download). The dataset had over 650,000 entries, with URLs and their classification (benign, 
phishing, malware, and defacement).

## How the Code Works

In this project, I used machine learning models with SciKit learn. 

The first step in my process was to extract features (data attributes that are used in prediction) of the URLs from the URL string itself. I researched possible indicators of malicious strings, and looked at
features including the length of the string, the presence of certain characters and words, and other attributes of the URL I could get using the urllib library.

I tried three models that are capable of handling large datasets: Naive Bayes (a probabilistic model that assumes all features are independent), Random Forest
(which combines several decision trees, hierarchical systems for classification), and XGBoost (a model also based on decision trees known for its scalability and computing power).


## How to Run

Running the Python notebook is very easy. After cloning or downloading the repository, open it in Jupyter Notebook, Google Colaboratory, VSCode, or any editor.

Then, you can choose to run each cell at a time or run them all at once.
