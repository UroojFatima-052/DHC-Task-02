# Loan Default Prediction – Machine Learning Project

This project focuses on predicting whether a loan applicant is likely to **default** or **not default** using machine learning techniques.  


## Objectives
- Clean and preprocess loan applicant data  
- Handle missing values appropriately  
- Perform exploratory data analysis (EDA)  
- Train classification models  
- Evaluate model performance using accuracy and confusion matrix  


## Data Preprocessing
- Dropped sparse and low-importance columns  
- Filled missing numerical values using **median**  
- Filled missing categorical values using **mode**  
- Encoded all categorical features using **one-hot encoding**  
- Split the dataset into **train** and **test** sets  


## Exploratory Data Analysis
Visualizations included:
- Income distribution  
- Loan amount distribution  
- Credit score analysis  
- LTV distribution  
- Loan purpose vs default  
- Region vs default  
- Correlation heatmaps  
- Scatter and box plots  

These plots helped identify patterns and relationships that influence loan default behavior.


##  Models Used
### 1. Logistic Regression  
Used as a baseline linear model for binary classification.

### 2. Decision Tree Classifier  
Captures non-linear relationships and interactions between variables.



## Model Performance

Model                Accuracy 

Logistic Regression   **87%**  
Decision Tree         **88%**  

The **Decision Tree** slightly outperformed Logistic Regression, suggesting the data contains non-linear patterns that trees capture effectively.


## Conclusion
Both models performed well, achieving around **87–88% accuracy**.  
The Decision Tree performed the best overall, while Logistic Regression provided interpretable baseline results.  
The project demonstrates a complete ML pipeline including cleaning, EDA, encoding, model training, and evaluation.


## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  


## Contact
For questions or improvements, feel free to reach out or open an issue.