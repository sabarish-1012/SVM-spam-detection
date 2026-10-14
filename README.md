# SMS Spam Detection using Support Vector Machine (SVM)

## Project Overview

This project builds a machine learning model to classify SMS messages as **Spam** or **Ham (Legitimate)** using Support Vector Machine (SVM).

The project explores text preprocessing, TF-IDF feature extraction, Linear SVM, and RBF Kernel SVM to understand how different classification approaches perform on text data.

## Objectives

- Classify SMS messages as spam or legitimate.
- Convert text messages into numerical features using TF-IDF.
- Train and evaluate a Linear SVM classifier.
- Explore RBF Kernel SVM and hyperparameter tuning.
- Compare model performance using classification metrics.
- Analyse false positives and false negatives.

## Dataset

**SMS Spam Collection Dataset**

The dataset contains SMS messages labelled as spam or ham.

Dataset source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

Check the original dataset's terms before redistributing the data.

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook

## Project Workflow

1. Load and inspect the dataset.
2. Clean and preprocess SMS messages.
3. Split the data into training, validation, and test sets.
4. Convert text into numerical vectors using TF-IDF.
5. Train a Linear SVM classifier.
6. Train and tune an RBF Kernel SVM.
7. Evaluate models using accuracy, precision, recall, and F1-score.
8. Analyse the confusion matrix, false positives, and false negatives.

## Models

### Linear SVM

Uses a linear decision boundary and is a useful baseline for high-dimensional text classification.

### RBF Kernel SVM

Uses a nonlinear kernel to learn more complex decision boundaries.

Hyperparameters should be tuned using training and validation data or cross-validation, without using the test set for model selection.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- False positive and false negative analysis

## Results

Add your actual test-set results here after running the notebook.

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Linear SVM | Add result | Add result | Add result | Add result |
| RBF Kernel SVM | Add result | Add result | Add result | Add result |

Do not enter estimated or invented metrics. Report the values obtained from your final evaluation.

## Key Learnings

- Text preprocessing and TF-IDF feature extraction.
- Linear and nonlinear SVM classification.
- Hyperparameter tuning and model evaluation.
- Understanding precision, recall, false positives, and false negatives.

## How to Run

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install dependencies using `pip install -r requirements.txt`.
4. Open the Jupyter Notebook.
5. Run the cells in order.

## Future Improvements

- Build a small web application for live SMS classification.
- Save and reuse the trained model and TF-IDF vectorizer.
- Evaluate performance on new, unseen messages.
- Monitor false positives and false negatives.

## Author

Sabarish

GitHub: https://github.com/sabarish-1012