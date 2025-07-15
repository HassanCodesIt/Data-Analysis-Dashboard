# Data Analysis Dashboard

A modern, interactive dashboard for data analysis and visualization built with **Flask**, **Pandas**, **Plotly**, and **Bootstrap 5**.

## 🚀 Features

- **Upload CSV/XLSX** files and preview data
- **Flexible filtering, grouping, and aggregation**
- **Multiple chart types**: Bar, Column, Line, Pie, Donut, Scatter, Bubble, Histogram, Box, Heatmap, Area, Stacked Area, Radar, Funnel, Treemap
- **Top N + 'Other'** logic for readable charts
- **Drilldown**: Click "Other" in Pie/Bar charts to see a breakdown
- **Export** filtered data and charts (CSV, Excel, PNG)
- **Modern UI**: Responsive, beautiful Bootstrap 5 design
- **Loading animations** for chart generation
- **No page reloads** for drilldown (AJAX/Plotly)

## 🏗️ Project Structure

```
project_root/
├── app.py
├── requirements.txt
├── README.md
├── /uploads/                # Uploaded datasets
├── /templates/              # HTML templates
├── /static/                 # CSS/JS assets
```

## ⚡ Quickstart

1. **Clone the repo:**
   ```bash
   git clone https://github.com/HassanCodesIt/Data-Analysis-Dashboard.git
   cd Data-Analysis-Dashboard
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run locally:**
   ```bash
   python app.py
   # or for production
   gunicorn -w 4 app:app
   ```
4. **Open in browser:**
   [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## ✨ Usage
- Upload your CSV/XLSX file
- Preview and analyze data
- Choose chart types and customize axes, grouping, and Top N
- Click "Other" in Pie/Bar charts for drilldown
- Export data and charts as needed

## 🌐 Deployment
- Use **gunicorn** for production: `gunicorn -w 4 app:app`
- Deploy on Heroku, Render, or any cloud platform supporting Flask + Gunicorn

## 🧑‍💻 Tech Stack
- Flask, Pandas, Plotly, Matplotlib, Seaborn
- Bootstrap 5, HTML, CSS, JS
- Gunicorn (production server)

## 📄 License
MIT 