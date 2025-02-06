# **India’s Flood Landscape: AI-Driven State-wise and Year-wise Analysis with Predictive and Preventive Insights (Assam Focus)**  

## **Abstract**  
Floods in India cause extensive damage to infrastructure, agriculture, and human settlements. This project leverages **machine learning** to analyze **state-wise and year-wise** flood damages over the past 20 years, focusing on Assam. The study employs **Linear Regression, Random Forest, and Gradient Boosting** to predict future flood damage trends and improve flood management strategies.  

## **Introduction**  
Floods are one of the most devastating natural disasters in India, with states like **Assam, West Bengal, and Andhra Pradesh** being highly vulnerable. Traditional flood prediction models rely on **historical statistics**, which may not capture evolving climate patterns. This project integrates **machine learning techniques** to **analyze past trends and forecast future flood impacts**, aiding in better flood preparedness and management.  

## **Objectives**  
- **Analyze** flood damage trends in India (2000–2021).  
- **Identify** the states most affected by floods.  
- **Examine** district-wise flood impact in Assam (2019–2023).  
- **Develop predictive models** to forecast future flood damages.  
- **Provide recommendations** for flood mitigation and disaster management.  

## **Dataset Description**  
The dataset is sourced from:  
- **Central Water Commission (CWC)**: State-wise flood damage data (2000–2021).  
- **Assam State Disaster Management Authority (ASDMA)**: Assam-specific flood data (2019–2023).  
- **India Meteorological Department (IMD)**: Rainfall statistics.  

**Key Parameters:**  
- **Flood-affected area (in million hectares)**  
- **Total population affected**  
- **Crops damaged (area in million hectares & financial loss in Rs. Crore)**  
- **Houses damaged (number & financial loss in Rs. Crore)**  
- **Public utility damages (in Rs. Crore)**  
- **Rainfall statistics (actual vs. normal rainfall, deviation in mm)**  

## **Methodology**  
The project follows a structured **data-driven approach**:  

### **1. Data Preprocessing**  
- **Cleaning & Imputation**: Handling missing values and outliers.  
- **Feature Engineering**: Creating new attributes (e.g., damage per capita).  
- **Scaling**: Standardizing numerical variables.  

### **2. Exploratory Data Analysis (EDA)**  
- **Trend Analysis**: Year-wise flood damage comparison.  
- **Geographical Analysis**: Identifying highly affected states and regions.  
- **Anomaly Detection**: Using **K-Means Clustering** to detect unusual flood years.  

### **3. Predictive Modeling**  
**Machine Learning Algorithms Used:**  
- **Linear Regression** (for general trend forecasting).  
- **Random Forest** (for robust predictions).  
- **Gradient Boosting** (best for Assam-specific predictions).  

## **Tools & Technologies**  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn).  
- **Machine Learning Algorithms** (Linear Regression, SVM, Random Forest, Gradient Boosting).  
- **Data Visualization** (Heatmaps, Bar Charts, Line Graphs, Scatter Plots).  

## **Key Findings**  
- **Flood damages have increased over the years**, with **2015 and 2021 being the most destructive**.  
- **Andhra Pradesh, West Bengal, and Karnataka** suffered the highest total damages.  
- **Assam experiences frequent flooding**, with Baksa, Chirang, and Barpeta being the most vulnerable districts.  
- **Linear Regression was the best-performing model** for national predictions, while **Gradient Boosting performed best for Assam**.  

## **Results**  
- **Flood damage is increasing in both severity and frequency**, especially in urban areas.  
- **Public infrastructure is highly vulnerable**, with damages exceeding **₹50,000 Cr in peak years**.  
- **Gradient Boosting achieved an R² score of 0.9999**, making it highly accurate for Assam’s flood damage predictions.  

## **Future Scope**  
- **Integrate IoT & real-time satellite data** for early flood detection.  
- **Enhance models using Convolutional Neural Networks (CNNs) & LSTMs**.  
- **Develop a flood risk index for Indian states and districts**.  
- **Improve disaster response strategies using AI-powered decision systems**.  

## **Contact**  
For more information, contact:  
📧 **Sanika Khanduja** – sanika172btcse23@igdtuw.ac.in  
📧 **Shreyjaya Bahl** – shreyjaya190btcse23@igdtuw.ac.in  
📧 **Ritu Rani (Corresponding Author)** – rituranibpit@gmail.com  
