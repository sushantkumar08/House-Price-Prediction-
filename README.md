

# **House Price Prediction of Bangalore**

## **Overview**
This project focuses on predicting house prices in Bangalore, India, using Machine Learning techniques. It integrates data science, machine learning, and web development to create a predictive model deployed on the Heroku platform. The goal is to provide accurate house price estimations based on factors like location, size, and amenities.



## **Objective**
- Build a machine learning model to predict house prices in Bangalore.
- Understand the end-to-end machine learning workflow, from data preprocessing to model deployment.



## **Motivation**
Machine Learning has vast potential in real-world applications. Predicting housing prices is critical for investors, homeowners, and policymakers, making this an impactful use case.



## **Dataset**
The dataset is sourced from Kaggle and contains over 13,000 rows with features including:
- **Area Type**
- **Availability**
- **Location**
- **BHK**
- **Square Footage**
- **Bathrooms**
- **Balconies**

Dataset Link: [Kaggle - Bengaluru House Price Data](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data)



## **Technologies Used**
### **Programming Languages**
- Python
- JavaScript (Frontend)

### **Libraries**
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

### **Tools**
- Jupyter Notebook
- Flask (Backend)
- Heroku (Deployment Platform)



## **Methodology**

### **1. Data Preprocessing**
- Removed missing values and irrelevant features.
- Applied dimensionality reduction techniques to optimize categorical variables (e.g., locations).
- Detected and removed outliers using statistical analysis and business logic:
  - Removed properties with unrealistic square footage or BHK counts.
  - Filtered out properties where pricing trends were inconsistent.

### **2. Exploratory Data Analysis**
- Analyzed patterns, trends, and correlations.
- Visualized pricing outliers to identify discrepancies.

### **3. Model Building**
- Experimented with multiple machine learning algorithms:
  - **Linear Regression** (Best performance: 80% accuracy)
  - Decision Tree Regression
  - Random Forests
  - Support Vector Machines
- Used K-Fold Cross-Validation and GridSearchCV for hyperparameter tuning.

### **4. Feature Engineering**
- Engineered new features like "Price Per Square Foot."
- Reduced data dimensions by grouping low-frequency locations.

### **5. Deployment**
- Exported the model as a pickle file for backend integration.
- Developed a Flask-based web application.
- Deployed the app on Heroku for accessibility.



## **Web Application**
- **Frontend:** Simple HTML form with JavaScript to interact with the backend.
- **Functionality:** Users input details like square footage, BHK, bathrooms, and location to get an estimated price.




## **Results**
- The Decision Tree Regression model achieved the best R-squared value, making it the most reliable algorithm for this dataset.
- The deployed web app provides an intuitive interface for accurate house price prediction.



## **Project Architecture**

1. **Data Science Workflow:**
   - Data Cleaning
   - Exploratory Data Analysis
   - Feature Engineering
   - Model Building and Evaluation

2. **Web Development Workflow:**
   - Backend: Flask API
   - Frontend: HTML + JavaScript
   - Deployment: Heroku


## **Conclusion**
The project successfully predicts property prices in Bangalore by combining data science, machine learning, and web development. The integration of a web app provides users with a simple yet effective way to estimate house prices.


---


### **Web Application Interface**
Below is the screenshot of the user interface of the House Price Prediction of Bangalore app, where users can input property details to get estimated prices.

 
![1st SS](https://github.com/user-attachments/assets/cc92e564-efaf-4f81-8086-ab6ae02d9841)

![2nd SS](https://github.com/user-attachments/assets/f3acbeb4-edc5-4d76-97b0-9fa16c91c7da)

![3rd SS](https://github.com/user-attachments/assets/6be64540-610c-43f4-9829-ee111122c3e5)

