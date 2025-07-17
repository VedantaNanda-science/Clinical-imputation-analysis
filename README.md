# A Comparative Analysis of Imputation Techniques for Missing Values in Clinical Data

This project presents a comparative analysis of imputation techniques to handle missing data in clinical datasets. The study evaluates 8 methods — from simple imputation to advanced ensemble-based strategies — and measures their impact on machine learning model performance.

## 🧪 Imputation Techniques Explored

- Complete Case Analysis (CCA)
- Simple Imputation (Mean/Median)
- Arbitrary Value Imputation
- Random Sample Imputation
- K-Nearest Neighbors (KNN) Imputation
- Multiple Imputation by Chained Equations (MICE)
- End of Distribution Imputation
- Random Forest Imputation

## 📊 Models Evaluated

- Logistic Regression
- Random Forest Classifier
- Support Vector Machines (SVM)

Each model was trained and evaluated using 5-fold cross-validation. Metrics included:
- F1 Score
- Precision & Recall
- Out-of-Bag (OOB) score (for Random Forest)

## 📁 Repository Structure

clinical-imputation-analysis/
├── notebooks/
│ └── imputation_analysis.ipynb # Jupyter notebook
├── report/
│ └── research_paper.pdf # Final research paper
├── requirements.txt # Python dependencies
└── README.md # Project overview
