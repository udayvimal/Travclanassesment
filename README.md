# TravClan – Business Analyst Intern Assignment  
Hotel Booking & Cancellation Analysis

## Author
**Uday Vimal**  
Email: udaywork0204@gmail.com  

---

## 📌 Project Overview
This project analyzes hotel booking transactions from an online travel platform to
identify cancellation patterns, understand underlying root causes, and propose
actionable business recommendations.  

The analysis is designed from a **B2B travel platform perspective**, focusing on
revenue predictability, partner reliability, and channel performance.

---

## 📂 Dataset Description
- **Dataset Name:** Hotel_bookings_final.csv  
- **Records:** ~30,000 booking transactions  
- **Source:** Online hotel booking platform  

### Key Dimensions
- Booking Channel (Web, Mobile App, Travel Agent)
- Room Type (Standard, Deluxe, Suite)
- Star Rating (2–5 stars)
- Booking Status (Cancelled / Completed)

### Derived Metrics
- Cancellation Flag
- Stay Length
- Lead Time

---

## 🎯 Objectives
- Identify meaningful booking and cancellation trends
- Analyze variation across channels, room types, and star ratings
- Perform root cause analysis grounded in real booking behavior
- Provide practical, B2B-focused business recommendations

---

## 🔍 Analysis Approach
1. Data cleaning and missing value handling  
2. Feature engineering (lead time, stay length, cancellation flag)  
3. Exploratory analysis with visualizations  
4. Hypothesis testing for temporal and contextual factors  
5. Root cause interpretation based on observed patterns  

Negative findings (e.g., weak temporal impact) were explicitly validated and reported
to maintain analytical integrity.

---

## 📊 Key Insights
- Overall cancellation rate is approximately **20%**
- Travel Agent bookings show the highest cancellation risk
- Standard room bookings are more price-sensitive and volatile
- Star rating has minimal impact compared to booking context
- Cancellation behavior is driven more by **channel and room type**
  than by timing or stay duration

---

## 💡 Business Recommendations
- Channel-specific cancellation controls for agent bookings
- Context-aware pricing instead of blanket discounts
- Promotion of premium room categories for stable revenue
- Relationship-driven pricing using CRM and partner performance data

---

## 🛠 Tools & Technologies
- Python
  - pandas
  - numpy
  - matplotlib
  - seaborn
- Jupyter Notebook
- PowerPoint / PDF for reporting

---

## ✅ Notes
- Virtual environment (`trav_env`) is excluded from version control
- Analysis focuses on business reasoning rather than model complexity
- Visualizations are designed for executive-level interpretation

---

## 📬 Contact
For any questions or clarifications, feel free to reach out at  
**udaywork0204@gmail.com**


---

## 📁 Repository Structure
