# 🏥 Hospital Emergency Room Dashboard - Power BI Project

## 📊 Project Overview

This Power BI dashboard presents an in-depth analysis of **hospital emergency room (ER)** activity across a **19-month period (April 2023 – October 2024)**. It highlights different KPI's such as patient demographics, wait times, satisfaction levels, departmental referrals, and admission trends. This project aims to provide healthcare professionals and administrators with insights to optimize staffing, improve service delivery, and enhance patient care.

---
![Monthly_view](https://github.com/user-attachments/assets/43beaddb-9915-4764-9d1c-140dfac86a76)

## 🔍 Dashboard Features

### ➤ Key Metrics (Top Summary Cards):
- **Total No. of Patients**: 9,216
- **Average Wait Time**: 35.3 minutes
- **Patient Satisfaction Score**: 4.99 / 10
- **No. of Patients Referred**: 3,716

### ➤ Patient Admission Status:
- **Admitted**: 4,612 (50.05%)
- **Treated & Released**: 4,604 (49.95%)

### ➤ Performance Metrics:
- **% of Patients Seen Within Target**: Moderate, indicating areas for improvement
- **Peak Time Blocks**: 11 AM, 1 PM, 7 PM, 11 PM

---

## 🧭 Time-Based Trends

### ➤ Peak Days & Hours:
- **Busiest Days**: Monday (1,377), Saturday (1,321), Tuesday (1,318)
- **Busiest Hours**: Late mornings and evenings — especially 11 AM, 1 PM, 7 PM, 11 PM

### ➤ Hourly Heat Map:
- Time-based data reveals clear staffing pressure points
- Useful for scheduling optimization and shift planning

---

## 🏥 Department Referrals

### ➤ Top Referred Departments:
- **General Practice**: 1,840 cases
- **Orthopedics**: 995
- **Physiotherapy**: 276
- **Cardiology**: 248
- Also includes Gastroenterology, Neurology, and more

---

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** for dashboard building and visualizations
- **DAX** to create calculated columns and measures
- **Data Modeling**: Connected Hospital ER data with a custom Date Table
- **Bookmarks & Navigation** for interactive user experience

---

## 📁 Data Model Details

### Tables Used:
1. **Hospital_ER_Data**
   - Columns include: Patient Admission Date, Admission Hour, Age Group, Referral Department, Satisfaction Score, Wait Time, etc.

2. **Date Table** (Custom)
   - Includes: Date, Day Name, Month Name, Year, and additional time attributes

### Relationships:
- **One-to-many** relationship from `Date Table[Date]` → `Hospital_ER_Data[Admission Date]`
- Enables dynamic time-based filtering and time series insights

---

## 🎯 Purpose of the Project

- To simulate a **real-world Emergency Room dashboard**
- Part of my **Data Analytics portfolio**
- Demonstrates strengths in **data modeling**, **storytelling**, and **visual insight creation** using Power BI

---

## 📌 How to Use

1. Open the `.pbix` file using Power BI Desktop
2. Use slicers to filter by **month** and **department**
3. Navigate through the dashboard using tabs:
   - **Monthly View**
   - **Consolidated View**
   - **Patient Details**
   - **Key Takeaways**

---

## 📬 Contact

If you have questions, feedback, or would like to connect:

**Tej Patel YR**  
📧 tejpatelyr.ire@gmail.com 
🌐 http://www.linkedin.com/in/tej-patel-yr

