# 🛒 Store Sales Predictive Analysis

A comprehensive data science project that explores and predicts store sales using real-world retail data. The project encompasses in-depth Exploratory Data Analysis (EDA), preprocessing, and the application of machine learning techniques to forecast store performance.

---

## 📁 Project Structure

- `Store Sales EDA Analysis.ipynb`: Detailed exploratory data analysis of store sales dataset.
- `Store Sales Predictive Analysis.ipynb`: Preprocessing, feature engineering, model training and evaluation for sales prediction.

---

## 📊 Exploratory Data Analysis

The EDA focuses on uncovering insights from the dataset and understanding factors that influence sales.

### Key EDA Highlights:
- Distribution of sales across store types and clusters
- Seasonal trends and time-based sales patterns
- Correlation between variables like promotions, holidays, and sales
- Outlier detection and handling of missing data

> Tools Used: `Pandas`, `Seaborn`, `Matplotlib`, `Plotly`

---

## 🛠️ Data Preprocessing

- **Handling Missing Values**: Strategy includes imputation or dropping, based on feature relevance.
- **Encoding**: Applied `LabelEncoder` for categorical variables.
- **Scaling**: Standardized numeric features using `StandardScaler`.
- **Feature Selection**: Retained meaningful variables to improve model accuracy.

---

## 🤖 Machine Learning Model

A **Logistic Regression** model was implemented for classification-based sales prediction.

### Workflow:
1. Data Split: Train-Test split using `train_test_split`
2. Model Training: Fit logistic regression on scaled features
3. Evaluation: Accuracy, confusion matrix, and classification report

> Libraries: `Scikit-learn`, `NumPy`

---

## 🧠 Insights & Results

- Promotional campaigns and holiday events significantly impact sales.
- Clusters and store types reveal distinct purchasing behaviors.
- The logistic regression model gives a decent baseline; future improvements can involve ensemble methods (Random Forest, XGBoost).

---

## 📌 Future Enhancements

- Implement time-series forecasting (ARIMA, Prophet, LSTM)
- Hyperparameter tuning and model ensembling
- Integration with a dashboard for real-time store performance monitoring

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/sahil007707/store-sales-analysis.git
