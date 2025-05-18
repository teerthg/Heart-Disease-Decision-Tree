# Heart Disease Classification using Decision Tree

This project uses Decision Tree Classification to predict heart disease presence based on various medical features. It includes full preprocessing, modeling, tuning, and evaluation workflows.

---

## Dataset Description
- **File:** `heart_disease.xlsx`
- **Sheet used:** `Heart_disease`
- **Target Variable:** `num` (0 = No Disease, 1 = Disease)

---

## Project Steps & Rationale

### 1. Exploratory Data Analysis (EDA)
- Understand structure and types of data
- Detect missing values and outliers
- Visualize feature distributions using pairplots and heatmaps

### 2. Feature Engineering
- Encoded categorical columns (Label Encoding)
- Converted boolean and string types to numerical
- Applied StandardScaler to normalize feature values

### 3. Model Training
- Used `DecisionTreeClassifier` from scikit-learn
- Split data into training and testing (80-20 split)
- Evaluated with accuracy, confusion matrix, precision, recall, F1-score

### 4. Hyperparameter Tuning
- Applied GridSearchCV for optimal:
  - `max_depth`
  - `min_samples_split`
  - `criterion`
- Re-trained best model and re-evaluated

### 5. Model Visualization
- Used `plot_tree()` to visualize decision rules
- Increased figure and font size for better readability

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Author
**Teerth Gupta**  
Master’s Student – Statistics and Data Science  
Uppsala University, Sweden  
GitHub: [https://github.com/teerthg](https://github.com/teerthg)
