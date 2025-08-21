
# Customer Churn Prediction

Customer churn—the loss of existing subscribers—directly impacts a telecom company’s revenue. This repository presents an end-to-end machine-learning workflow that analyzes customer records to anticipate churn and guide retention strategies.

## 📖 About the Project
The project explores a public dataset of 7,043 California customers, performing exploratory analysis, feature engineering, and training several classification algorithms to uncover patterns behind customer loyalty.

## 📌 Objective
Develop a data-driven system to classify customers into **Churn**, **Stay**, or **Join** segments using demographics, location, tenure, and subscription data. The model helps the business:

- flag high-risk customers before they leave,
- understand which factors most influence churn,
- design targeted marketing and retention campaigns.

## 📊 Dataset
- **Customer Churn table** – 7,043 customers with details about their demographics, location, tenure, subscription services, and quarterly status.
- **Zip Code Population table** – population estimates for the California zip codes used in the Customer Churn table.

## 🛠️ Installation
Clone the repository and install the dependencies.

```bash
git clone https://github.com/Pavankumarmanagoli/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction

# (Optional) create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows use .venv\Scripts\activate

# install required packages
pip install -r requirements.txt
```

## 🚀 Usage
Launch the Jupyter notebook to explore the dataset, train models and evaluate results.

```bash
jupyter notebook src/Customer_Churn_Prediction.ipynb
```

The notebook covers data preprocessing, model training for **Random Forest**, **Logistic Regression**, **Naive Bayes**, **Decision Tree**, and **XGBoost**, and evaluation metrics.

## 📈 Model Performance
| Model                  | Accuracy |
|------------------------|---------:|
| Random Forest          | 78.11%   |
| Logistic Regression    | 78.28%   |
| Naive Bayes Gaussian   | 36.77%   |
| Decision Tree          | 77.29%   |
| XGBClassifier          | 80.86%   |

## 👀 Screenshots
<img src="/assets/1.png" alt="Exploratory Data Analysis" />
<img src="/assets/2.png" alt="Model Training" />
<img src="/assets/3.png" alt="Confusion Matrix" />
<img src="/assets/4.png" alt="Feature Importance" />



## 🪪 License
This project follows the [MIT LICENSE](https://choosealicense.com/licenses/mit/).


    
