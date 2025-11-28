# Iris Flower Classification – ML Project

This project builds a machine learning model to classify Iris flowers into Setosa, Versicolor, and Virginica using the classic Iris dataset.  
It includes EDA, model training, comparison, cross-validation, and prediction.

## Features
- Dataset upload through Google Colab  
- Data cleaning & preprocessing  
- Label encoding  
- Visualizations:
  - Histograms
  - Pairplot
  - Correlation heatmap
  - Boxplots
- Model comparison using:
  - Logistic Regression
  - KNN
  - SVM (RBF)
  - Random Forest
- 5-fold cross-validation  
- Best model selection  
- Confusion matrix & classification report  
- Saves final model and label encoder using joblib  

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-Learn  
- Seaborn, Matplotlib  
- Joblib  

## How to Run
1. Open the notebook in Google Colab  
2. Upload `iris.csv` when prompted  
3. Run all cells  
4. Use the prediction function to test new values  

## Output Files
- `iris_best_model.joblib`
- `iris_label_encoder.joblib`

## Example Prediction
```python
predict_species(5.1, 3.5, 1.4, 0.2)
