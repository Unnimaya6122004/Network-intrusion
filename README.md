# Network Intrusion Detection

## Introduction
This project implements a machine learning-based approach for network intrusion detection using the Random Forest and Support Vector Machine (SVM) classifiers. The dataset is preprocessed, trained, and evaluated to classify network intrusions effectively.

## Prerequisites
Ensure you have the following installed before running the code:
- Python 3.x
- Required Python libraries:
  ```bash
  pip install pandas numpy seaborn matplotlib scikit-learn
  ```

## Running the Code
1. Clone the Repository (If applicable)**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Download the Dataset**
   - Place `Train_data.csv` and `Test_data.csv` in the working directory.

3. Run the Script**
   Execute the Python script:
   ```bash
   python network_intrusion_detection.py
   ```

## Code Workflow
1. Load Dataset: Reads `Train_data.csv` and `Test_data.csv`.
2. Data Preprocessing:
   - Missing values handled with median imputation.
   - Categorical features encoded using Label Encoding.
   - Features scaled using StandardScaler.
3. Train Models:
   - Random Forest Classifier
   - Support Vector Machine (SVM)
4. Evaluate Models:
   - Accuracy, Precision, Recall, and F1-Score computed.
   - Confusion Matrix visualized.
5. Predict on New Data:
   - Loads `Test_data.csv` for evaluation.
   - Predicts labels using trained models.

## Output
- Model evaluation metrics displayed.
- Feature importance visualized (for Random Forest).
- Predictions on a sample test case printed.

## Notes
- Ensure the dataset columns match those expected in the script.
- Modify the `class` column name if different in your dataset.

## Author
Unnimaya K.

---


