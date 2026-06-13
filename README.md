# Support Ticket Classification System

## Project Overview

This project builds a Machine Learning model to automatically classify customer support tickets into categories based on ticket subject and description.

The system uses Natural Language Processing (NLP) techniques and a Random Forest classifier to predict ticket types and improve customer support efficiency.

---

## Features

* Data preprocessing and cleaning
* Text feature extraction using TF-IDF
* Support ticket classification
* Model training and testing
* Performance evaluation
* Confusion matrix visualization
* Predict ticket category for new tickets

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Project Structure

```
Support-Ticket-Classification/
│
├── customer_support_tickets.csv.zip
├── support_ticket_classification.py
├── requirements.txt
├── README.md
└── outputs/
```

---

## Installation

Clone the repository:

```bash
git clone <repository_link>
cd Support-Ticket-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Execute:

```bash
python support_ticket_classification.py
```

---

## Workflow

1. Load dataset
2. Clean and preprocess ticket text
3. Combine subject and description
4. Convert text using TF-IDF
5. Train Random Forest model
6. Evaluate model performance
7. Predict support ticket category

---

## Model Evaluation

Metrics used:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## Example Prediction

Input:

```
My payment failed and money was deducted.
```

Output:

```
Predicted Ticket Type: Billing
```

---

## Future Improvements

* Deep Learning (LSTM/BERT)
* Priority prediction (High/Medium/Low)
* Web deployment using Flask/Streamlit
* Real-time ticket analysis

---

## Author

Mukunda
