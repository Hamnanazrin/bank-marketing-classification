###  Bank Marketing Term Deposit Prediction

This project is a classification analysis to predict whether a client will subscribe to a term deposit based on their personal and financial data.

##  Dataset

  - **Source**: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)
  - **Records**: 45,211
  - **Target**: `y` (1 = subscribed, 0 = not subscribed)

##  Key Steps

  - Loaded and preprocessed the data by converting categorical columns to numeric codes.
  - Dropped the 'duration' column, as it can lead to unrealistic model performance.
  - Visualized key data distributions and relationships.
  - Split the data into a 70% training set and a 30% testing set.
  - Trained a classification model.

##  Model Used

  - **XGBoost Classifier**

##  Files

  - `BankMarketingCSV.csv` – The dataset
  - `your_project_notebook.ipynb` – Your full Colab notebook
  - `README.md` – This project overview

## 🔗 Colab Notebook

 [Open in Colab](https://colab.research.google.com/drive/19rMWu8FHsHEJ8CeLYo67_Y4IWQzLfCSD?usp=sharing)
