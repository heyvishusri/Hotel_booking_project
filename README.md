
# 🏨 Hotel Booking Data Analysis

This project presents a comprehensive exploratory data analysis (EDA) of hotel booking data. It uncovers valuable business insights related to customer behavior, cancellation trends, seasonal patterns, and booking preferences that can help improve decision-making in the hospitality sector.

---

## 📌 Objectives

- Analyze booking patterns across different hotel types.
- Identify factors that influence booking cancellations.
- Discover trends in customer preferences and seasonality.
- Visualize correlations between lead time, ADR, market segment, and special requests.

---

## 📊 Dataset Overview

- **Size**: ~32,000 rows
- **Attributes**: Hotel type, lead time, arrival date, ADR (Average Daily Rate), country, market segment, special requests, and more.

---

## 🛠️ Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📈 Key Insights

- City hotels have a significantly higher cancellation rate than resort hotels.
- Most cancellations occur for bookings with longer lead times.
- Bookings with special requests tend to have a lower cancellation rate.
- August and July are peak months in terms of number of bookings.
- Portugal, UK, and France are top contributing countries.
- Higher ADRs are generally associated with resort hotels in high season.

---

## 📁 Project Structure

```
Hotel_booking_project/
│
├── Hotel_Booking_data_analysis.ipynb   # Main notebook containing full EDA
├── README.md                           # Project documentation
└── hotel_bookings.csv (optional)       # Dataset (not uploaded here)
```

---

## 🚀 How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/heyvishusri/Hotel_booking_project.git
   cd Hotel_booking_project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Hotel_Booking_data_analysis.ipynb
   ```

---

## 📌 Visualizations Used

- Countplots
- Bar charts
- Heatmaps
- Line plots
- Boxplots
- Distribution plots

Each visualization is used to derive actionable insights for decision-makers in the hotel industry.

---

## ✅ Conclusion

This project successfully demonstrates how data analytics can be applied in the hospitality industry to:
- Reduce booking cancellations
- Enhance customer satisfaction
- Optimize marketing efforts
- Forecast seasonal trends for better resource management


## Here's a tailored list of common **Data Analyst placement interview questions** along with **smart, concise sample answers** that you can confidently use in interviews:

---

### ✅ **1. Tell me about yourself.**

**Answer:**
I'm a final-year B.Tech student with a strong foundation in Python, SQL, and data visualization. I recently completed a project analyzing hotel booking data using Pandas, Matplotlib, and Seaborn. I'm passionate about turning raw data into actionable insights and looking forward to applying my skills in a professional analytics environment.

---

### ✅ **2. What are the key responsibilities of a data analyst?**

**Answer:**

* Collecting, cleaning, and analyzing data
* Identifying trends and patterns
* Creating dashboards and reports
* Supporting decision-making with insights
* Communicating findings to stakeholders

---

### ✅ **3. What libraries do you use for data analysis in Python?**

**Answer:**

* **Pandas** – for data manipulation and analysis
* **NumPy** – for numerical operations
* **Matplotlib / Seaborn** – for visualizations
* **Scikit-learn** – for basic machine learning models
* **SQLAlchemy** – for connecting Python with databases

---

### ✅ **4. How do you handle missing data?**

**Answer:**
I check for missing values using `.isnull()`. Depending on the context, I either:

* Drop missing rows using `dropna()`
* Fill values with mean/median/mode using `fillna()`
* Use forward/backward fill for time series
* Or investigate further if data is critical

---

### ✅ **5. Explain your recent project.**

**Answer:**
I analyzed a hotel booking dataset (\~32K records) to understand customer behavior, cancellation trends, and seasonality. I used Pandas for EDA, visualized patterns with Seaborn and Matplotlib, and derived insights like the impact of lead time and special requests on cancellations.

---

### ✅ **6. What’s the difference between INNER JOIN and LEFT JOIN?**

**Answer:**

* **INNER JOIN** returns only matching records from both tables.
* **LEFT JOIN** returns all records from the left table and matching ones from the right. If no match, it fills with NULL.

---

### ✅ **7. What’s the difference between WHERE and HAVING in SQL?**

**Answer:**

* **WHERE** filters rows before grouping.
* **HAVING** filters groups after aggregation.

---

### ✅ **8. How do you explain a complex analysis to a non-technical stakeholder?**

**Answer:**
I avoid technical jargon and use visualizations and simple analogies. I focus on the business impact and actionable takeaways, not the technical process.

---

### ✅ **9. What’s your approach to exploratory data analysis (EDA)?**

**Answer:**

* Understand the data structure
* Check for nulls, duplicates, outliers
* Summarize with descriptive stats
* Visualize distributions and relationships
* Identify trends or anomalies

---

### ✅ **10. What tools do you use for dashboards and reporting?**

**Answer:**
Primarily **Excel** and **Tableau** for dashboards. I also use **Matplotlib/Seaborn** for plots in Python. I’m open to learning Power BI as well.

---



