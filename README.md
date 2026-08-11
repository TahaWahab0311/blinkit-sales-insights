# 🛒 Blinkit Sales Insights

Exploratory Data Analysis (EDA) of **Blinkit** sales data — uncovering key business KPIs and sales patterns across product types, fat content, and outlet characteristics using Python.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-3776AB)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Overview

This project analyzes Blinkit's sales dataset to answer key business questions such as:

- What are the overall sales KPIs (total sales, average sales, items sold, average rating)?
- How do sales vary by **item fat content** and **item type**?
- Which **outlet size**, **location tier**, and **establishment year** drive the most sales?
- How does fat content preference differ across outlet location tiers?

The notebook walks through data cleaning, KPI computation, and visualization — similar to what you'd build for a business intelligence dashboard.

---

## 📂 Dataset

The analysis uses `blinkit_data.csv`, containing fields such as:

| Column | Description |
|---|---|
| `Item Fat Content` | Low Fat / Regular (cleaned from inconsistent labels) |
| `Item Type` | Product category |
| `Sales` | Sales value |
| `Rating` | Customer rating |
| `Outlet Size` | Small / Medium / High |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 |
| `Outlet Establishment Year` | Year the outlet was established |

> ⚠️ Note: The dataset is not included in this repo. Add your own `blinkit_data.csv` inside a `data/` folder and update the file path in the notebook before running.

---

## 🔑 Key KPIs Calculated

- 💰 **Total Sales**
- 📈 **Average Sales**
- 📦 **Number of Items Sold**
- ⭐ **Average Rating**

---

## 📊 Visualizations

The notebook generates the following charts:

1. **Sales by Fat Content** — Pie chart
2. **Sales by Item Type** — Bar chart
3. **Fat Content by Outlet Location Tier** — Grouped bar chart
4. **Sales by Outlet Establishment Year** — Line chart
5. **Sales by Outlet Size** — Pie chart
6. **Sales by Outlet Location Type** — Horizontal bar chart (Seaborn)

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** & **NumPy** — data manipulation
- **Matplotlib** & **Seaborn** — data visualization
- **Jupyter Notebook**

---

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/blinkit-sales-insights.git
   cd blinkit-sales-insights
   ```

2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Add your dataset (`blinkit_data.csv`) and update the file path in the notebook.

4. Launch the notebook
   ```bash
   jupyter notebook blinkit.ipynb
   ```

---

## 📈 Sample Insight

> Sales are fairly evenly distributed across outlet location tiers, with **Low Fat** items consistently outperforming **Regular** items across all outlet tiers — highlighting a clear customer preference trend.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open a PR or issue.

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star!
