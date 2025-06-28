 🌳 Bank Marketing Decision Tree Classifier (Task 03)

This project builds a Decision Tree Classifier to predict whether a customer will purchase a product or service based on demographic and behavioral data. The dataset used is the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).
 📁 Dataset

Source: UCI Machine Learning Repository  
Dataset Name: Bank Marketing Dataset  
File Used:`bank.csv`

Target Variable:  
- `y` — whether the client subscribed to a term deposit (`yes` or `no`)
 📌 Objectives

- Preprocess the dataset (handle categorical variables, missing values, etc.)
- Train a **Decision Tree Classifier**
- Evaluate the model using accuracy, precision, recall, and confusion matrix
- Visualize the tree structure and feature importances

🔧 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

⚙️ Key Features

- Handles categorical encoding using `LabelEncoder` or `OneHotEncoder`
- Train-test split with evaluation
- Model metrics: Accuracy, Confusion Matrix, Classification Report
- Decision tree visualization using `plot_tree`

 🚀 How to Run

1. Clone this repository or download the notebook/script.
2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
