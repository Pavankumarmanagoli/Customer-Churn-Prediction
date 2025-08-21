# Customer Churn Prediction

Predict customer retention for a California telecommunications provider using machine learning.

## 📌 Objective
The goal of this project is to predict whether a customer will **churn**, **stay**, or **join** the company based on their demographics, location, tenure, and subscription services. Accurate churn prediction enables proactive retention efforts and better business decisions.

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

##  Screenshots
<img src="/assets/1.png" alt="Exploratory Data Analysis" />
<img src="/assets/2.png" alt="Model Training" />
<img src="/assets/3.png" alt="Confusion Matrix" />
<img src="/assets/4.png" alt="Feature Importance" />



## 🪪 License
This project follows the [MIT LICENSE](https://choosealicense.com/licenses/mit/).


    
