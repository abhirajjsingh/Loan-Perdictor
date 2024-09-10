# Two-Wheeler Loan Approval Prediction

## Project Overview
This project develops a machine learning model to predict whether a two-wheeler loan application will be accepted or rejected. The model is trained on historical loan application data combined with additional data extracted from third-party sources, focusing on applicant financial behaviors and other relevant details.

## Data Description
The dataset used includes various features related to the applicants:
- Personal details (name, contact)
- Financial information (income, credit score)
- Employment details
- Other relevant information gathered from third-party sources.

The data is split into:
- **Training data:** Used to train the model.
- **Test data:** Used to evaluate the model's performance.

## Installation
Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name

## Model
The project uses a Random Forest Classifier due to its effectiveness in handling various data types and robustness against overfitting. The model is evaluated using accuracy, precision, recall, and F1-score.
