

#  Factory Production Analytics Dashboard | Power BI
https://github.com/Shubhanshu007iit/Factory-Production-Dashboard/blob/main/Production%20Dashbaord.png 


Factory production analytics using Python, Excel, and Power BI for KPIs, OEE, and performance insights. A data-driven interactive dashboard designed to monitor and optimize real-time production performance. This project provides insights into production output, downtime, efficiency, defects, and resource utilization — helping manufacturing teams make faster and smarter decisions.

---

## 📌 Project Objectives

✅ Track total production output  
✅ Monitor machine & line efficiency  
✅ Analyze defect trends and rejection rates  
✅ Identify downtime causes & durations  
✅ Improve decision-making with KPIs & visual insights  

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Excel / CSV Production Dataset**
- **Power Query**
- **DAX Measures**
- **Data Modeling**

---

## 📂 Project Structure
📁 Production-Dashboard
│── 📊 Dashboard.pbix
│── 📄 Production_Data.csv
│── 📄 Machines_Data.csv (optional)
│── 📄 README.md
│── 📁 Screenshots
│ └── dashboard_overview.png


---

## 📥 Dataset Description

| Column Name        | Description |
|-------------------|-------------|
| Date              | Production date |
| Shift             | Shift (A/B/C) |
| Machine Name      | Machine or Line |
| Production Count  | Total units produced |
| Defective Units   | Units rejected/failed |
| Downtime (min)    | Machine stoppage time |
| Operator Name     | Supervisor/Operator |

---

## 📊 Key Metrics (KPIs)

- **Total Production**
- **Defect Rate (%)**
- **Machine Efficiency (%)**
- **Total Downtime (min/hr)**
- **Shift-wise Performance**
- **Top Underperforming Machines**

---

## 📈 Dashboard Features

✅ Interactive filters (Date, Shift, Machine)  
✅ Trend analysis charts  
✅ Defect heatmaps  
✅ Downtime root-cause visual  
✅ Drill-through machine reports  

---

## 🔧 Data Modeling & DAX

Sample DAX Measures:

```DAX
Defect Rate = DIVIDE(SUM(Production[Defective Units]), SUM(Production[Production Count]))
Machine Efficiency = 1 - (SUM(Production[Downtime (min)]) / 1440)
Total Production = SUM(Production[Production Count])
Insights & Outcomes

Identified peak and low-performance shifts

Detected machines with highest downtime

Reduced defect rate opportunities

Improved production planning visibility

📌 Future Enhancements

Real-time IoT data integration

Predictive maintenance using ML

Automated email alerts

Mobile-responsive dashboard

🤝 Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss.

 Author
Shubhanshu Kumar
Power BI & Data Analytics Enthusiast


