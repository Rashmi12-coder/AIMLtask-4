# AIMLtask-4


# **Titanic Survival Prediction Using Logistic Regression**  

## **Project Overview**  
This project applies **Logistic Regression** for **binary classification**, predicting whether a passenger **survived or not** based on Titanic dataset features.  

## **Dataset Information**  
- **Dataset Used**: `cleaned_titanic.csv`  
- **Preprocessing**:  
  - Removed missing values  
  - Selected relevant features (`Pclass`, `Age`, `SibSp`, `Parch`)  
  - Target variable: `Survived` (1 = Survived, 0 = Did not survive)  

## **Installation & Setup**  
Run the following to install dependencies:  
```bash
pip install -r requirements.txt
```  
Or manually install:  
```python
pip install pandas numpy scikit-learn matplotlib
```

## **How to Run**  
Execute the script using:  
```python
python titanic_classification.py
```

## **Model Details**  
- **Algorithm Used**: Logistic Regression  
- **Independent Variables**: `Pclass`, `Age`, `SibSp`, `Parch`  
- **Dependent Variable**: `Survived` (Binary classification)  
- **Evaluation Metrics**: Confusion Matrix, Precision, Recall, ROC-AUC  

## **Results**  
| Metric  | Value |
|---------|-------|
| Precision | X.XX  |
| Recall    | X.XX  |
| ROC-AUC   | X.XX  |

## **Visualization**  
Example **ROC Curve**, evaluating model performance:

![ROC Curve](path/to/your/roc_curve.png)

## **Project Structure**  
```
├── cleaned_titanic.csv   # Preprocessed dataset
├── titanic_classification.py # Logistic Regression script
├── requirements.txt      # Dependencies
├── README.md             # Documentation
```
