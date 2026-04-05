# 🚗 Automobile Sales Recession Dashboard

An interactive data visualization dashboard analyzing historical automobile sales trends during recession and non-recession periods for **XYZAutomotives**. Built with **Plotly** and **Dash**.

---

## 📝 Description

This project was developed as part of the **IBM Data Analyst Professional Certificate** Final Assignment. The goal is to analyze how automobile sales at **XYZAutomotives** were affected during times of economic recession between **1980 and 2013**.

The analysis explores key economic indicators such as **GDP**, **unemployment rate**, **consumer confidence**, and **advertising expenditure**, and how they correlate with automobile sales across different **vehicle types** and **time periods**.

The final deliverable is a fully interactive **Plotly Dash dashboard** with two report views:
- 📅 **Yearly Statistics** — for exploring sales trends year by year
- 📉 **Recession Statistics** — for understanding the impact of economic downturns on automobile sales

---

## 📊 Dashboard Overview

The dashboard contains two main report sections:

### 1. Yearly Automobile Sales Statistics
Explore automobile sales trends for any selected year (1980–2013):
- **Yearly Automobile Sales** — Line chart showing average sales across the entire period
- **Total Monthly Automobile Sales** — Line chart displaying monthly totals for the selected year
- **Average Vehicles Sold by Vehicle Type** — Bar chart breaking down sales by vehicle type
- **Total Advertisement Expenditure by Vehicle Type** — Pie chart showing ad spend distribution

### 2. Recession Period Statistics
Understand how recessions impacted automobile sales:
- **Average Automobile Sales Fluctuation (Year-wise)** — Line chart of average sales during recession years
- **Average Vehicles Sold by Vehicle Type** — Bar chart comparing vehicle type performance during recessions
- **Total Expenditure Share by Vehicle Type** — Pie chart of advertising spend during recession periods
- **Effect of Unemployment Rate on Vehicle Type & Sales** — Bar chart revealing unemployment's impact on sales

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| `Python` | Core programming language |
| `Pandas` | Data manipulation and analysis |
| `Plotly` | Interactive chart creation |
| `Dash` | Web dashboard framework |
| `Seaborn` | Statistical data visualization |
| `Matplotlib` | Supporting visualizations |

---

## 📁 Project Structure

```
automobile-sales-recession-dashboard/
│
├── data/
│   └── automobile_sales.csv        # Dataset (1980–2013)
│
├── assets/
│   └── style.css                   # Dashboard styling
│
├── notebooks/
│   └── EDA.ipynb                   # Exploratory Data Analysis
│
├── dashboard.py                    # Main Dash application
├── requirements.txt                # Python dependencies
└── README.md
```

---

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/automobile-sales-recession-dashboard.git
cd automobile-sales-recession-dashboard
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the dashboard**
```bash
python dashboard.py
```

4. **Open in browser**
```
http://127.0.0.1:8050/
```

---

## 📈 Dataset

The dataset covers automobile sales data from **1980 to 2013** and includes the following key columns:

| Column | Description |
|---|---|
| `Year` | Year of record |
| `Month` | Month of record |
| `Recession` | 1 = Recession period, 0 = Non-recession |
| `Automobile_Sales` | Number of vehicles sold |
| `Vehicle_Type` | Category of vehicle |
| `Advertising_Expenditure` | Ad spend for that period |
| `Consumer_Confidence` | Consumer confidence index |
| `Seasonality_Weight` | Seasonal impact factor |
| `unemployment_rate` | Unemployment rate |
| `GDP` | Gross Domestic Product |

---

## 🔍 Key Insights

- **Executive and Sports cars** are most severely impacted during recessions
- **SuperMiniCar** retains the highest sales resilience during economic downturns
- **Advertising expenditure** remains relatively stable regardless of recession
- **Consumer confidence** shows a positive correlation with automobile sales
- **GDP and unemployment rate** are strong indicators of sales fluctuation

---

## 🧠 Skills Demonstrated

- Data wrangling and preprocessing with Pandas
- Exploratory Data Analysis (EDA)
- Interactive dashboard development with Plotly & Dash
- Statistical visualization with Seaborn & Matplotlib
- Recession period analysis and economic trend interpretation

---

## 📝 License

This project was developed as part of the **IBM Data Analyst Professional Certificate** Final Assignment.

---

## 🙋 Author

**Your Name**
- GitHub: [@ibr5500](https://github.com/ibr5500)
- LinkedIn: [Ibrahim Ahmat](https://www.linkedin.com/in/ibrahim-ahmat/)
