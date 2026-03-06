Supervised and Unsupervised Datasets

Taken from: chatgpt.com

1. Supervised Dataset (with labels)

A supervised dataset contains input data and the correct output (label).
The model learns by comparing predictions to the known answer.

Example: Email Spam Detection Dataset
| Email Text                   | Label    |
| ---------------------------- | -------- |
| "Win a free iPhone now!"     | Spam     |
| "Meeting scheduled at 3 PM"  | Not Spam |
| "Limited offer! Click here!" | Spam     |
| "Project report attached"    | Not Spam |
Explanation

Input: Email text
Output/Label: Spam or Not Spam
The algorithm learns patterns to classify future emails.

Common supervised tasks:
- Classification: Spam detection
- Regression: Predicting house prices

2. Unsupervised Dataset (no labels)

An unsupervised dataset contains only input data with no correct answers.
The model must discover patterns or groupings on its own.

Example: Customer Shopping Dataset
| Customer ID | Age | Monthly Spending | Visits per Month |
| ----------- | --- | ---------------- | ---------------- |
| 001         | 22  | 150              | 6                |
| 002         | 45  | 600              | 3                |
| 003         | 25  | 180              | 7                |
| 004         | 50  | 650              | 2                |

Explanation
- There are no labels like "high spender" or "low spender."
- The algorithm might cluster customers into groups such as:
Young frequent shoppers
Older high spenders
Low activity customers

Common unsupervised tasks:
- Clustering (e.g., customer segmentation)
- Dimensionality reduction
- Anomaly detection


More Examples of Supervised and Unsupervised Datasets

spam.csv
Supervised Dataset taken from:
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

USA_Housing.csv
Unsupervised Dataset taken from:
https://www.kaggle.com/code/fatmakursun/supervised-unsupervised-learning-examples