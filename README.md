# Titanic - Machine Learning from Disaster  

## Project Introduction  
This project is part of the Kaggle Competition: **Titanic - Machine Learning from Disaster**, where the main objective is to build a model that predicts the survival of passengers in the Titanic tragedy based on demographic and economic data.  

Data cleaning, exploration, and analysis were conducted using Python, with visualizations created using Power BI. Two classification models, **K-Nearest Neighbors (KNN)** and **Random Forest**, were used to train and test the data.  

📊 **View My Power BI Dashboard**  




![Uploading Dashboardimage.PNG…]()


---

## Data Cleaning Process  

- **Age Column**:  
  - Decimal values were rounded to the nearest whole number.  
  - Missing values were filled with the median.  
  - Rows with a value of 0 were removed.  

- **Embarked Column**:  
  - Missing values were filled with the mode.  

- **Fare Column**:  
  - Rows with a value of 0 were removed.  

- **Columns with Many Missing Values**:  
  - Columns with over 77% missing data were removed as they were irrelevant for analysis.  

- **Outliers**:  
  - Outliers in the `Age` and `Fare` columns were retained as they were considered logical.  

---

## Key Visual Insights  

### **Age Categories**  
- **Young Adults** (18–35 years old) made up the largest category (546 passengers).  
- **Children** exhibited the highest survival rate, especially in first- and second-class tickets.  

### **Ticket Pricing**  
- **Cheap** tickets were the most purchased (714 passengers).  
- Passengers with **Pclass 1** tickets had the highest survival rate.  

### **Survival by Gender**  
- Women had a higher survival rate across all classes, particularly in first class.  

### **Pclass and Survival**  
- **Pclass 1** had the highest survival rate.  

### **Male vs Female**  
- There were more men on board (561 passengers), but women had a higher survival rate.  

---

## Key Statistics  

- **Passenger Age**:  
  - Youngest: 1 year old; Oldest: 80 years old.  
  - Average age: 29 years, with a standard deviation of 13.06.  

- **Tickets**:  
  - 670 unique tickets among 875 records.  
  - The ticket "Dooley, Mr. Patrick" appeared 7 times, indicating shared tickets.  

- **Ticket Categories**:  
  - **Cheap** ticket category: 714 passengers.  
  - **Premium** ticket category had the fewest passengers (20).  

---

## Machine Learning Models  

Two classification models were used to predict survival:  

- **K-Nearest Neighbors (KNN)**:  
  - Accuracy: 82%.  

- **Random Forest**:  
  - Performance Metrics: (Add precision, recall, or other metrics here if available).  

---

## Technologies Used  

- **Python**: For data analysis and machine learning models.  
- **Power BI**: For data visualization.  
- **Scikit-Learn**: For building KNN and Random Forest models.  

---

## Dashboard  

The interactive Power BI dashboard can be accessed at the following link:  
**[Power BI Dashboard](#)**  

---

## Conclusion  

This project demonstrates how data cleaning, exploration, and machine learning can be used to generate meaningful predictions based on the Titanic dataset. If you find this repository helpful, please give it a star! 🌟  
