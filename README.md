# 📊 Customer Service Request Analysis

## 🎯 Objective
Analyze customer service request data to uncover meaningful insights into complaint patterns, response time behavior, and location-based trends.

---

## 🔍 Key Insights
- 🚗 Blocked Driveway is the most common complaint type  
- 📍 Brooklyn has the highest number of complaints  
- ⏱️ Response time varies significantly across complaint types  
- ⚡ Some complaints are resolved quickly, while others take longer  
- 📊 Statistical tests confirm differences in complaint resolution time  

---

## 📁 Dataset Information
- Source: NYC 311 Service Requests  
- Rows: ~364,000+  
- Columns: 53  
- Data includes complaint types, location, timestamps, and resolution details  

---

## ⚙️ Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- SciPy  

---

## 🧹 Data Cleaning Steps
- Removed records with missing **Closed Date**  
- Converted date columns into datetime format  
- Removed incorrect timelines (Closed < Created)  
- Created **Request Closing Time** feature  
- Handled missing values in City column  

---

## 📊 Exploratory Data Analysis
- Null value analysis  
- Complaint distribution across cities  
- Frequency plots for complaint types  
- Scatter & Hexbin visualization for Brooklyn  

---

## 📍 Complaint Analysis
- Identified most frequent complaint types  
- Analyzed complaints per city  
- Created pivot table for city vs complaint types  

---

## 📈 Statistical Testing
- Performed **ANOVA test**  
- Applied **Kruskal-Wallis test**  
- Validated differences in response time across complaint types  

---

## 📌 Observations
- The dataset reflects diverse urban service issues across multiple cities  
- Blocked Driveway, Illegal Parking, and Noise are dominant complaints  
- Brooklyn shows the highest complaint volume  
- Response time varies depending on complaint complexity  
- Statistical tests confirm significant differences in resolution time  

---

## 📊 Visualizations
- Bar charts (Complaint Types, City-wise complaints)  
- Scatter Plot (Brooklyn complaint distribution)  
- Hexbin Plot (Density visualization)  

---

## 🚀 Conclusion
This analysis highlights key complaint patterns and reveals variability in response time across different complaint types.  
The findings can help improve operational efficiency and resource allocation for better service management.

---

## 👨‍💻 Author
Akshay Patil B.Sc. Computer Science | Aspiring Data Analyst

🔹 Contact

📧 Email: akshaypatil11712@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/akshay-patil2403/

💻 GitHub: https://github.com/akshaypatil111712-dotcom/

---

## ⭐ If you like this project, give it a star!
