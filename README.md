
# **Laptop Price Prediction Using Machine Learning Pipeline**

**This project focuses on predicting laptop prices using machine learning techniques. The dataset used for this project was obtained from Kaggle.**

# **Objective**

**The main objective of this project is to develop a predictive model that can accurately estimate the price of laptops based on various features such as Company TypeName,Ram,Weight,Touchscreen Ips,ppi,Cpu brand,HDD,SSD,Gpu brand ,os.**

# **Methodology**

**Data Preprocessing :Handle missing values and encode categorical variables using column transformation techniques.**

**Exploratory Data Analysis (EDA):Explore the dataset to gain insights into feature distributions, correlations, and patterns. This step aids in understanding the data better before model training.**

**Feature Engineering: Create new features based on domain knowledge or transformations of existing features to enhance model performance.**

M**achine Learning Pipeline: Train and evaluate various machine learning models using pipelines. Models include Linear Regression, Lasso Regression, Ridge Regression, Support Vector Machine (SVM), k-Nearest Neighbors (kNN), Decision Trees, and Random Forest.**

**Hyperparameter Tuning: Utilize Grid Search CV and Random Search CV techniques to tune hyperparameters for the Random Forest model. Also, employ hyperparameter tuning for the Decision Tree model.**

**Model Evaluation: Model performance was evaluated using metrics such as R2 score and Mean Absolute Error (MAE) to assess predictive accuracy**

# Deployment:

The machine learning model was deployed using Streamlit, allowing users to input laptop specifications and receive price predictions in real-time. The application is hosted on Render for easy accessibility.

You can access it here :

https://sms-spam-classification-kj65.onrender.com/


To deploy this project run

Clone the repository:
```bash
  git clone https://github.com/Ankita01K/CodeTech-IT-Solutions.git
```

Install the required dependencies

```bash
  pip install -r requirements.txt
```


Run the Streamlit App
```bash
  streamlit run app.py
```



## Demo

Insert gif or link to demo





![Screenshot 2024-03-10 111034](https://github.com/Ankita01K/Laptop-Price-Prediction/assets/123232024/f65e7957-a694-448c-9179-1f24aa58dfeb)

Prediction almost correct 

![Screenshot 2024-03-10 111109](https://github.com/Ankita01K/Laptop-Price-Prediction/assets/123232024/297265b4-e3b0-41a9-91be-d31ccc802d1f)
