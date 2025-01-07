# Uncovering Olympic Success: A Century of Data Insights and Predictions

## Project Overview
This project delves into a comprehensive analysis of over 100 years of Summer Olympics data. The goal was to identify patterns and insights, such as the impact of athlete demographics and event types on performance, and to build machine learning models to predict Olympic medal winners.

---

## Table of Contents
- [About the Dataset](#about-the-dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Machine Learning Models](#machine-learning-models)
- [Technologies Used](#technologies-used)
- [Results and Insights](#results-and-insights)
- [How to Use This Project](#how-to-use-this-project)
- [Future Improvements](#future-improvements)

---

## About the Dataset
The dataset contains over **300,000 rows** spanning a century of Summer Olympics history.  
**Key attributes**:
- **Athlete Demographics**: Name, age, gender, height, and weight.
- **Participation Data**: Events, nations, years, and medals.

---

## Exploratory Data Analysis (EDA)
### Data Cleaning:
- Addressed missing values, normalized formats, and dropped irrelevant fields.

### Key Trends Uncovered:
1. Growth in athlete participation over the years.
2. Shifting dominance of nations across events and disciplines.
3. Changing profiles of medalists (age, height, weight) by sport.

### Visualizations:
- **Medal tallies** of top-performing countries.
- **Gender participation trends** using time-series plots.
- **Correlation heatmaps** to reveal significant relationships.

---

## Machine Learning Models
Four machine learning models were implemented to predict medal winners, evaluated on a well-prepared dataset:

### 1. Logistic Regression
- **Accuracy**: 68.65%  
- Used as a baseline model; it captures linear relationships but struggles with complex interactions.

### 2. Decision Tree Classifier
- **Accuracy**: 89.83%  
- Captures complex, non-linear patterns efficiently, though prone to overfitting without pruning.

### 3. Random Forest Classifier
- **Accuracy**: 92.77% (Highest accuracy)  
- Combines predictions from multiple decision trees for improved generalization.

### 4. K-Nearest Neighbors (KNN)
- **Accuracy**: 87.53%  
- Effective for smaller datasets but sensitive to feature scaling and computationally expensive on larger datasets.

---

## Technologies Used
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
- **Jupyter Notebook**: For analysis, visualization, and model building.
- **Machine Learning Models**: Scikit-learn-based classifiers (Logistic Regression, Decision Tree, Random Forest, KNN).

---

## Results and Insights
### Performance Drivers:
- Medals are influenced significantly by an athlete’s physical attributes, prior event performance, and national support.

### Model Comparison:
- **Random Forest** achieved the highest accuracy (**92.77%**) by leveraging the strengths of ensemble learning.
- **Logistic Regression** was less effective, revealing the need for non-linear modeling in this context.

---

## How to Use This Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/olympics-predictions.git
   cd olympics-predictions

## Future Improvements
Experiment with additional algorithms like Gradient Boosting or XGBoost for further accuracy improvement.
Introduce new features such as coach history, training data, or funding levels by nation.
Create a web dashboard for dynamic interaction and live medal predictions.
