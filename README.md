# Spam-Email-Classifier

## 📧 Project Overview

This project is a machine learning model that classifies emails as either "spam" or "ham" (not spam). It uses a logistic regression model trained on the `mail_data.csv` dataset. The entire process, from data cleaning to model evaluation, is documented in the `Copy of Spam_Email_Classifier.ipynb` Jupyter Notebook.

## Dataset

The dataset used for this project is `mail_data.csv`. It contains two columns:
* **Category:** Labels the email as "spam" or "ham".
* **Message:** The content of the email.

## 🛠️ How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)<YOUR_USERNAME>/Spam-Email-Classifier.git
    ```
2.  **Open the notebook:** Launch Jupyter Notebook and open `Copy of Spam_Email_Classifier.ipynb`.
3.  **Run the cells:** Execute the cells in the notebook to see the data preprocessing, model training, and evaluation steps.

## Model

The project uses a **Logistic Regression** model, a simple yet effective algorithm for binary classification tasks like this one. The text data is converted into numerical features using **TF-IDF Vectorization**.

## 📈 Evaluation

The model's performance is evaluated using the **accuracy score**, which measures the proportion of correctly classified emails.
