# Plagiarism-Detector
### A Machine Learning Engineer Nanodegree project
Building a plagiarism detector that examines a text file and performs binary classification, labeling that file as either plagiarized or not, depending on how similar the text file is to a provided source text.

# Project Overview 
###  Notebook 1: Data Exploration
- Load in the corpus of plagiarism text data.
- Explore the existing data features and the data distribution.
- This first notebook is not required in your final project submission.

### Notebook 2: Feature Engineering
- Clean and pre-process the text data.
- Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
- Select "good" features, by analyzing the correlations between different features.
- Create train/test .csv files that hold the relevant features and class labels for train/test data points.

### Notebook 3: Train and Deploy Your Model in SageMaker
- Upload your train/test feature data to S3.
- Define a binary classification model and a training script.
- Train your model and deploy it using SageMaker. **In choosing a model for this problem of binary classification I trained a NN using pytorch.**
- Evaluate your deployed classifier.
