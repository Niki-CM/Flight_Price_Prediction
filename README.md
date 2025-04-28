Flight Price Prediction | Machine Learning Project
## **Project Overview**
- In this project, we aim to predict the price of airline tickets using machine learning algorithms based on various flight features such as airline, source, destination, date of journey, departure time, and more.

## **Objective:**
Build an end-to-end regression model that can accurately predict flight prices and assist users and businesses in making informed decisions.

## **Problem Statement**
Flight prices often fluctuate based on multiple factors such as the airline company, source, destination, number of stops, and timing.
Our task is to predict the flight ticket prices using supervised machine learning techniques, which will help airlines optimize pricing strategies and assist customers in finding better deals.

## **Dataset**
Source: Kaggle 

## **Features:**

- Airline
- Date_of_Journey
- Source
- Destination
- Route
- Dep_Time
- Arrival_Time
- Duration
- Total_Stops
- Additional_Info
- Price (Target variable)

## **Technologies Used**
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost

Joblib (for model saving)

## **Workflow**
** Problem Understanding** 

* Data Collection
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Feature Engineering
* Model Building 
* Model Evaluation
* Hyperparameter Tuning
* Model Saving
* Conclusion and Future Scope

## **Exploratory Data Analysis (EDA)**
* Visualized missing values.
* Analyzed distribution of prices.
* Investigated the impact of features like Airline, Source, Destination, and Duration on Price.
* Found correlations between input features and the target variable.

## **Model Building and Evaluation**
![image](https://github.com/user-attachments/assets/e98e8015-3a92-44a5-9a3d-f5f99f72eb7f)


* Random Forest Regressor performed the best among the tested models.

##  **Final Deliverables**
* Trained Flight Price Prediction model (flight_price_model.pkl)
* Project Notebook (Flight_Price_Prediction.ipynb)

## **Future Scope**
* Integrate Deep Learning (Neural Networks) for improved predictions.
* Incorporate real-time flight data like weather, events, holidays.
* Build a web app using Flask/Streamlit for live predictions.

Acknowledgments
Thanks to Kaggle  for providing the dataset.
Inspired by real-world airline ticketing use cases.



How to Run Locally
Clone this repo:

bash
Copy code
git clone https://github.com/yourusername/flight-price-prediction.git
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Open the notebook and run step-by-step!

