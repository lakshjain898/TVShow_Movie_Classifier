# Logistic Regression for Classification

## Overview
This project demonstrates the implementation of Logistic Regression for a binary classification problem. The dataset used contains information about Netflix titles, including various categorical and numerical features. The goal is to classify whether a title is a "Movie" or a "TV Show."

## Steps Implemented

### 1. Data Preprocessing
- **Handling Missing Values:**
  - Numerical columns: Imputed with the median.
  - Categorical columns: Imputed with the most frequent value.
- **Encoding Categorical Features:**
  - Used one-hot encoding for categorical features.

### 2. Model Implementation
- **Algorithm:** Logistic Regression
- **Library Used:** Scikit-learn
- **Key Steps:**
  - Split data into training and testing sets (80-20 split).
  - Trained the Logistic Regression model on the training set.
  - Predicted probabilities for the test set.

### 3. Performance Evaluation
- **Metrics Used:**
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC Curve
- **Visualization:**
  - Plotted the ROC curve to analyze the model's performance.

## Dependencies
- Python 3.10+
- Required Libraries:
  ```bash
  pip install pandas numpy matplotlib scikit-learn
  ```

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook code.ipynb
   ```

## Files in the Repository
- `code.ipynb`: Jupyter Notebook containing the implementation.
- `netflix_titles.csv`: Dataset used for training and testing.
- `README.md`: This documentation file.

## Results
- The Logistic Regression model achieved the following results on the test set:
  - **Accuracy:** XX% (replace with actual value)
  - **Precision:** XX% (replace with actual value)
  - **Recall:** XX% (replace with actual value)
  - **F1-Score:** XX% (replace with actual value)
  - **ROC-AUC Score:** XX (replace with actual value)

## Future Enhancements
- Implement other classification algorithms (e.g., Random Forest, SVM) for comparison.
- Perform hyperparameter tuning for Logistic Regression.
- Use advanced encoding techniques for categorical features.

## Author
Laksh Jain
