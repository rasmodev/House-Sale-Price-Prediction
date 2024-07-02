# House-Sale-Price-Prediction
![image](https://github.com/rasmodev/House-Sale-Price-Prediction/assets/131151974/b740ea17-8438-404c-926b-ebca9450f6cb)

This project focuses on predicting house sale prices based on various features using machine learning regression techniques. The dataset used contains detailed information about residential properties, including physical attributes, location characteristics, and sale conditions.
Certainly! Here's a GitHub README template for your house price prediction project:

---
## Methodology

The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework, which includes the following phases:

1. **Business Understanding:**
   - Define objectives and understand the importance of predicting house prices.

2. **Data Understanding:**
   - Explore datasets, analyze variable descriptions, and conduct exploratory data analysis (EDA) to understand data distributions and relationships.

3. **Data Preparation:**
   - Clean data by handling missing values, duplicates, and outliers.
   - Encode categorical variables and perform feature engineering to prepare data for modeling.

4. **Modeling:**
   - Select and implement regression algorithms such as Linear Regression, Random Forest, and Gradient Boosting to predict house prices.
   - Train models using the training dataset and evaluate their performance.

5. **Evaluation:**
   - Assess model performance using metrics like Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).
   - Optimize models by fine-tuning hyperparameters to improve predictions.

6. **Deployment:**
   - Deploy the best-performing model as a web application for real-time predictions using frameworks like Streamlit, Gradio, or FastAPI.

## Business Understanding

### Objectives

- **Exploratory Data Analysis (EDA):** Gain insights into housing data to understand features, demographics, and price trends.
- **Predictive Modeling:** Develop accurate models to estimate house sale prices, benefiting real estate companies, buyers, sellers, and financial institutions.

### Stakeholders

- **Real Estate Companies:** Utilize accurate property valuations to offer competitive pricing.
- **Home Buyers and Sellers:** Make informed decisions based on property valuations.
- **Financial Institutions:** Assess property values for lending decisions, reducing risks.
- **Investors:** Identify investment opportunities based on price trends and property values.

## Data Understanding

### Data Fields

The dataset includes 80 features (81 in training data) covering various aspects of residential properties:

- **Numerical Features:** Include areas (lot, basement, living), number of rooms, and years built/remodeled.
- **Categorical Features:** Cover zoning, utilities, neighborhood, and property condition.

### Loading Data

- **Train Dataset:** Contains features including `SalePrice`, used for training models.
- **Test Dataset:** Lacks `SalePrice` and is used for predictions after model training.

### Setup

- **Libraries Used:** Pandas, NumPy, Seaborn, Matplotlib, Plotly Express, Scikit-Learn, LightGBM, Category Encoders.

### Data Preparation

- **Cleaning:** Addressed missing values, duplicates, outliers.
- **Encoding:** Categorical variables transformed using One-Hot and Label Encoding.
- **Feature Engineering:** Created new features to enhance model performance.

### Modeling

- **Regression Models:** Linear Regression, Lasso, Ridge, Decision Tree, Random Forest, Gradient Boosting, XGBoost, LightGBM.
- **Evaluation:** Used RMSE and MAE to assess model accuracy.

### Deployment

- **Web Application:** Deployed using Streamlit for real-time predictions.

## Repository Structure

```
├── data/                        # Directory for dataset files
│   ├── train.csv                # Training dataset
│   ├── test.csv                 # Test dataset
│   └── test_predictions.csv     # Dataset with test predictions
├── notebooks/                   # Directory for Jupyter notebooks
│   └── house_price_pred.ipynb   # Jupyter notebook for EDA, modeling, and evaluation
├── src/                         # Source code for the project
│   └── app.py                   # Streamlit web application for model deployment
├── requirements.txt             # Python dependencies
├── model_and_key_components.pkl # Saved model and key components for deployment
├── README.md                    # Project overview, setup instructions, and usage guide
└── LICENSE                      # License information
```

## Setup Instructions

1. Clone the repository:

   ```
   git clone https://github.com/rasmodev/house-price-prediction.git
   cd house-price-prediction
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Explore the notebook in `notebooks/` for detailed analysis and modeling.

4. Run the Streamlit application for real-time predictions:

   ```
   streamlit run src/app.py
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
# Author

`Rasmo Wanyama`

`Data Analyst/Data Scientist`

Let's connect on LinkedIn:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rasmo-/) 
