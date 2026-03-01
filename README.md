
#  Flight Price Prediction – Exploratory Data Analysis (EDA)

##  Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a flight ticket pricing dataset.  
The objective is to understand the important factors affecting ticket prices and prepare the dataset for machine learning model development.

The project includes data cleaning, feature engineering, visualization, correlation analysis, and outlier treatment.

---

##  Business Objective

Flight ticket prices change dynamically based on several factors. By analyzing pricing patterns:

- Airlines can optimize pricing strategies  
- Customers can understand fare variations  
- Businesses can forecast ticket pricing trends  
- Data-driven insights can improve revenue planning  

---

##  Dataset Information

The dataset contains the following features:

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
- Target Variable: *Price*

---

##  Project Workflow

### 1️⃣ Data Preprocessing

- Checked and handled missing values  
- Removed duplicate records  
- Converted date and time columns into proper format  
- Dropped unnecessary columns  

---

### 2️⃣ Exploratory Data Analysis (EDA)

- Analyzed price distribution  
- Compared airline vs price  
- Studied total stops vs price  
- Analyzed duration impact on price  
- Generated correlation heatmap  

---

### 3️⃣ Feature Engineering

- Extracted Journey Day and Journey Month  
- Extracted Departure Hour & Minute  
- Extracted Arrival Hour & Minute  
- Converted Duration into numerical format  
- Encoded Total Stops into numerical values  

---

### 4️⃣ Outlier Detection

Used Interquartile Range (IQR) method:

- Calculated Q1 (25th percentile)  
- Calculated Q3 (75th percentile)  
- Computed IQR = Q3 − Q1  
- Defined lower and upper bounds  
- Capped extreme values  

---

## 📊 Key Insights

- Airline plays a significant role in ticket pricing  
- Non-stop flights are generally more expensive  
- Duration has strong positive correlation with price  
- More stops tend to reduce ticket price  
- Seasonal trends influence airfare  

---

##  Outcome

- Cleaned and structured dataset  
- Identified key pricing factors  
- Prepared data for machine learning models  

---

##  Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---
