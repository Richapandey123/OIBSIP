# Iris Flower Classification

## Objective
To build a machine learning model that predicts the species of an iris flower (Setosa, Versicolor or Virginica) from its sepal and petal measurements.

## Dataset
Built-in Iris dataset from scikit-learn (150 samples, 4 features, 3 balanced classes).

## Tech Stack
Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, Jupyter Notebook (Google Colab)

## Steps Performed
1. Exploratory data analysis (shape, data types, null values, descriptive statistics)
2. Visualisations: pairplot and box plots
3. Feature analysis (which features separate the species best)
4. Train/test split (80/20, stratified)
5. Trained three models: Logistic Regression, KNN, Decision Tree
6. Evaluation: accuracy, classification report, confusion matrix

## Results
| Model | Accuracy |
|---|---|
| KNN | 100% |
| Logistic Regression | 96.67% |
| Decision Tree | 93.33% |

**Best model:** K-Nearest Neighbours (KNN)

## Key Insights
- Petal length and petal width are the most discriminative features.
- Setosa is clearly separable from the other two species.
- Versicolor and Virginica overlap slightly, which causes the few misclassifications.

## Screenshots
### Pairplot
![Pairplot](screenshots/pairplot.png)

### Box Plots
![Box Plots](screenshots/boxplots.png)

### Confusion Matrices
![Confusion Matrices](screenshots/confusion_matrix.png)

### Model Comparison
![Comparison](screenshots/comparison.png)

## Files
- `Iris_Classification.ipynb`: complete notebook with code, outputs and observations

## Author
Richa Pandey | Data Science Intern, Oasis Infobyte
